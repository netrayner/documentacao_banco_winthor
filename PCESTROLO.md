# 📊 Tabela: PCESTROLO

### Estrutura de Colunas e Restrições

   Tabela    Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTROLO CODFILIAL  VARCHAR2(2)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCESTROLO   NUMROLO VARCHAR2(10)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCESTROLO   CODPROD  NUMBER(6,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCESTROLO        QT NUMBER(16,3)                                  NaN            OPERACIONAL                        NaN
PCESTROLO   NUMLOTE VARCHAR2(15)             Indica o número do lote.            OPERACIONAL                        NaN
PCESTROLO    DTVENC         DATE Indica a data de vencimento do lote.            OPERACIONAL                        NaN
PCESTROLO    CODCOR NUMBER(10,0)                        Código da Cor            OPERACIONAL                        NaN
PCESTROLO  QTESTMIN NUMBER(22,8)               Qtde minima de estoque            OPERACIONAL                        NaN
PCESTROLO   OBSLOTE VARCHAR2(40)                   Observação do lote            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*