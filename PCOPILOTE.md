# 📊 Tabela: PCOPILOTE

### Estrutura de Colunas e Restrições

   Tabela        Coluna Tipo/Tamanho                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOPILOTE       CODPROD  NUMBER(6,0)                                                                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCOPILOTE       NUMLOTE VARCHAR2(15)                                                                                                       NaN            OPERACIONAL                        NaN
PCOPILOTE            QT NUMBER(20,8)                                                                                                       NaN            OPERACIONAL                        NaN
PCOPILOTE         NUMOP  NUMBER(8,0)                                                                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCOPILOTE QTREQUISITADO NUMBER(20,8) Campo que armazena o valor consumido de cada lote de cada produto caso o produto seja controlado por lote            OPERACIONAL                        NaN
PCOPILOTE       DTBAIXA         DATE                                                                                                       NaN            OPERACIONAL                        NaN
PCOPILOTE   FRACAOUMIDA  VARCHAR2(5)                                                                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCOPILOTE        NUMSEQ  NUMBER(4,0)                                                                               Indica sequencial das MPS.     CHAVE PRIMÁRIA (PK)                        NaN
PCOPILOTE    NUMLOTEORI VARCHAR2(15)                                                                                 Indica o lote de origem.             OPERACIONAL                        NaN
PCOPILOTE       QTPERDA NUMBER(20,8)                                                                                                       NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*