# 📊 Tabela: PCEMAILNFE

### Estrutura de Colunas e Restrições

    Tabela       Coluna   Tipo/Tamanho                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMAILNFE    CODFILIAL    VARCHAR2(2)                                                                     Códifo da filial da NF            OPERACIONAL                        NaN
PCEMAILNFE     CHAVENFE   VARCHAR2(44)                                                                  Chave NF-e da nota fiscal            OPERACIONAL                        NaN
PCEMAILNFE    TIPOENVIO    VARCHAR2(1)                                       Tipo do envio (E - Emissão / C - Cancelamento) da NF            OPERACIONAL                        NaN
PCEMAILNFE        EMAIL  VARCHAR2(200)                                                                       E-mail a ser enviado            OPERACIONAL                        NaN
PCEMAILNFE   DTINCLUSAO           DATE                                                          Data da inclusão do email na fila            OPERACIONAL                        NaN
PCEMAILNFE      TIPOMOV    VARCHAR2(1)                                                                           Entrada ou Saida            OPERACIONAL                        NaN
PCEMAILNFE NUMTRANSACAO   NUMBER(10,0)                                              Número da transação da nota no banco de dados            OPERACIONAL                        NaN
PCEMAILNFE      NUMNOTA   NUMBER(10,0)                                                           Número da nota no banco de dados            OPERACIONAL                        NaN
PCEMAILNFE DESTINATARIO   VARCHAR2(60)                                                              Nome do destinatário do email            OPERACIONAL                        NaN
PCEMAILNFE       ORIGEM   VARCHAR2(60)                                      Origem do email (Cliente, Transportadora, Redespacho)            OPERACIONAL                        NaN
PCEMAILNFE   PROCESSADO    VARCHAR2(1) Utilizado para controle de envio de email (S - PROCESSANDO, N - REGISTRO LIVRE PARA ENVIO)            OPERACIONAL                        NaN
PCEMAILNFE     MENSAGEM VARCHAR2(1000)                                                            Mensagem sobre o envio do email            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*