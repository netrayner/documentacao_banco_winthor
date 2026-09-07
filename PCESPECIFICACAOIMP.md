# 📊 Tabela: PCESPECIFICACAOIMP

### Estrutura de Colunas e Restrições

            Tabela           Coluna  Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESPECIFICACAOIMP CODESPECIFICACAO  VARCHAR2(20)         Código do Atributo    CHAVE PRIMÁRIA (PK)                        NaN
PCESPECIFICACAOIMP        DESCRICAO VARCHAR2(100)      Descrição do Atributo            OPERACIONAL                        NaN
PCESPECIFICACAOIMP      CODATRIBUTO  VARCHAR2(20)    Código da especificação    CHAVE PRIMÁRIA (PK)                        NaN
PCESPECIFICACAOIMP       DTCADASTRO          DATE            Data do Vinculo            OPERACIONAL                        NaN
PCESPECIFICACAOIMP       CODUSUARIO   NUMBER(8,0) Código do usuário Cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*