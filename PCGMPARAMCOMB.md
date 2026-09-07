# 📊 Tabela: PCGMPARAMCOMB

### Estrutura de Colunas e Restrições

       Tabela       Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMPARAMCOMB       CODIGO NUMBER(10,0)             Código da combinação    CHAVE PRIMÁRIA (PK)                        NaN
PCGMPARAMCOMB CODPARAMMETA NUMBER(10,0) Código da parametrização da meta CHAVE ESTRANGEIRA (FK)              PCGMPARAMMETA
PCGMPARAMCOMB CODINDICADOR NUMBER(10,0)              Código do indicador CHAVE ESTRANGEIRA (FK)              PCGMINDICADOR
PCGMPARAMCOMB  CODTIPOMETA NUMBER(10,0)           Código do tipo de meta CHAVE ESTRANGEIRA (FK)               PCGMTIPOMETA

---
*Documentação gerada automaticamente.*