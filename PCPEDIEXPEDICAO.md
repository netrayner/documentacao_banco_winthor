# 📊 Tabela: PCPEDIEXPEDICAO

### Estrutura de Colunas e Restrições

         Tabela       Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIEXPEDICAO CODEXPEDICAO NUMBER(20,0)                   CÓDIGO DE EXPEDICAO    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIEXPEDICAO       NUMPED NUMBER(10,0)             NÚMERO DO PEDIDO EXPEDIDO            OPERACIONAL                        NaN
PCPEDIEXPEDICAO      CODPROD  NUMBER(6,0)            CÓDIGO DO PRODUTO EXPEDIDO            OPERACIONAL                        NaN
PCPEDIEXPEDICAO       NUMSEQ NUMBER(20,0) NÚMERO SEQUENCIAL DO PRODUTO EXPEDIDO            OPERACIONAL                        NaN
PCPEDIEXPEDICAO   QTEXPEDIDA NUMBER(20,6)        QUANTIDADE EXPEDIDA DO PRODUTO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*