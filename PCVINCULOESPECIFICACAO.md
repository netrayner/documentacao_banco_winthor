# 📊 Tabela: PCVINCULOESPECIFICACAO

### Estrutura de Colunas e Restrições

                Tabela           Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVINCULOESPECIFICACAO          CODPROD  NUMBER(6,0)          Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCVINCULOESPECIFICACAO           CODNVE VARCHAR2(20)                 Código NVE    CHAVE PRIMÁRIA (PK)            PCNVEIMPORTACAO
PCVINCULOESPECIFICACAO      CODATRIBUTO VARCHAR2(20)         Código do Atributo    CHAVE PRIMÁRIA (PK)         PCESPECIFICACAOIMP
PCVINCULOESPECIFICACAO CODESPECIFICACAO VARCHAR2(20)    Código da Especificação CHAVE ESTRANGEIRA (FK)         PCESPECIFICACAOIMP
PCVINCULOESPECIFICACAO       DTCADASTRO         DATE            Data do Vinculo            OPERACIONAL                        NaN
PCVINCULOESPECIFICACAO       CODUSUARIO  NUMBER(8,0) Código do usuário Cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*