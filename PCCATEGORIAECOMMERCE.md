# 📊 Tabela: PCCATEGORIAECOMMERCE

### Estrutura de Colunas e Restrições

              Tabela                Coluna   Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCATEGORIAECOMMERCE                    ID   NUMBER(10,0)                          Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCCATEGORIAECOMMERCE                  NOME  VARCHAR2(225)                     Nome da categoria no ecommerce            OPERACIONAL                        NaN
PCCATEGORIAECOMMERCE             DESCRICAO VARCHAR2(4000)              Descrição da categoria no ecommerce            OPERACIONAL                        NaN
PCCATEGORIAECOMMERCE                   URL  VARCHAR2(300)                      URL da categoria no ecommerce            OPERACIONAL                        NaN
PCCATEGORIAECOMMERCE                 ORDEM    NUMBER(3,0)      Ordem de exibição da catetoria no ecommerce            OPERACIONAL                        NaN
PCCATEGORIAECOMMERCE               VISIVEL    NUMBER(1,0) Indica se a categoria estará visivil no ecommerce            OPERACIONAL                        NaN
PCCATEGORIAECOMMERCE           CATEGORIAID   NUMBER(10,0)             Identificador da categoiria no winthor CHAVE ESTRANGEIRA (FK)       PCCATEGORIAECOMMERCE
PCCATEGORIAECOMMERCE DATAULTIMAATUALIZACAO           DATE                      Data da última atualização            OPERACIONAL                        NaN
PCCATEGORIAECOMMERCE                 ATIVO    NUMBER(1,0)     Indica se a categoria está ativa no ecommerce            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*