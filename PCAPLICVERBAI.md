# 📊 Tabela: PCAPLICVERBAI

### Estrutura de Colunas e Restrições

       Tabela                       Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAPLICVERBAI                     NUMAPLIC  NUMBER(8,0)                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAPLICVERBAI                    CODFILIAL  VARCHAR2(2)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                     NUMVERBA  NUMBER(8,0)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                      CODPROD  NUMBER(6,0)                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAPLICVERBAI                      DTAPLIC         DATE                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                     CODCONTA NUMBER(10,0)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                     QTESTGER NUMBER(16,3)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                  CUSTOFINANT NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                 CUSTOREALANT NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                      VLAPLIC NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                CUSTOFINATUAL NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI               CUSTOREALATUAL NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                  CUSTOREPANT NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                CUSTOREPATUAL NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI               CUSTOULTENTANT NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI             CUSTOULTENTATUAL NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                      QTVENDA NUMBER(20,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                      VLVENDA NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                VLCUSTOFINANT NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                   VLCUSTOFIN NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI               VLCUSTOREALANT NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                  VLCUSTOREAL NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI            CUSTOREALSEMSTANT NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI          CUSTOREALSEMSTATUAL NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI             DTINICIOVIGENCIA         DATE                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                DTFIMVIGENCIA         DATE                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                    PERCAPLIC NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI              VLAPLICUNITARIO NUMBER(18,6)                 Indica o valor unitário rebaixa CMV.            OPERACIONAL                        NaN
PCAPLICVERBAI        CUSTOPROXIMACOMPRAANT NUMBER(18,6)  Custo da próxima compra antes da aplicação de verba            OPERACIONAL                        NaN
PCAPLICVERBAI      CUSTOPROXIMACOMPRAATUAL NUMBER(18,6)    Custo da próxima compra após a aplicação da verba            OPERACIONAL                        NaN
PCAPLICVERBAI               CUSTOFORNECANT NUMBER(18,6)           Custo fornecedor após a aplicação da verba            OPERACIONAL                        NaN
PCAPLICVERBAI             CUSTOFORNECATUAL NUMBER(18,6)                                                  NaN            OPERACIONAL                        NaN
PCAPLICVERBAI                    CONDVENDA  NUMBER(5,0)                                    Condição de Venda            OPERACIONAL                        NaN
PCAPLICVERBAI             CUSTOFINSEMSTANT NUMBER(18,6)                          Custo financeiro sem ST Ant            OPERACIONAL                        NaN
PCAPLICVERBAI           CUSTOFINSEMSTATUAL NUMBER(18,6)                        Custo financeiro sem ST Atual            OPERACIONAL                        NaN
PCAPLICVERBAI          CUSTOFORNECSEMSTANT NUMBER(18,6)                          Custo fornecedor sem ST Ant            OPERACIONAL                        NaN
PCAPLICVERBAI        CUSTOFORNECSEMSTATUAL NUMBER(18,6)                        Custo fornecedor sem ST Atual            OPERACIONAL                        NaN
PCAPLICVERBAI   CUSTOPROXIMACOMPRASEMSTANT NUMBER(18,6)                      Custo próxima compra sem ST Ant            OPERACIONAL                        NaN
PCAPLICVERBAI CUSTOPROXIMACOMPRASEMSTATUAL NUMBER(18,6)                    Custo próxima compra sem ST Atual            OPERACIONAL                        NaN
PCAPLICVERBAI          CUSTOULTENTSEMSTANT NUMBER(18,6)                      Custo última entrada sem ST Ant            OPERACIONAL                        NaN
PCAPLICVERBAI        CUSTOULTENTSEMSTATUAL NUMBER(18,6)                    Custo última entrada sem ST Atual            OPERACIONAL                        NaN
PCAPLICVERBAI                   ROTINALANC VARCHAR2(13)                         Nome da rotina de lançamento            OPERACIONAL                        NaN
PCAPLICVERBAI                       CODCLI  NUMBER(9,0)                                    Código do cliente            OPERACIONAL                        NaN
PCAPLICVERBAI            CUSTOULTENTFINANT NUMBER(18,6)          Custo da Última Entrada Financeira Anterior            OPERACIONAL                        NaN
PCAPLICVERBAI          CUSTOULTENTFINATUAL NUMBER(18,6)             Custo da Última Entrada Financeira Atual            OPERACIONAL                        NaN
PCAPLICVERBAI       CUSTOULTENTFINSEMSTANT NUMBER(18,6)   Custo da Última Entrada Financeira sem ST Anterior            OPERACIONAL                        NaN
PCAPLICVERBAI     CUSTOULTENTFINSEMSTATUAL NUMBER(18,6)      Custo da Última Entrada Financeira sem ST Atual            OPERACIONAL                        NaN
PCAPLICVERBAI         TIPORATEIOVALORVERBA  VARCHAR2(1)                     Tipo de rateio do valor da verba            OPERACIONAL                        NaN
PCAPLICVERBAI            CODROTINAPOLITICA VARCHAR2(48) Nome/Código da rotina que criou a política comercial            OPERACIONAL                        NaN
PCAPLICVERBAI                  CODPOLITICA NUMBER(10,0)                Código da politica comercial de venda            OPERACIONAL                        NaN
PCAPLICVERBAI                NUMTRANSVENDA NUMBER(10,0)                         Transação de venda de origem            OPERACIONAL                        NaN
PCAPLICVERBAI                       NUMPED NUMBER(10,0)                           Numero do pedido de origem            OPERACIONAL                        NaN
PCAPLICVERBAI                       NUMSEQ NUMBER(20,0)        Numero de sequência da movimentação de origem            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*