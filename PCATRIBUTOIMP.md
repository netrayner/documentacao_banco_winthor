# 📊 Tabela: PCATRIBUTOIMP

### Estrutura de Colunas e Restrições

       Tabela      Coluna  Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCATRIBUTOIMP CODATRIBUTO  VARCHAR2(20)         Código do Atributo    CHAVE PRIMÁRIA (PK)                        NaN
PCATRIBUTOIMP   DESCRICAO VARCHAR2(100)      Descrição do Atributo            OPERACIONAL                        NaN
PCATRIBUTOIMP      CODNVE  VARCHAR2(20)    Código da especificação    CHAVE PRIMÁRIA (PK)            PCNVEIMPORTACAO
PCATRIBUTOIMP  DTCADASTRO          DATE            Data do Vinculo            OPERACIONAL                        NaN
PCATRIBUTOIMP  CODUSUARIO   NUMBER(8,0) Código do usuário Cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*