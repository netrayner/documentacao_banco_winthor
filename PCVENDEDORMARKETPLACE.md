# 📊 Tabela: PCVENDEDORMARKETPLACE

### Estrutura de Colunas e Restrições

               Tabela               Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVENDEDORMARKETPLACE                   ID NUMBER(22,0)               Identificador gerado automaticamente    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDEDORMARKETPLACE    IDFILIALECOMMERCE NUMBER(22,0) Id da filial e-commerce (tabela pcfilialecommerce) CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE
PCVENDEDORMARKETPLACE IDCIASHOPMARKETPLACE NUMBER(22,0)     ID do marketplace(tabela PCCIASHOPMARKETPLACE) CHAVE ESTRANGEIRA (FK)       PCCIASHOPMARKETPLACE
PCVENDEDORMARKETPLACE              CODUSUR  NUMBER(5,0)      Código do vendedor  Winthor (tabela PCUSUARI) CHAVE ESTRANGEIRA (FK)                   PCUSUARI

---
*Documentação gerada automaticamente.*