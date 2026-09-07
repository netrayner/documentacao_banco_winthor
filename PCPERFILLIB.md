# 📊 Tabela: PCPERFILLIB

### Estrutura de Colunas e Restrições

     Tabela      Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPERFILLIB    PERFILID NUMBER(10,0)                                 ID do Perfil    CHAVE PRIMÁRIA (PK)                   PCPERFIL
PCPERFILLIB   CODTABELA NUMBER(22,0)                             Código da Tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCPERFILLIB     CODIGON NUMBER(22,0)                              Código Numérico    CHAVE PRIMÁRIA (PK)                        NaN
PCPERFILLIB     CODIGOA VARCHAR2(40)                           Código do Cadastro    CHAVE PRIMÁRIA (PK)                        NaN
PCPERFILLIB CODFUNC_LIB NUMBER(22,0) Matrícula do Usuário que efetuou a liberação            OPERACIONAL                        NaN
PCPERFILLIB     DATALIB TIMESTAMP(6)                            Data da Liberação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*