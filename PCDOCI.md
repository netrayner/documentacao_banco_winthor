# 📊 Tabela: PCDOCI

### Estrutura de Colunas e Restrições

Tabela    Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCI CODFISCAL  VARCHAR2(6)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCI     SECAO  VARCHAR2(1)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCI     LINHA  NUMBER(4,0)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCI    COLUNA  NUMBER(4,0)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCI TIPOCAMPO  VARCHAR2(1)                 NaN            OPERACIONAL                        NaN
PCDOCI   TAMANHO  NUMBER(4,0)                 NaN            OPERACIONAL                        NaN
PCDOCI  DECIMAIS  NUMBER(2,0)                 NaN            OPERACIONAL                        NaN
PCDOCI     TEXTO VARCHAR2(75)                 NaN            OPERACIONAL                        NaN
PCDOCI   TIPODOC  VARCHAR2(3)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCI    CODDOC  NUMBER(8,0)                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*