# 📊 Tabela: PCLANCINTERMEDIARIACC

### Estrutura de Colunas e Restrições

               Tabela              Coluna   Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLANCINTERMEDIARIACC NUMTRANSCENTROCUSTO   NUMBER(12,0)                             Núm. Trans. Centro custo            OPERACIONAL                        NaN
PCLANCINTERMEDIARIACC           CODFILIAL    VARCHAR2(2)                                          Cód. Filial            OPERACIONAL                        NaN
PCLANCINTERMEDIARIACC   CODIGOCENTROCUSTO   VARCHAR2(40)                            Código do centro de custo            OPERACIONAL                        NaN
PCLANCINTERMEDIARIACC               VALOR   NUMBER(12,2)                        Valor de rateio do lançamento            OPERACIONAL                        NaN
PCLANCINTERMEDIARIACC      NUMTRANSLANCTO   NUMBER(38,0) Número do lançamento contabil da PCLANCINTERMEDIARIA            OPERACIONAL                        NaN
PCLANCINTERMEDIARIACC    AGRUPALANCAMENTO VARCHAR2(2000)            Agrupamento utilizado totalizador da 2130            OPERACIONAL                        NaN
PCLANCINTERMEDIARIACC          PERCRATEIO    NUMBER(9,6)                                                  NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*