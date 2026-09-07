# 📊 Tabela: PCTRIBUTACAOCIASHOP

### Estrutura de Colunas e Restrições

             Tabela    Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBUTACAOCIASHOP        ID NUMBER(22,0)      ID da registro    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTACAOCIASHOP CODFILIAL  VARCHAR2(2)    Código da filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCTRIBUTACAOCIASHOP  CODPRACA NUMBER(22,0)     Código da praça CHAVE ESTRANGEIRA (FK)                    PCPRACA
PCTRIBUTACAOCIASHOP        UF  VARCHAR2(2)                  UF            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*