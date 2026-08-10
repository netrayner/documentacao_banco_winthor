# 📊 Tabela: PCRATEIOCONTABILCC

### Estrutura de Colunas e Restrições

            Tabela            Coluna Tipo/Tamanho                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRATEIOCONTABILCC         CODFILIAL  VARCHAR2(2)                                                                                      Código filial do rateio    CHAVE PRIMÁRIA (PK)                        NaN
PCRATEIOCONTABILCC    NUMTRANSLANCTO NUMBER(38,0)                                                                                  Núm. Trans. Lancto contábil    CHAVE PRIMÁRIA (PK)                        NaN
PCRATEIOCONTABILCC CODIGOCENTROCUSTO VARCHAR2(40)                                                                                    Código do centro de custo    CHAVE PRIMÁRIA (PK)                        NaN
PCRATEIOCONTABILCC          NATUREZA  VARCHAR2(1)                                                                              Natureza do lançamento contábil            OPERACIONAL                        NaN
PCRATEIOCONTABILCC             VALOR NUMBER(22,2)                                                                                              Valor do rateio            OPERACIONAL                        NaN
PCRATEIOCONTABILCC        PERCRATEIO NUMBER(10,6)                                                                                         Percentual do rateio            OPERACIONAL                        NaN
PCRATEIOCONTABILCC    LOTEIMPORTACAO NUMBER(10,0) Campo usando para rastrear um lote de importação feito pela rotina 2127, este valor vem da DFSEQ_IMPCONTABIL            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*