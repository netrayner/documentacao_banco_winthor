# 📊 Tabela: PCCOMISSMEDREDE

### Estrutura de Colunas e Restrições

         Tabela          Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSMEDREDE       CODFILIAL  VARCHAR2(2)                     Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDREDE         CODREDE  NUMBER(4,0)           Código da Rede de Clientes    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDREDE    PERCINCIDPMC  NUMBER(8,4) Percentual de Incidência sobre o PMC            OPERACIONAL                        NaN
PCCOMISSMEDREDE CODFUNCCADASTRO  NUMBER(8,0)                 Funcionário cadastro            OPERACIONAL                        NaN
PCCOMISSMEDREDE      DTCADASTRO         DATE                        Data Cadastro            OPERACIONAL                        NaN
PCCOMISSMEDREDE   CODFUNCULTALT  NUMBER(8,0)         Funcionário última alteração            OPERACIONAL                        NaN
PCCOMISSMEDREDE        DTULTALT         DATE                  Data últ. Alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*