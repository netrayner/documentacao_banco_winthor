# 📊 Tabela: PCEMBALAGEMECOMMERCEVARIANTE

### Estrutura de Colunas e Restrições

                      Tabela                   Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMBALAGEMECOMMERCEVARIANTE                       ID NUMBER(10,0)           Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBALAGEMECOMMERCEVARIANTE              CODAUXILIAR NUMBER(20,0)                    Codigo de barras            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCEVARIANTE              EMBALAGEMID NUMBER(10,0)          Identificador da embalagem CHAVE ESTRANGEIRA (FK)       PCEMBALAGEMECOMMERCE
PCEMBALAGEMECOMMERCEVARIANTE DEFINICAOVALORECOMMERCE1 NUMBER(10,0)  Identifcador do valor da definição            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCEVARIANTE DEFINICAOVALORECOMMERCE2 NUMBER(10,0) Identificador do valor da definição            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCEVARIANTE        PERCENTUALESTOQUE  NUMBER(5,2)               Percentual do estoque            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCEVARIANTE                  VISIVEL  NUMBER(1,0)                     Visivel(1 ou 0)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*