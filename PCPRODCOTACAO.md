# 📊 Tabela: PCPRODCOTACAO

### Estrutura de Colunas e Restrições

       Tabela              Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODCOTACAO           CODFILIAL  VARCHAR2(2)                                            Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODCOTACAO             CODPROD  NUMBER(6,0)                                           Indica o código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODCOTACAO          NUMCOTACAO  NUMBER(8,0)                                           Indica o número da cotação.    CHAVE PRIMÁRIA (PK)                  PCCOTACAO
PCPRODCOTACAO            QTPEDIDA NUMBER(14,4)                                             Indica quantidade pedida.            OPERACIONAL                        NaN
PCPRODCOTACAO          QTSUGESTAO NUMBER(14,4)                                 Indica quantidade sugestão de compra.            OPERACIONAL                        NaN
PCPRODCOTACAO        PEDIDOGERADO  VARCHAR2(1) Verifica se gerou ou não o pedido de compra para o pedido da cotação.            OPERACIONAL                        NaN
PCPRODCOTACAO TIPOEMBALAGEMPEDIDO  VARCHAR2(1)     Representa a unidade em que o item foi digitado (Venda ou Master)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*