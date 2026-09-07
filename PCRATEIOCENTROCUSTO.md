# 📊 Tabela: PCRATEIOCENTROCUSTO

### Estrutura de Colunas e Restrições

             Tabela            Coluna  Tipo/Tamanho                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRATEIOCENTROCUSTO            RECNUM   NUMBER(8,0)                                                                     Número do lançamento.            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO          CODCONTA  NUMBER(10,0)                                                                Código da Conta Gerencial.            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO    CODCENTROCUSTO  NUMBER(10,0)                                                                Código do Centro de Custo.            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO             VALOR  NUMBER(12,2)                                                                      Valor do lançamento.            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO        PERCRATEIO  NUMBER(10,6)                                                       Percentual de Rateio do lançamento.            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO            DTLANC          DATE                                                                       Data do lançamento.            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO     CONTRAPARTIDA   VARCHAR2(1)                                                            Lançamento teve contra-partida            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO       RECNUMPRINC  NUMBER(10,0)                                                            Número do lançamento principal            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO         CODFILIAL   VARCHAR2(2)                                                       Código da filial do centro de custo            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO CODIGOCENTROCUSTO  VARCHAR2(40)                                                                 Código do centro de custo            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO      ROTINAUPDATE VARCHAR2(100) Campo usado pela trigger TRG_LOG_PCRATEIOCENTROCUSTO para acompanhar alterações na tabela            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO      ROTINAINSERT VARCHAR2(100) Campo usado pela trigger TRG_LOG_PCRATEIOCENTROCUSTO para acompanhar alterações na tabela            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO CODFUNCAUTSUPLORC   NUMBER(8,0)                                 CODIGO FUNCIONARIO AUTORIZACAO SUPLEMENTACAO ORCAMENTARIA            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO    DATAAUTSUPLORC          DATE                                               DATA AUTORIZACAO SUPLEMENTACAO ORCAMENTARIA            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO ORCAMENTOEXCEDIDO   VARCHAR2(1)                             IDENTIFICA QUAL CENTRO DE CUSTO DO RATEIO EXCEDEU O ORÇAMENTO            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO NUMTRANSPISCOFINS  NUMBER(10,0)                                                         Numero de transação do PISCONFINS            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO         RECNUMREF  NUMBER(10,0)                                                          Recnum ao que o imposto pertence            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO    PERCRATCONTREF  NUMBER(10,6)                                             Percentual da conta ao que o imposto pertence            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO          TIPOTRIB  VARCHAR2(20)                                                                           Tipo do tributo            OPERACIONAL                        NaN
PCRATEIOCENTROCUSTO     LANCIMPRETIDO   VARCHAR2(1)                                               Indica se é um lançamento de imposto retido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*