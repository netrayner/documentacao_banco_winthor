# 📊 Tabela: PCLOGFORMULA

### Estrutura de Colunas e Restrições

      Tabela         Coluna  Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGFORMULA          DTLOG          DATE               Data de geração do log            OPERACIONAL                        NaN
PCLOGFORMULA  CODUSUARIOLOG   NUMBER(8,0) Códigod o usuário alterou a registro            OPERACIONAL                        NaN
PCLOGFORMULA     CODFORMULA VARCHAR2(200)                    Código da formula            OPERACIONAL                        NaN
PCLOGFORMULA      DESCRICAO VARCHAR2(300)                 Descrição da formula            OPERACIONAL                        NaN
PCLOGFORMULA        FORMULA          CLOB                              Fórmula            OPERACIONAL                        NaN
PCLOGFORMULA CODTIPOFORMULA   NUMBER(8,0)               Código tipo da fórmula            OPERACIONAL                        NaN
PCLOGFORMULA     DTCADASTRO          DATE                     Data de cadastro            OPERACIONAL                        NaN
PCLOGFORMULA  CODUSUARIOINC   NUMBER(8,0)              Código usuario inclusão            OPERACIONAL                        NaN
PCLOGFORMULA    DTALTERACAO          DATE                    Data de alteração            OPERACIONAL                        NaN
PCLOGFORMULA  CODUSUARIOALT   NUMBER(8,0)             Código usuario alteração            OPERACIONAL                        NaN
PCLOGFORMULA         CODIGO   NUMBER(4,0)                   Índice de pesquisa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*