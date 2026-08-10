# 📊 Tabela: PCRATEIOCONTABILCR

### Estrutura de Colunas e Restrições

            Tabela              Coluna Tipo/Tamanho                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRATEIOCONTABILCR           CODFILIAL  VARCHAR2(2)                                                                                               Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCRATEIOCONTABILCR      NUMTRANSLANCTO NUMBER(38,0)                                                                     Número do transação que gerou o lançamento    CHAVE PRIMÁRIA (PK)                        NaN
PCRATEIOCONTABILCR CODIGOCENTRORECEITA VARCHAR2(40)                                                                                    Código do centro de receita    CHAVE PRIMÁRIA (PK)                        NaN
PCRATEIOCONTABILCR            NATUREZA  VARCHAR2(1)                                                                                           Natureza da operação            OPERACIONAL                        NaN
PCRATEIOCONTABILCR               VALOR NUMBER(22,2)                                                                                            Valor do lançamento            OPERACIONAL                        NaN
PCRATEIOCONTABILCR          PERCRATEIO NUMBER(10,6)                                                                                           Percentual de rateio            OPERACIONAL                        NaN
PCRATEIOCONTABILCR      LOTEIMPORTACAO NUMBER(10,0) Campo usando para rastrear um lote de importação feito pela rotina 2127, este valor vem da DFSEQ_IMPCONTABILCR            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*