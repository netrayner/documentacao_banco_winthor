# 📊 Tabela: PCFILIALATOCONCESSORIO

### Estrutura de Colunas e Restrições

                Tabela            Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILIALATOCONCESSORIO         CODFILIAL  VARCHAR2(2) Código da filial do ato acessorio            OPERACIONAL                        NaN
PCFILIALATOCONCESSORIO             NPROC VARCHAR2(60)        Descricao do ato acessorio            OPERACIONAL                        NaN
PCFILIALATOCONCESSORIO           INDPROC  NUMBER(1,0) Indica o processo a ser realizado            OPERACIONAL                        NaN
PCFILIALATOCONCESSORIO             TPATO  NUMBER(2,0)           Tipo de ato Concessório            OPERACIONAL                        NaN
PCFILIALATOCONCESSORIO CODATOCONCESSORIO  NUMBER(8,0)           Código do ato acessorio    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*