# 📊 Tabela: PCARMAZEMECOMMERCE

### Estrutura de Colunas e Restrições

            Tabela               Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCARMAZEMECOMMERCE                   ID NUMBER(22,0)               idenficador incremental    CHAVE PRIMÁRIA (PK)                        NaN
PCARMAZEMECOMMERCE           COD_FILIAL  VARCHAR2(2)           codigo da filial no WinThor CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCARMAZEMECOMMERCE ID_ARMAZEM_ECOMMERCE  NUMBER(4,0)            id do armazém no ecommerce            OPERACIONAL                        NaN
PCARMAZEMECOMMERCE  ID_BRANCH_ECOMMERCE  NUMBER(4,0)  id da filial do armazém no ecommerce            OPERACIONAL                        NaN
PCARMAZEMECOMMERCE                 NOME VARCHAR2(64)                       nome do armazém            OPERACIONAL                        NaN
PCARMAZEMECOMMERCE             ENDERECO VARCHAR2(64)                   endereço do armazém            OPERACIONAL                        NaN
PCARMAZEMECOMMERCE               NUMERO  VARCHAR2(5)                     número do armazém            OPERACIONAL                        NaN
PCARMAZEMECOMMERCE          COMPLEMENTO VARCHAR2(64)                complemento do armazém            OPERACIONAL                        NaN
PCARMAZEMECOMMERCE               CIDADE VARCHAR2(32)                     cidade do armazem            OPERACIONAL                        NaN
PCARMAZEMECOMMERCE                   UF  VARCHAR2(2)                         uf do armazem            OPERACIONAL                        NaN
PCARMAZEMECOMMERCE                  CEP  VARCHAR2(8)                        cep do armazem            OPERACIONAL                        NaN
PCARMAZEMECOMMERCE  INTEGRADO_ECOMMERCE  NUMBER(1,0) Indica se esta integrado no ecommerce            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*