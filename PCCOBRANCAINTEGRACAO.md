# 📊 Tabela: PCCOBRANCAINTEGRACAO

### Estrutura de Colunas e Restrições

              Tabela           Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOBRANCAINTEGRACAO               ID NUMBER(10,0)       Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCCOBRANCAINTEGRACAO CODIGOCOBWINTHOR VARCHAR2(45) CÃ³digo de cobranÃ§a do winthor CHAVE ESTRANGEIRA (FK)                      PCCOB
PCCOBRANCAINTEGRACAO  CODIGOECOMMERCE NUMBER(10,0)            CÃ³digo do ecommerce CHAVE ESTRANGEIRA (FK)        PCCOBRANCAECOMMERCE
PCCOBRANCAINTEGRACAO         FILIALID NUMBER(10,0)  CÃ³digo da filial no ecommerce CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE

---
*Documentação gerada automaticamente.*