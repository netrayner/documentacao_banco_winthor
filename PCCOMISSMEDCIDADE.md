# 📊 Tabela: PCCOMISSMEDCIDADE

### Estrutura de Colunas e Restrições

           Tabela          Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSMEDCIDADE       CODFILIAL  VARCHAR2(2)                                  Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDCIDADE         TIPOCAD  VARCHAR2(1) Tipo de Cadastro da Cidade [I-Inclusão;E-Exceção]    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDCIDADE       CODCIDADE  NUMBER(6,0)                          Código da Cidade no IBGE    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSMEDCIDADE         CODUSUR  NUMBER(6,0)                                 Código do Usuário            OPERACIONAL                        NaN
PCCOMISSMEDCIDADE CODFUNCCADASTRO  NUMBER(8,0)                              Funcionário cadastro            OPERACIONAL                        NaN
PCCOMISSMEDCIDADE      DTCADASTRO         DATE                                     Data Cadastro            OPERACIONAL                        NaN
PCCOMISSMEDCIDADE   CODFUNCULTALT  NUMBER(8,0)                      Funcionário última alteração            OPERACIONAL                        NaN
PCCOMISSMEDCIDADE        DTULTALT         DATE                               Data últ. Alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*