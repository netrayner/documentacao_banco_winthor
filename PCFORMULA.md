# 📊 Tabela: PCFORMULA

### Estrutura de Colunas e Restrições

   Tabela         Coluna  Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMULA     CODFORMULA VARCHAR2(200)             Código da formula    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULA      DESCRICAO VARCHAR2(300)          Descrição da formula            OPERACIONAL                        NaN
PCFORMULA        FORMULA          CLOB                       Formula            OPERACIONAL                        NaN
PCFORMULA CODTIPOFORMULA   NUMBER(8,0)     Código do tipo da fórmula CHAVE ESTRANGEIRA (FK)              PCFORMULATIPO
PCFORMULA     DTCADASTRO          DATE              Data de cadastro            OPERACIONAL                        NaN
PCFORMULA  CODUSUARIOINC   NUMBER(8,0) Código do usuário de inclusão            OPERACIONAL                        NaN
PCFORMULA    DTALTERACAO          DATE             Data de alteração            OPERACIONAL                        NaN
PCFORMULA  CODUSUARIOALT   NUMBER(8,0) Código do usuario que alterou            OPERACIONAL                        NaN
PCFORMULA         CODIGO   NUMBER(4,0)          Indice para pesquisa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*