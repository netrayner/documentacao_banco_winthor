# 📊 Tabela: PCPRODUTOECOMMERCE

### Estrutura de Colunas e Restrições

            Tabela                Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTOECOMMERCE                    ID  NUMBER(10,0)        Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOECOMMERCE               CODPROD  NUMBER(10,0)       Código do produto winthor CHAVE ESTRANGEIRA (FK)                   PCPRODUT
PCPRODUTOECOMMERCE                  NOME VARCHAR2(255)                  Nome do produto            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE        DESCRICAOCURTA VARCHAR2(255)           Descrição do produto            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE                 ORDEM   NUMBER(3,0)                            Ordem            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE           POSSUIGRADE   NUMBER(1,0)                     Possui grade            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE          DEFINICAO1ID  NUMBER(10,0)                    Definição 1            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE          DEFINICAO2ID  NUMBER(10,0)                    Definição 2            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE           CATEGORIAID  NUMBER(10,0)       Identificador da categoria            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE                 ATIVO   NUMBER(1,0)                    Ativo(1 ou 0)            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE                 BONUS  NUMBER(10,0)                           Bônus            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE DATAULTIMAATUALIZACAO          DATE    Data da última atualização            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE                   URL VARCHAR2(255)                   Url do produto            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE     PERCENTUALESTOQUE   NUMBER(6,2)            Percentual do estoque            OPERACIONAL                        NaN
PCPRODUTOECOMMERCE    PERCACRESCIMOPRECO  NUMBER(18,6) Percentual de acrescimo no preço            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*