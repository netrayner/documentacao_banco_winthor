# 📊 Tabela: PCANALISEDOESTOQUE

### Estrutura de Colunas e Restrições

            Tabela           Coluna   Tipo/Tamanho                                                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCANALISEDOESTOQUE TIPOMOVIMENTACAO  VARCHAR2(100)                                                    Indica o tipo de analise feita no estoque "GERENCIAL" ou "CONTABIL".            OPERACIONAL                        NaN
PCANALISEDOESTOQUE          CODPROD    NUMBER(6,0)                                                                 Indica o código do produto que teve o estoque analisado            OPERACIONAL                        NaN
PCANALISEDOESTOQUE        CODFILIAL    VARCHAR2(2)                                                                 Indica o código da filial que teve o estoque analisado.            OPERACIONAL                        NaN
PCANALISEDOESTOQUE       DTANTERIOR           DATE                                           Indica a data usada como ponto de partida para analise do estoque no período.            OPERACIONAL                        NaN
PCANALISEDOESTOQUE       QTANTERIOR   NUMBER(18,6)                                         Indica a quantidade usada como saldo inicial do estoque para fazer a analisado.            OPERACIONAL                        NaN
PCANALISEDOESTOQUE     QTMOVIMETADA   NUMBER(18,6)                                                                    Indica a quantidade movimentada no perído analisado.            OPERACIONAL                        NaN
PCANALISEDOESTOQUE   QTESTOQUEATUAL   NUMBER(18,6)                       Indica a quantidade de estoque existente na tabela PCEST no nomento que a analise foi finalizada.            OPERACIONAL                        NaN
PCANALISEDOESTOQUE        QTCORRETA   NUMBER(18,6)    Indica a quantidade que deveria esta na tabela PCEST com base no saldo inicial e movimentações do período analisado.            OPERACIONAL                        NaN
PCANALISEDOESTOQUE            QTDIF   NUMBER(18,6) Indica a quantidade que representa a diferênça entre o estoque calculado e o estoque atual (QTCORRETA - QTESTOQUEATUAL)            OPERACIONAL                        NaN
PCANALISEDOESTOQUE       OBSERVACAO VARCHAR2(2000)                                                                                                                     NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*