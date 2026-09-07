# 📊 Tabela: PCMENS

### Estrutura de Colunas e Restrições

Tabela        Coluna   Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENS       CODUSUR    NUMBER(4,0)                                                    NaN            OPERACIONAL                        NaN
PCMENS          DATA           DATE                                                    NaN            OPERACIONAL                        NaN
PCMENS         MENS1   VARCHAR2(60)                                                    NaN            OPERACIONAL                        NaN
PCMENS         MENS2   VARCHAR2(60)                                                    NaN            OPERACIONAL                        NaN
PCMENS         MENS3   VARCHAR2(60)                                                    NaN            OPERACIONAL                        NaN
PCMENS         MENS4   VARCHAR2(60)                                                    NaN            OPERACIONAL                        NaN
PCMENS       ENVIADO    VARCHAR2(1)                                                    NaN            OPERACIONAL                        NaN
PCMENS         MENS5   VARCHAR2(60)                                                    NaN            OPERACIONAL                        NaN
PCMENS         MENS6   VARCHAR2(60)                                                    NaN            OPERACIONAL                        NaN
PCMENS         MENS7   VARCHAR2(60)                                                    NaN            OPERACIONAL                        NaN
PCMENS         MENS8   VARCHAR2(60)                                                    NaN            OPERACIONAL                        NaN
PCMENS  CODFUNCEMITE    NUMBER(8,0)                                                    NaN            OPERACIONAL                        NaN
PCMENS  DATACOMPLETA           DATE Indica a data e hora da mensagem.|Campo do tipo data.             OPERACIONAL                        NaN
PCMENS DATAENVIOMENS           DATE                       Data de envio da mensagem ao Rca            OPERACIONAL                        NaN
PCMENS        CODCLI    NUMBER(6,0)                                      Código do cliente            OPERACIONAL                        NaN
PCMENS      FANTASIA   VARCHAR2(40)                               Nome fantasia do cliente            OPERACIONAL                        NaN
PCMENS        NUMPED   NUMBER(10,0)                                       Numero do pedido            OPERACIONAL                        NaN
PCMENS       CODPROD    NUMBER(6,0)                                      Código do produto            OPERACIONAL                        NaN
PCMENS       QTFALTA   NUMBER(20,6)                                    Quantidade da falta            OPERACIONAL                        NaN
PCMENS         MENS9 VARCHAR2(2048)                                    Campo para mensagem            OPERACIONAL                        NaN
PCMENS     ENVIADOFV        CHAR(1)                                                    NaN            OPERACIONAL                        NaN
PCMENS     ENVIADONV    VARCHAR2(1)                                                    NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*