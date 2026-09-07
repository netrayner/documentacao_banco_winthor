# 📊 Tabela: PCPEDIDOECOMMERCE

### Estrutura de Colunas e Restrições

           Tabela                 Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIDOECOMMERCE                     ID  NUMBER(10,0)        Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIDOECOMMERCE  NUMEROPEDIDOECOMMERCE  NUMBER(10,0)      Número de pedido ecommerce            OPERACIONAL                        NaN
PCPEDIDOECOMMERCE              CODFILIAL   VARCHAR2(2)                Código da filial            OPERACIONAL                        NaN
PCPEDIDOECOMMERCE           ORIGEMPEDIDO VARCHAR2(500)                 Origem do pedido            OPERACIONAL                        NaN
PCPEDIDOECOMMERCE             PEDIDOJSON          CLOB                   Pedido em JSON            OPERACIONAL                        NaN
PCPEDIDOECOMMERCE      ULTIMAATUALIZACAO          DATE    Data da última atualização            OPERACIONAL                        NaN
PCPEDIDOECOMMERCE                 STATUS  VARCHAR2(50)                 Status do pedido            OPERACIONAL                        NaN
PCPEDIDOECOMMERCE       DATACANCELAMENTO          DATE             Data de cancelamento            OPERACIONAL                        NaN
PCPEDIDOECOMMERCE NUMEROPEDIDOMARKTPLACE VARCHAR2(150) Número de pedido do marketplace            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*