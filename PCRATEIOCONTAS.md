# 📊 Tabela: PCRATEIOCONTAS

### Estrutura de Colunas e Restrições

        Tabela            Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRATEIOCONTAS            RECNUM  NUMBER(8,0)                     RECNUM do título na PCLANC            OPERACIONAL                        NaN
PCRATEIOCONTAS          CODCONTA NUMBER(10,0)                      Código da conta gerencial            OPERACIONAL                        NaN
PCRATEIOCONTAS             VALOR NUMBER(12,2) Valor rateado de acordo com o percentual usado            OPERACIONAL                        NaN
PCRATEIOCONTAS        PERCRATEIO NUMBER(10,6)                     Percentual usado no rateio            OPERACIONAL                        NaN
PCRATEIOCONTAS            DTLANC         DATE                   Data de lançamento do rateio            OPERACIONAL                        NaN
PCRATEIOCONTAS     CONTRAPARTIDA  VARCHAR2(1)               Indica se houve a contra-partida            OPERACIONAL                        NaN
PCRATEIOCONTAS       RECNUMPRINC NUMBER(10,0)           RECNUM do título principal na PCLANC            OPERACIONAL                        NaN
PCRATEIOCONTAS         CODFILIAL  VARCHAR2(2)  Código da filial pra qual foi gerado o rateio            OPERACIONAL                        NaN
PCRATEIOCONTAS    CODRATEIOCONTA NUMBER(10,0)              Código do rateio de contas padrão            OPERACIONAL                        NaN
PCRATEIOCONTAS       NUMTRANSENT NUMBER(10,0)                 Numero de transação de entrada            OPERACIONAL                        NaN
PCRATEIOCONTAS         RECNUMREF NUMBER(10,0)               Recnum ao que o imposto pertence            OPERACIONAL                        NaN
PCRATEIOCONTAS     LANCIMPRETIDO  VARCHAR2(1)    Indica se é um lançamento de imposto retido            OPERACIONAL                        NaN
PCRATEIOCONTAS          TIPOTRIB VARCHAR2(20)                                Tipo do tributo            OPERACIONAL                        NaN
PCRATEIOCONTAS NUMTRANSPISCOFINS NUMBER(10,0)              Numero de transação do PISCONFINS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*