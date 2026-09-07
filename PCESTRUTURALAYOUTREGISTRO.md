# 📊 Tabela: PCESTRUTURALAYOUTREGISTRO

### Estrutura de Colunas e Restrições

                   Tabela           Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTRUTURALAYOUTREGISTRO           CODIGO NUMBER(10,0)    Código do layout    CHAVE PRIMÁRIA (PK)                        NaN
PCESTRUTURALAYOUTREGISTRO CODIGO_ESTRUTURA NUMBER(10,0) Código da estrutura CHAVE ESTRANGEIRA (FK)          PCESTRUTURALAYOUT
PCESTRUTURALAYOUTREGISTRO             NOME VARCHAR2(32)   Nome da estrutura            OPERACIONAL                        NaN
PCESTRUTURALAYOUTREGISTRO            ORDEM  NUMBER(3,0)  Ordem da estrutura            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*