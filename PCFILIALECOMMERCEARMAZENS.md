# 📊 Tabela: PCFILIALECOMMERCEARMAZENS

### Estrutura de Colunas e Restrições

                   Tabela              Coluna Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILIALECOMMERCEARMAZENS                  ID NUMBER(22,0)   identificador incremental    CHAVE PRIMÁRIA (PK)                        NaN
PCFILIALECOMMERCEARMAZENS          ID_ARMAZEM NUMBER(22,0)               id do armazem CHAVE ESTRANGEIRA (FK)         PCARMAZEMECOMMERCE
PCFILIALECOMMERCEARMAZENS ID_FILIAL_ECOMMERCE NUMBER(10,0)    id da fililal e-commerce CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE
PCFILIALECOMMERCEARMAZENS               ATIVO  NUMBER(1,0) indica se esta ativo ou nao            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*