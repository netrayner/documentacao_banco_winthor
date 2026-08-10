# 📊 Tabela: PCPLANPAGAMENTOMARKETPLACE

### Estrutura de Colunas e Restrições

                    Tabela               Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPLANPAGAMENTOMARKETPLACE                   ID NUMBER(22,0)               Identificador gerado automaticamente    CHAVE PRIMÁRIA (PK)                        NaN
PCPLANPAGAMENTOMARKETPLACE    IDFILIALECOMMERCE NUMBER(22,0) Id da filial e-commerce (tabela pcfilialecommerce) CHAVE ESTRANGEIRA (FK)          PCFILIALECOMMERCE
PCPLANPAGAMENTOMARKETPLACE IDCIASHOPMARKETPLACE NUMBER(22,0)     ID do marketplace(tabela PCCIASHOPMARKETPLACE) CHAVE ESTRANGEIRA (FK)       PCCIASHOPMARKETPLACE
PCPLANPAGAMENTOMARKETPLACE             CODPLPAG  NUMBER(4,0)      Código do plano de pagamento (tabela PCPLPAG) CHAVE ESTRANGEIRA (FK)                    PCPLPAG

---
*Documentação gerada automaticamente.*