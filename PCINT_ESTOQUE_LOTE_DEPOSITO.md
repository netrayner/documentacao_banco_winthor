# 📊 Tabela: PCINT_ESTOQUE_LOTE_DEPOSITO

### Estrutura de Colunas e Restrições

                     Tabela            Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINT_ESTOQUE_LOTE_DEPOSITO CODIGODEPOSITOWMS NUMBER(10,0) Código Depósito WMS    CHAVE PRIMÁRIA (PK)                        NaN
PCINT_ESTOQUE_LOTE_DEPOSITO         CODFILIAL  VARCHAR2(1)    Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCINT_ESTOQUE_LOTE_DEPOSITO           CODPROD  NUMBER(6,0)   Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCINT_ESTOQUE_LOTE_DEPOSITO           NUMLOTE VARCHAR2(15)      Número do Lote    CHAVE PRIMÁRIA (PK)                        NaN
PCINT_ESTOQUE_LOTE_DEPOSITO        DTVALIDADE         DATE    Data de Validade            OPERACIONAL                        NaN
PCINT_ESTOQUE_LOTE_DEPOSITO    DATAFABRICACAO         DATE  Data de Fabricação            OPERACIONAL                        NaN
PCINT_ESTOQUE_LOTE_DEPOSITO        QUANTIDADE NUMBER(22,8)          Quantidade            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*