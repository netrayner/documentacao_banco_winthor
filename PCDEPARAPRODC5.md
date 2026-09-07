# 📊 Tabela: PCDEPARAPRODC5

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEPARAPRODC5  SEQFAMILIA NUMBER(11,0)                     Sequencial familia            OPERACIONAL                        NaN
PCDEPARAPRODC5  SEQPRODUTO NUMBER(11,0)                     Sequencial produto            OPERACIONAL                        NaN
PCDEPARAPRODC5     CODPROD  NUMBER(6,0)           Código do produto no Winthor    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPARAPRODC5 CODAUXILIAR NUMBER(20,0) Codigo de barras do produto no Winthor    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPARAPRODC5       ATIVO  VARCHAR2(1)    Indica se a linha esta ativa ou não            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*