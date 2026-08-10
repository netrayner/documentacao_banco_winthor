# 📊 Tabela: PCFLUPESQRAPIDACOL

### Estrutura de Colunas e Restrições

            Tabela              Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFLUPESQRAPIDACOL       CODPESQRAPIDA  VARCHAR2(25)                              Código da pesquisa    CHAVE PRIMÁRIA (PK)            PCFLUPESQRAPIDA
PCFLUPESQRAPIDACOL                NOME VARCHAR2(130)                                  Nome da coluna    CHAVE PRIMÁRIA (PK)                        NaN
PCFLUPESQRAPIDACOL               LABEL VARCHAR2(130)                 Tag/classificador para a coluna            OPERACIONAL                        NaN
PCFLUPESQRAPIDACOL         ALINHAMENTO   VARCHAR2(7)                     Tipo de alinhamento na tela            OPERACIONAL                        NaN
PCFLUPESQRAPIDACOL           ORDENAVEL   VARCHAR2(5) Indica se o campo pode ser usado para ordenação            OPERACIONAL                        NaN
PCFLUPESQRAPIDACOL           ESCONDIDO   VARCHAR2(5)                   Indica se o campo é invisível            OPERACIONAL                        NaN
PCFLUPESQRAPIDACOL   COMPRIMENTO_MEDIO   NUMBER(5,0)         Comprimento para slots de tamanho médio            OPERACIONAL                        NaN
PCFLUPESQRAPIDACOL COMPRIMENTO_PEQUENO   NUMBER(5,0)       Comprimento para slots de tamanho pequeno            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*