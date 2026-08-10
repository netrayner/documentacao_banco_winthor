# 📊 Tabela: PCALIENAFORNEC

### Estrutura de Colunas e Restrições

        Tabela     Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCALIENAFORNEC  CATEGORIA  NUMBER(6,0) Código da categoria: ramo atividade, praça, produto, etc.    CHAVE PRIMÁRIA (PK)                        NaN
PCALIENAFORNEC  CODFORNEC  NUMBER(6,0)                                     Código do fornecedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCALIENAFORNEC REFWINTHOR VARCHAR2(40)   Código do Whinthor: ramo atividade, praça, produto,etc.    CHAVE PRIMÁRIA (PK)                        NaN
PCALIENAFORNEC  ALIENACAO VARCHAR2(40)                     Código de alienação com o fornecedor.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*