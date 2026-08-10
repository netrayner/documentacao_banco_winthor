# 📊 Tabela: PCDIVERGENCIASPREENT

### Estrutura de Colunas e Restrições

              Tabela                Coluna Tipo/Tamanho     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDIVERGENCIASPREENT           NUMTRANSENT NUMBER(10,0)    Transação de entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCDIVERGENCIASPREENT                NUMSEQ NUMBER(10,0)       Sequencia do item    CHAVE PRIMÁRIA (PK)                        NaN
PCDIVERGENCIASPREENT               CODPROD NUMBER(10,0)       Codigo do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCDIVERGENCIASPREENT               NUMLOTE VARCHAR2(15)          Numero do Lote            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT                NUMPED  NUMBER(9,0)        Numero de pedido            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT      PRECOBRUTOPEDIDO NUMBER(18,6)  Preço de compra pedido            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT        PERCDESCPEDIDO NUMBER(18,6)         Desconto pedido            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT    PRECOLIQUIDOPEDIDO NUMBER(18,6)    Preço liquido pedido            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT PRECOMERCADORIAPEDIDO NUMBER(18,6) Preço mercadoria pedido            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT            QTDEPEDIDO NUMBER(20,6)       Quantidade pedido            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT        PRECOBRUTONOTA NUMBER(18,6)    Preço de compra nota            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT          PERCDESCNOTA NUMBER(18,6)           Desconto nota            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT      PRECOLIQUIDONOTA NUMBER(18,6)      Preço liquido nota            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT   PRECOMERCADORIANOTA NUMBER(18,6)   Preço mercadoria nota            OPERACIONAL                        NaN
PCDIVERGENCIASPREENT              QTDENOTA NUMBER(20,6)         Quantidade nota            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*