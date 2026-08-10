# 📊 Tabela: PCCONTA

### Estrutura de Colunas e Restrições

 Tabela                     Coluna   Tipo/Tamanho                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTA                   CODCONTA   NUMBER(10,0)                                                                             NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTA                      CONTA   VARCHAR2(40)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA                 GRUPOCONTA    NUMBER(4,0)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA             CODCONTAMASTER   NUMBER(10,0)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA                       TIPO    VARCHAR2(1)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA               INVESTIMENTO    VARCHAR2(1)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA                    BONIFIC    VARCHAR2(1)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA                  VLORCAMES   NUMBER(14,2)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA               FIXAVARIAVEL    VARCHAR2(1)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA         GERAPROVLANCCONTAB    VARCHAR2(1)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA      CODCONTACONTRAPARTIDA   NUMBER(10,0)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA       USARATEIOCENTROCUSTO    VARCHAR2(1)                                                 Usa rateio por Centro de Custo?            OPERACIONAL                        NaN
PCCONTA       CODCENTROCUSTOPADRAO   NUMBER(10,0)                                                Código do Centro de Custo Padrão            OPERACIONAL                        NaN
PCCONTA                      VERBA    VARCHAR2(1)                                                        Conta contábil de verba.            OPERACIONAL                        NaN
PCCONTA              CONTACONTABIL   VARCHAR2(12)                                                                             NaN            OPERACIONAL                        NaN
PCCONTA          CODEVENTOINTFOLHA VARCHAR2(1000)                                                          Cód. Evento folha - RM            OPERACIONAL                        NaN
PCCONTA           CODSECAOINTFOLHA   VARCHAR2(50)                                                Código da seção integração folha            OPERACIONAL                        NaN
PCCONTA      RESTRINGIRNOBALANCETE    VARCHAR2(1) Campo que define a restricao de apresentacao da conta no balancete (rotina 124)            OPERACIONAL                        NaN
PCCONTA UTILIZACENTROCUSTORESTRITO    VARCHAR2(2)                          Indica se a conta utiliza restrição de centro de custo            OPERACIONAL                        NaN
PCCONTA          PRESTACAODECONTAS    VARCHAR2(1)                                                 É conta de prestação de contas?            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*