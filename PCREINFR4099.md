# 📊 Tabela: PCREINFR4099

### Estrutura de Colunas e Restrições

      Tabela            Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR4099                ID   NUMBER(8,0)                           Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR4099           GRUPOID   NUMBER(8,0)               Código do grupo de empresas            OPERACIONAL                        NaN
PCREINFR4099               MES   NUMBER(8,0)             Mês do período de competência            OPERACIONAL                        NaN
PCREINFR4099               ANO   NUMBER(8,0)             Ano do período de competência            OPERACIONAL                        NaN
PCREINFR4099 MARCO_COMPETENCIA  VARCHAR2(10)          Marco do período de competência.            OPERACIONAL                        NaN
PCREINFR4099            STATUS VARCHAR2(100) Status do processo de fechamento/abertura            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*