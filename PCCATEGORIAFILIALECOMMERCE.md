# 📊 Tabela: PCCATEGORIAFILIALECOMMERCE

### Estrutura de Colunas e Restrições

                    Tabela                Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCATEGORIAFILIALECOMMERCE                    ID NUMBER(10,0)  Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCCATEGORIAFILIALECOMMERCE       CODIGOECOMMERCE NUMBER(10,0)           Código ecommerce            OPERACIONAL                        NaN
PCCATEGORIAFILIALECOMMERCE             CODFILIAL  VARCHAR2(2)    Código da filial withor CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCCATEGORIAFILIALECOMMERCE           CATEGORIAID NUMBER(10,0) Identificador da categoria            OPERACIONAL                        NaN
PCCATEGORIAFILIALECOMMERCE DATAULTIMAATUALIZACAO         DATE  Data a última atualização            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*