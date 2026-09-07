# 📊 Tabela: PCEMAILDFEENVIADO

### Estrutura de Colunas e Restrições

           Tabela       Coluna   Tipo/Tamanho                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMAILDFEENVIADO NUMTRANSACAO   NUMBER(10,0)                                                                  Número de transação do DFe    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILDFEENVIADO      TIPOMOV    VARCHAR2(1)                                                             Flag de Entrada ou Saída(E e S)    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILDFEENVIADO    CODFILIAL    VARCHAR2(2)                                                                     Código da filial do DFe            OPERACIONAL                        NaN
PCEMAILDFEENVIADO      TIPODOC    VARCHAR2(4)                                                      Tipo do documento(NFe, CTe, CCe, MDFe)            OPERACIONAL                        NaN
PCEMAILDFEENVIADO    TIPOENVIO    VARCHAR2(1)                                       Tipo do envio (E - Emissão / C - Cancelamento) do DFe    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILDFEENVIADO        EMAIL   VARCHAR2(80)                                                                      E-mail do destinatário    CHAVE PRIMÁRIA (PK)                        NaN
PCEMAILDFEENVIADO      NUMNOTA   VARCHAR2(10)                                                                               Número do DFe            OPERACIONAL                        NaN
PCEMAILDFEENVIADO     CHAVEDFE   VARCHAR2(55)                                                                                Chave do DFe            OPERACIONAL                        NaN
PCEMAILDFEENVIADO DESTINATARIO  VARCHAR2(100)                                                              Nome do destinatário do e-mail            OPERACIONAL                        NaN
PCEMAILDFEENVIADO       ORIGEM   VARCHAR2(60)                                      Origem do e-mail (Cliente, Transportadora, Redespacho)            OPERACIONAL                        NaN
PCEMAILDFEENVIADO   PROCESSADO    VARCHAR2(1) Utilizado para controle de envio de e-mail (S - PROCESSANDO, N - REGISTRO LIVRE PARA ENVIO)            OPERACIONAL                        NaN
PCEMAILDFEENVIADO     MENSAGEM VARCHAR2(1000)                                                            Mensagem sobre o envio do e-mail            OPERACIONAL                        NaN
PCEMAILDFEENVIADO   DTINCLUSAO           DATE                                                          Data da inclusão do e-mail na fila            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*