# 📊 Tabela: PCLAYOUTBOLETO

### Estrutura de Colunas e Restrições

        Tabela                 Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTBOLETO                 CODIGO NUMBER(10,0)                   Código identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTBOLETO                   NOME VARCHAR2(50)                         Nome do layout            OPERACIONAL                        NaN
PCLAYOUTBOLETO                TAMANHO  NUMBER(4,0)                      Tamanho do Layout            OPERACIONAL                        NaN
PCLAYOUTBOLETO    BANCOCORRESPONDENTE NUMBER(10,0)       Variavel de banco correspondente            OPERACIONAL                        NaN
PCLAYOUTBOLETO VARIAVELLINHADIGITAVEL NUMBER(10,0)            Variavel de linha digitável            OPERACIONAL                        NaN
PCLAYOUTBOLETO                 STATUS VARCHAR2(15) Status da variável, Invalido ou válido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*