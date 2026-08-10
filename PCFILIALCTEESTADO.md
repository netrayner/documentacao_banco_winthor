# 📊 Tabela: PCFILIALCTEESTADO

### Estrutura de Colunas e Restrições

           Tabela    Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILIALCTEESTADO    CODCTE NUMBER(10,0)       Código do CTE    CHAVE PRIMÁRIA (PK)                        NaN
PCFILIALCTEESTADO    NUMCTE NUMBER(10,0)  Próximo número CTE            OPERACIONAL                        NaN
PCFILIALCTEESTADO  SERIECTE  VARCHAR2(3)           Série CTE            OPERACIONAL                        NaN
PCFILIALCTEESTADO CODFILIAL  VARCHAR2(2)    Código da filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCFILIALCTEESTADO        UF  VARCHAR2(2)       Estado da CTE CHAVE ESTRANGEIRA (FK)                   PCESTADO

---
*Documentação gerada automaticamente.*