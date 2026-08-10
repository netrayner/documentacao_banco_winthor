# 📊 Tabela: PCBANCOFILIAIS

### Estrutura de Colunas e Restrições

        Tabela    Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBANCOFILIAIS  CODBANCO  NUMBER(4,0)     Código do banco    CHAVE PRIMÁRIA (PK)                    PCBANCO
PCBANCOFILIAIS CODFILIAL  VARCHAR2(2)    Código da filial    CHAVE PRIMÁRIA (PK)                   PCFILIAL

---
*Documentação gerada automaticamente.*