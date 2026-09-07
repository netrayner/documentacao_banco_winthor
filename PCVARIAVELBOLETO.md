# 📊 Tabela: PCVARIAVELBOLETO

### Estrutura de Colunas e Restrições

          Tabela              Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVARIAVELBOLETO              CODIGO  NUMBER(10,0)             Código identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCVARIAVELBOLETO                NOME  VARCHAR2(50)                 Nome da variável            OPERACIONAL                        NaN
PCVARIAVELBOLETO           DESCRICAO VARCHAR2(255)            Descrição da variável            OPERACIONAL                        NaN
PCVARIAVELBOLETO        TIPOVARIAVEL  VARCHAR2(15)                 Tipo de variável            OPERACIONAL                        NaN
PCVARIAVELBOLETO           TIPODADOS  VARCHAR2(15)      Tipo do retorno da variável            OPERACIONAL                        NaN
PCVARIAVELBOLETO        TIPOCONTEUDO  VARCHAR2(15)     Tipo de conteúdo da variável            OPERACIONAL                        NaN
PCVARIAVELBOLETO VARIAVELNOSSONUMERO  VARCHAR2(15) Tipo da variavel de nosso número            OPERACIONAL                        NaN
PCVARIAVELBOLETO            CONTEUDO          CLOB                         Conteúdo            OPERACIONAL                        NaN
PCVARIAVELBOLETO              STATUS  VARCHAR2(15)        Status invalido ou válido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*