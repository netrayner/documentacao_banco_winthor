# 📊 Tabela: PCITEMROLO

### Estrutura de Colunas e Restrições

    Tabela    Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMROLO CODFILIAL  VARCHAR2(2)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMROLO   NUMROLO VARCHAR2(10)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMROLO   CODPROD  NUMBER(6,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMROLO        QT NUMBER(16,3)                                  NaN            OPERACIONAL                        NaN
PCITEMROLO   NUMORCA NUMBER(10,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMROLO    NUMPED NUMBER(10,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMROLO    NUMSEQ NUMBER(20,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMROLO   NUMLOTE VARCHAR2(15)             Indica o número do lote.            OPERACIONAL                        NaN
PCITEMROLO    DTVENC         DATE Indica a data de vencimento do lote.            OPERACIONAL                        NaN
PCITEMROLO    CODCOR NUMBER(10,0)                        Código da Cor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*