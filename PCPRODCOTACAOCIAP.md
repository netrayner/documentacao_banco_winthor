# 📊 Tabela: PCPRODCOTACAOCIAP

### Estrutura de Colunas e Restrições

           Tabela       Coluna Tipo/Tamanho   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODCOTACAOCIAP    CODFILIAL  VARCHAR2(2)      Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODCOTACAOCIAP      CODPROD  NUMBER(6,0)     Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODCOTACAOCIAP   NUMCOTACAO  NUMBER(8,0)     Número da cotação    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODCOTACAOCIAP     QTPEDIDA NUMBER(14,4) Qtde pedida de compra            OPERACIONAL                        NaN
PCPRODCOTACAOCIAP PEDIDOGERADO  VARCHAR2(1)     Pedido foi gerado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*