# 📊 Tabela: PCPRODFORNREPOSICAO

### Estrutura de Colunas e Restrições

             Tabela               Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODFORNREPOSICAO            CODFILIAL  VARCHAR2(2)                 Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODFORNREPOSICAO              CODPROD  NUMBER(6,0)                Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODFORNREPOSICAO            CODFORNEC  NUMBER(6,0)             Código do Fornecedor    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODFORNREPOSICAO           PRIORIDADE  NUMBER(3,0)          Prioridade de Reposição            OPERACIONAL                        NaN
PCPRODFORNREPOSICAO          INTEGRADORA  NUMBER(6,0)            Código da Integradora            OPERACIONAL                        NaN
PCPRODFORNREPOSICAO INTEGRADORAESPELHONF  NUMBER(6,0) Cód. Integradora para Espelho NF            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*