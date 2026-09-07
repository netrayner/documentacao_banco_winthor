# 📊 Tabela: PCDOCC

### Estrutura de Colunas e Restrições

Tabela      Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCC   CODFISCAL  VARCHAR2(6)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCC    OPERACAO VARCHAR2(40)                 NaN            OPERACIONAL                        NaN
PCDOCC   NUMLINHAS  NUMBER(4,0)                 NaN            OPERACIONAL                        NaN
PCDOCC       LETRA  VARCHAR2(1)                 NaN            OPERACIONAL                        NaN
PCDOCC ESPACAMENTO  VARCHAR2(1)                 NaN            OPERACIONAL                        NaN
PCDOCC       SERIE  VARCHAR2(3)                 NaN            OPERACIONAL                        NaN
PCDOCC  QTMAXITENS  NUMBER(2,0)                 NaN            OPERACIONAL                        NaN
PCDOCC   TIPOPRECO  VARCHAR2(1)                 NaN            OPERACIONAL                        NaN
PCDOCC  IMPRESSORA VARCHAR2(15)                 NaN            OPERACIONAL                        NaN
PCDOCC     TIPODOC  VARCHAR2(3)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCC      CODDOC  NUMBER(8,0)                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*