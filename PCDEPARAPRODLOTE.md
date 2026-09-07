# 📊 Tabela: PCDEPARAPRODLOTE

### Estrutura de Colunas e Restrições

          Tabela         Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEPARAPRODLOTE        CODPROD  NUMBER(6,0)                                     Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPARAPRODLOTE      CODFILIAL  VARCHAR2(2)                                      Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPARAPRODLOTE        NUMLOTE VARCHAR2(15)                                Número do Lote Winthor    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPARAPRODLOTE SEQLOTEESTOQUE NUMBER(11,0) Sequencial que representa o lote no PDV Supermercados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*