# 📊 Tabela: PCCOMISSMEDREDUCAO

### Estrutura de Colunas e Restrições

            Tabela          Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSMEDREDUCAO       CODFILIAL  VARCHAR2(2)                  Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDREDUCAO       NUMREGIAO  NUMBER(4,0)                  Código da Região    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDREDUCAO    PERREDCOMISS  NUMBER(8,4) Percentual de Redução da Comissão            OPERACIONAL                        NaN
PCCOMISSMEDREDUCAO CODFUNCCADASTRO  NUMBER(8,0)              Funcionário cadastro            OPERACIONAL                        NaN
PCCOMISSMEDREDUCAO      DTCADASTRO         DATE                     Data Cadastro            OPERACIONAL                        NaN
PCCOMISSMEDREDUCAO   CODFUNCULTALT  NUMBER(8,0)      Funcionário última alteração            OPERACIONAL                        NaN
PCCOMISSMEDREDUCAO        DTULTALT         DATE               Data últ. Alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*