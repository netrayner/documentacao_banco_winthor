# 📊 Tabela: PCRATEIOCENTROCUSTOPCLANC3

### Estrutura de Colunas e Restrições

                    Tabela            Coluna  Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRATEIOCENTROCUSTOPCLANC3            NUMPED  NUMBER(10,0)    Número do pedido da tabela PCLANC3            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTOPCLANC3             PREST   VARCHAR2(3) Prestação do pedido da tabela PCLANC3            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTOPCLANC3          CODCONTA  NUMBER(10,0)             Código da conta gerencial            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTOPCLANC3             VALOR  NUMBER(12,2)                   Valor do lançamento            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTOPCLANC3        PERCRATEIO  NUMBER(10,6)    Percentual de rateio do lançamento            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTOPCLANC3            DTLANC          DATE                    Data do lançamento            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTOPCLANC3         CODFILIAL   VARCHAR2(2)   Código da filial do centro de custo            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTOPCLANC3 CODIGOCENTROCUSTO  VARCHAR2(40)             Código do centro de custo            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTOPCLANC3      ROTINAINSERT VARCHAR2(100)   Rotina que fez o insert do registro            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTOPCLANC3      ROTINAUPDATE VARCHAR2(100)   Rotina que fez o update no registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*