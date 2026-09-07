# 📊 Tabela: PCGMREALIZADOHISTORICO

### Estrutura de Colunas e Restrições

                Tabela        Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMREALIZADOHISTORICO CODCOMBINACAO NUMBER(10,0) Código da combinacao da parametrização atual    CHAVE PRIMÁRIA (PK)             PCGMCOMBINACAO
PCGMREALIZADOHISTORICO  CODPARAMMETA NUMBER(10,0)               Código da parametrização atual            OPERACIONAL                        NaN
PCGMREALIZADOHISTORICO   CODTIPOMETA NUMBER(10,0)                       Código do tipo de meta            OPERACIONAL                        NaN
PCGMREALIZADOHISTORICO  CODINDICADOR NUMBER(10,0)                          Código do indicador            OPERACIONAL                        NaN
PCGMREALIZADOHISTORICO          ITEM VARCHAR2(50)                       Código do item da meta            OPERACIONAL                        NaN
PCGMREALIZADOHISTORICO          DATA         DATE                       Data da meta histórica    CHAVE PRIMÁRIA (PK)                        NaN
PCGMREALIZADOHISTORICO       CODMETA NUMBER(10,0)                         Código da meta atual    CHAVE PRIMÁRIA (PK)                   PCGMMETA
PCGMREALIZADOHISTORICO     REALIZADO NUMBER(15,2)            Valor realizado da meta histórica            OPERACIONAL                        NaN
PCGMREALIZADOHISTORICO        FILTRO  VARCHAR2(7)                       Filtro do tipo de meta            OPERACIONAL                        NaN
PCGMREALIZADOHISTORICO    VLPROJECAO NUMBER(15,2)       Valor projetado para o mês de dezembro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*