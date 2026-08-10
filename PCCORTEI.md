# 📊 Tabela: PCCORTEI

### Estrutura de Colunas e Restrições

  Tabela          Coluna Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCORTEI         CODPROD  NUMBER(6,0)                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCORTEI      QTSEPARADA  NUMBER(8,2)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI       QTCORTADA  NUMBER(8,2)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI            DATA         DATE                                                    NaN            OPERACIONAL                        NaN
PCCORTEI          NUMCAR  NUMBER(8,0)                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCORTEI         CODFUNC  NUMBER(8,0)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI          NUMPED NUMBER(10,0)                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCORTEI          PVENDA NUMBER(12,3)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI     CODFUNCCONF  NUMBER(8,0)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI      CODFUNCSEP  NUMBER(8,0)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI       CODFILIAL  VARCHAR2(2)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI          QTORIG NUMBER(20,6)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI         QTFALTA  NUMBER(8,2)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI          MOTIVO VARCHAR2(80)                             Indica o motivo do corte.             OPERACIONAL                        NaN
PCCORTEI DTFINALCHECKOUT         DATE                                                    NaN            OPERACIONAL                        NaN
PCCORTEI            HORA  NUMBER(2,0)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI          MINUTO  NUMBER(2,0)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI          CODCLI  NUMBER(6,0)             Cliente do pedido onde foi lançado corte.             OPERACIONAL                        NaN
PCCORTEI         CODUSUR  NUMBER(4,0)                 RCA do pedido onde foi lançado corte.             OPERACIONAL                        NaN
PCCORTEI       CODROTINA  NUMBER(6,0)      Indica a rotina que efetuou o processo de corte.             OPERACIONAL                        NaN
PCCORTEI       CONDVENDA  NUMBER(5,0)                           Indica a condição de venda.             OPERACIONAL                        NaN
PCCORTEI  CODEMITENTEPED  NUMBER(8,0)                                                    NaN            OPERACIONAL                        NaN
PCCORTEI         NUMLOTE VARCHAR2(15)                                         numero do lote            OPERACIONAL                        NaN
PCCORTEI          NUMSEQ NUMBER(20,0)                                       Número sequência    CHAVE PRIMÁRIA (PK)                        NaN
PCCORTEI       TIPOCORTE  VARCHAR2(1) Gravar o itpo do corte: "C" - Corte ou "D" - Depuração            OPERACIONAL                        NaN
PCCORTEI      DTMXSALTER         DATE                                                    NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*