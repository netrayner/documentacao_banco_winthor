# 📊 Tabela: PCCOBRANCAMARKETPLACE

### Estrutura de Colunas e Restrições

               Tabela               Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOBRANCAMARKETPLACE                   ID NUMBER(22,0)               Identificador gerado automaticamente    CHAVE PRIMÁRIA (PK)                        NaN
PCCOBRANCAMARKETPLACE    IDFILIALECOMMERCE NUMBER(22,0) Id da filial e-commerce (tabela pcfilialecommerce) CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE
PCCOBRANCAMARKETPLACE IDCIASHOPMARKETPLACE NUMBER(22,0)     ID do marketplace(tabela PCCIASHOPMARKETPLACE) CHAVE ESTRANGEIRA (FK)       PCCIASHOPMARKETPLACE
PCCOBRANCAMARKETPLACE        CODCOBWINTHOR  VARCHAR2(4)          Código da cobrança winthor (tabela PCCOB) CHAVE ESTRANGEIRA (FK)                      PCCOB

---
*Documentação gerada automaticamente.*