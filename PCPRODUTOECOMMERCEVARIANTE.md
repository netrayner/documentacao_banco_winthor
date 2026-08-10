# 📊 Tabela: PCPRODUTOECOMMERCEVARIANTE

### Estrutura de Colunas e Restrições

                    Tabela                   Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTOECOMMERCEVARIANTE                       ID NUMBER(10,0)           Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOECOMMERCEVARIANTE                  CODPROD NUMBER(10,0)                   Código do produto CHAVE ESTRANGEIRA (FK)                   PCPRODUT
PCPRODUTOECOMMERCEVARIANTE                PRODUTOID NUMBER(10,0)            Identificador do produto CHAVE ESTRANGEIRA (FK)         PCPRODUTOECOMMERCE
PCPRODUTOECOMMERCEVARIANTE DEFINICAOVALORECOMMERCE1 NUMBER(10,0) Identificador do valor de definição            OPERACIONAL                        NaN
PCPRODUTOECOMMERCEVARIANTE DEFINICAOVALORECOMMERCE2 NUMBER(10,0) Identificador do valor de definição            OPERACIONAL                        NaN
PCPRODUTOECOMMERCEVARIANTE                  VISIVEL  NUMBER(1,0)                     Vísível(1 ou 0)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*