# 📊 Tabela: PCLOGCUSTO

### Estrutura de Colunas e Restrições

    Tabela                Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCUSTO               CODPROD   NUMBER(6,0)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO               CODFUNC   NUMBER(8,0)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO          CUSTOCONTANT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO          CUSTOREALANT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO           CUSTOFINANT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO           CUSTOREPANT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO        CUSTOULTENTANT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO        VALORULTENTANT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO                  DATA          DATE                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO                ROTINA  VARCHAR2(40)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO             CUSTOCONT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO             CUSTOREAL  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO              CUSTOFIN  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO              CUSTOREP  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO           CUSTOULTENT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO           VALORULTENT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO             CODFILIAL   VARCHAR2(2)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO                RECNUM   NUMBER(8,0)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO     CUSTOULTENTFINANT  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO        CUSTOULTENTFIN  NUMBER(18,6)                                                 NaN            OPERACIONAL                        NaN
PCLOGCUSTO                   OBS VARCHAR2(100)                                Indica a observação.            OPERACIONAL                        NaN
PCLOGCUSTO       CUSTOPROXCOMPRA  NUMBER(18,6)                   Indica o custo da próxima compra.            OPERACIONAL                        NaN
PCLOGCUSTO    CUSTOPROXCOMPRAANT  NUMBER(18,6)          Indica o custo da próxima compra anterior.            OPERACIONAL                        NaN
PCLOGCUSTO           CUSTOFORNEC  NUMBER(18,6)                       Indica o custo do fornecedor.            OPERACIONAL                        NaN
PCLOGCUSTO        CUSTOFORNECANT  NUMBER(18,6)              Indica o custo do fornecedor anterior.            OPERACIONAL                        NaN
PCLOGCUSTO     CUSTOULTPEDCOMPRA  NUMBER(18,6)          Indica o custo do último pedido de compra.            OPERACIONAL                        NaN
PCLOGCUSTO  CUSTOULTPEDCOMPRAANT  NUMBER(18,6) Indica o custo do último pedido de compra anterior.            OPERACIONAL                        NaN
PCLOGCUSTO                NUMFCI  VARCHAR2(36)                    Ficha de Conteúdo de Importação.            OPERACIONAL                        NaN
PCLOGCUSTO       VLPARCELAIMPFCI  NUMBER(18,6)                         Valor da Parcela Importada.            OPERACIONAL                        NaN
PCLOGCUSTO    PERCCONTEUDOIMPFCI   NUMBER(5,2)                             Conteúdo de Importação.            OPERACIONAL                        NaN
PCLOGCUSTO       VLIMPORTACAOFCI  NUMBER(18,6)                                Valor de Importação.            OPERACIONAL                        NaN
PCLOGCUSTO             NUMFCIANT  VARCHAR2(36)           Ficha de Conteúdo de Importação Anterior.            OPERACIONAL                        NaN
PCLOGCUSTO    VLPARCELAIMPFCIANT  NUMBER(18,6)                Valor da Parcela Importada Anterior.            OPERACIONAL                        NaN
PCLOGCUSTO PERCCONTEUDOIMPFCIANT   NUMBER(5,2)                    Conteúdo de Importação Anterior.            OPERACIONAL                        NaN
PCLOGCUSTO    VLIMPORTACAOFCIANT  NUMBER(18,6)                       Valor de Importação Anterior.            OPERACIONAL                        NaN
PCLOGCUSTO           CUSTOFISCAL  NUMBER(18,6)                                        CUSTO FISCAL            OPERACIONAL                        NaN
PCLOGCUSTO        CUSTOFISCALANT  NUMBER(18,6)                               CUSTO FISCAL ANTERIOR            OPERACIONAL                        NaN
PCLOGCUSTO     CUSTOULTENTFISCAL  NUMBER(18,6)                         CUSTO ULTIMA ENTRADA FISCAL            OPERACIONAL                        NaN
PCLOGCUSTO  CUSTOULTENTFISCALANT  NUMBER(18,6)                CUSTO ULTIMA ENTRADA FISCAL ANTERIOR            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*