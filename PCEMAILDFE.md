# 📊 Tabela: PCEMAILDFE

### Estrutura de Colunas e Restrições

    Tabela       Coluna   Tipo/Tamanho                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMAILDFE NUMTRANSACAO   NUMBER(10,0)                                                                  Número de transação do DFe    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILDFE      TIPOMOV    VARCHAR2(1)                                                             Flag de Entrada ou Saída(E e S)    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILDFE    CODFILIAL    VARCHAR2(2)                                                                     Código da filial do DFe            OPERACIONAL                        NaN
PCEMAILDFE      TIPODOC    VARCHAR2(4)                                                      Tipo do documento(NFe, CTe, CCe, MDFe)            OPERACIONAL                        NaN
PCEMAILDFE    TIPOENVIO    VARCHAR2(1)                                       Tipo do envio (E - Emissão / C - Cancelamento) do DFe    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILDFE        EMAIL   VARCHAR2(80)                                                                      E-mail do destinatário    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILDFE      NUMNOTA   VARCHAR2(10)                                                                               Número do DFe            OPERACIONAL                        NaN
PCEMAILDFE     CHAVEDFE   VARCHAR2(55)                                                                                Chave do DFe            OPERACIONAL                        NaN
PCEMAILDFE DESTINATARIO  VARCHAR2(100)                                                              Nome do destinatário do e-mail            OPERACIONAL                        NaN
PCEMAILDFE       ORIGEM   VARCHAR2(60)                                      Origem do e-mail (Cliente, Transportadora, Redespacho)            OPERACIONAL                        NaN
PCEMAILDFE   PROCESSADO    VARCHAR2(1) Utilizado para controle de envio de e-mail (S - PROCESSANDO, N - REGISTRO LIVRE PARA ENVIO)            OPERACIONAL                        NaN
PCEMAILDFE     MENSAGEM VARCHAR2(1000)                                                            Mensagem sobre o envio do e-mail            OPERACIONAL                        NaN
PCEMAILDFE   DTINCLUSAO           DATE                                                          Data da inclusão do e-mail na fila            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*