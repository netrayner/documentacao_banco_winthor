# 📊 Tabela: PCPEDIDORASTREIOECOMMERCE

### Estrutura de Colunas e Restrições

                   Tabela                Coluna   Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIDORASTREIOECOMMERCE                    ID   NUMBER(10,0)      Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIDORASTREIOECOMMERCE NUMEROPEDIDOECOMMERCE   NUMBER(10,0) Número do pedido no ecommerce            OPERACIONAL                        NaN
PCPEDIDORASTREIOECOMMERCE       NUMEROPEDIDOERP   NUMBER(10,0)   Número do pedido no Winthor            OPERACIONAL                        NaN
PCPEDIDORASTREIOECOMMERCE         ENVIOCOMPLETO    NUMBER(1,0)                 Envio completo            OPERACIONAL                        NaN
PCPEDIDORASTREIOECOMMERCE             CODFILIAL    VARCHAR2(2)              Código da filial            OPERACIONAL                        NaN
PCPEDIDORASTREIOECOMMERCE           URLRASTREIO VARCHAR2(1000)                Url de rastreio            OPERACIONAL                        NaN
PCPEDIDORASTREIOECOMMERCE                  DATA           DATE              Data de inclusão            OPERACIONAL                        NaN
PCPEDIDORASTREIOECOMMERCE        CODIGORASTREIO   VARCHAR2(50)            Código de rastreio            OPERACIONAL                        NaN
PCPEDIDORASTREIOECOMMERCE   STATUSPROCESSAMENTO  VARCHAR2(100)        Status do processamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*