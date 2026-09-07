# 📊 Tabela: PCITEMCOTACAOCIAP

### Estrutura de Colunas e Restrições

           Tabela     Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMCOTACAOCIAP  CODFILIAL  VARCHAR2(2)             Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAOCIAP    CODPROD  NUMBER(6,0)              Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAOCIAP  CODFORNEC  NUMBER(6,0)          Código do Fornecedor    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAOCIAP NUMCOTACAO  NUMBER(8,0)             Número da cotação    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAOCIAP    PCOMPRA NUMBER(18,6)               Preço de compra            OPERACIONAL                        NaN
PCITEMCOTACAOCIAP   GANHADOR  VARCHAR2(1) Ganhador da cotação de compra            OPERACIONAL                        NaN
PCITEMCOTACAOCIAP     NUMPED NUMBER(10,0)    Número do pedido de compra            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*