# 📊 Tabela: PCDEFINICAOVALORECOMMERCE

### Estrutura de Colunas e Restrições

                   Tabela      Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEFINICAOVALORECOMMERCE          ID  NUMBER(10,0)              Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCDEFINICAOVALORECOMMERCE   DESCRICAO VARCHAR2(225)    Descrição do valor da definição            OPERACIONAL                        NaN
PCDEFINICAOVALORECOMMERCE DEFINICAOID  NUMBER(10,0) Identificador da definição ecommerce CHAVE ESTRANGEIRA (FK)       PCDEFINICAOECOMMERCE

---
*Documentação gerada automaticamente.*