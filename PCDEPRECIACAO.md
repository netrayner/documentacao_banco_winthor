# 📊 Tabela: PCDEPRECIACAO

### Estrutura de Colunas e Restrições

       Tabela                      Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEPRECIACAO                   CODFILIAL  VARCHAR2(2)                                          Indica o código filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPRECIACAO              SEQDEPRECIACAO NUMBER(10,0)                              Indica a sequencial da depreciação.    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPRECIACAO                         MES  NUMBER(2,0)                                         Indica o mês depreciado.    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPRECIACAO                         ANO  NUMBER(4,0)                                         Indica o ano depreciado.    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPRECIACAO                NUMTRANSACAO NUMBER(10,0)                                    Indica o número da transação.            OPERACIONAL                        NaN
PCDEPRECIACAO               TIPOTRANSACAO  VARCHAR2(2)                                      Indica o tipo da transação.            OPERACIONAL                        NaN
PCDEPRECIACAO                     CODPROD  NUMBER(6,0)                                          Indica o código do bem.            OPERACIONAL                        NaN
PCDEPRECIACAO          DATAULTDEPRECIACAO         DATE                             Indica a data da ultima depreciação.            OPERACIONAL                        NaN
PCDEPRECIACAO          VLRDEPRECACUMULADA NUMBER(18,2)                         Indica o valor da depreciação acumulado.            OPERACIONAL                        NaN
PCDEPRECIACAO                    VALORBEM NUMBER(18,2)                                           Indica o valor do bem.            OPERACIONAL                        NaN
PCDEPRECIACAO                VLRDEPRECMES NUMBER(18,2)                                Indica o valor depreciado do mês.            OPERACIONAL                        NaN
PCDEPRECIACAO                    BEMSALVO  VARCHAR2(1)                                   Indica se o calculo foi salvo.            OPERACIONAL                        NaN
PCDEPRECIACAO           NUMLANCTOCONTABIL NUMBER(38,0)                                     Indica número do lançamento.            OPERACIONAL                        NaN
PCDEPRECIACAO          QTDDIASDEPRECIADOS  NUMBER(6,0)                                  Quantidade de dias depreciados.            OPERACIONAL                        NaN
PCDEPRECIACAO         SEQBENSPATRIMONIAIS NUMBER(10,0)                                Sequência do bem individualizado.            OPERACIONAL                        NaN
PCDEPRECIACAO           VALORCORRIGIDOBEM NUMBER(18,2)                                  Indica o Valor corrigido do bem            OPERACIONAL                        NaN
PCDEPRECIACAO VLRDEPRECACUMULADACORRIGIDO NUMBER(18,2)      Indica o valor da depreciação acumulado do valor corrigido.            OPERACIONAL                        NaN
PCDEPRECIACAO       VLRDEPRECMESCORRIGIDO NUMBER(18,2) Indica o valor depreciado do mês sobre o valor corrigido do bem.            OPERACIONAL                        NaN
PCDEPRECIACAO  NUMLANCTOCONTABILCORRIGIDO NUMBER(38,0)                     Núm. Lançamento contábil por Valor Corrigido            OPERACIONAL                        NaN
PCDEPRECIACAO  NUMLANCTOCONTABILATRIBUIDO NUMBER(38,0)                     Núm. Lançamento contábil por Valor Atribuído            OPERACIONAL                        NaN
PCDEPRECIACAO           VALORATRIBUIDOBEM NUMBER(18,2)                                  Indica o Valor Atribuído do bem            OPERACIONAL                        NaN
PCDEPRECIACAO VLRDEPRECACUMULADAATRIBUIDO NUMBER(18,2)      Indica o valor da depreciação acumulado do valor atribuído.            OPERACIONAL                        NaN
PCDEPRECIACAO       VLRDEPRECMESATRIBUIDO NUMBER(18,2) Indica o valor depreciado do mês sobre o valor atribuído do bem.            OPERACIONAL                        NaN
PCDEPRECIACAO         TIPOCALCDEPRECIACAO  VARCHAR2(2)                                    Tipo do cáculo de depreciação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*