# 📊 Tabela: PCSALDO

### Estrutura de Colunas e Restrições

 Tabela                   Coluna Tipo/Tamanho                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDO                CODFILIAL  VARCHAR2(2)                                                                                   Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDO            CODPLANOCONTA  NUMBER(5,0)                                                                          Indica o código do plano de contas.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDO                      MES  NUMBER(2,0)                                                                                  Indica o mês do lançamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDO                      ANO  NUMBER(4,0)                                                                                  Indica o ano do lançamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDO           CODREDUZIDO_PC VARCHAR2(12)                                                                                    Indica o código reduzido.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDO              VALORDEBITO NUMBER(22,2)                                                                                    Indica o valor do débito.            OPERACIONAL                        NaN
PCSALDO             VALORCREDITO NUMBER(22,2)                                                                                   Indica o valor do crédito.            OPERACIONAL                        NaN
PCSALDO       VLRDEBENCERRAMENTO NUMBER(22,2)                                                                          Indica o valor débito encerramento.            OPERACIONAL                        NaN
PCSALDO       VLRCREENCERRAMENTO NUMBER(22,2)                                                                         Indica o valor crédito encerramento.            OPERACIONAL                        NaN
PCSALDO             VLRDEBCONCIL NUMBER(22,2)                                                                          Indica o valor de débito conciliado            OPERACIONAL                        NaN
PCSALDO             VLRCRECONCIL NUMBER(22,2)                                                                         Indica o valor de crédito conciliado            OPERACIONAL                        NaN
PCSALDO VLRDEBCONCILENCERRAMENTO NUMBER(22,2)                                          Indica o valor de débito conciliado levando em conta o encerramento            OPERACIONAL                        NaN
PCSALDO VLRCRECONCILENCERRAMENTO NUMBER(22,2)                                         Indica o valor de crédito conciliado levando em conta o encerramento            OPERACIONAL                        NaN
PCSALDO           LOTEIMPORTACAO NUMBER(10,0) Campo usando para rastrear um lote de importação feito pela rotina 2127, este valor vem da DFSEQ_IMPCONTABIL            OPERACIONAL                        NaN
PCSALDO         CODCONFEXERCICIO  NUMBER(8,0)                                                                                          Código do Exercício            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*