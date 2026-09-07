# 📊 Tabela: PCVARIAVEL

### Estrutura de Colunas e Restrições

    Tabela         Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVARIAVEL         TABELA VARCHAR2(30)                        Tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCVARIAVEL          CAMPO VARCHAR2(30)                        Coluna    CHAVE PRIMÁRIA (PK)                        NaN
PCVARIAVEL   VALORDEFAULT VARCHAR2(50)                 Valor default            OPERACIONAL                        NaN
PCVARIAVEL CODTIPOFORMULA  NUMBER(8,0)     Código do tipo da fórmula    CHAVE PRIMÁRIA (PK)              PCFORMULATIPO
PCVARIAVEL     DTCADASTRO         DATE              Data de cadastro            OPERACIONAL                        NaN
PCVARIAVEL  CODUSUARIOINC  NUMBER(8,0) Código do usuário de inclusão            OPERACIONAL                        NaN
PCVARIAVEL    DTALTERACAO         DATE             Data de alteração            OPERACIONAL                        NaN
PCVARIAVEL  CODUSUARIOALT  NUMBER(8,0) Código do usuario que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*