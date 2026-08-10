# 📊 Tabela: PCFILASTATUSPEDIDOECOMMERCE

### Estrutura de Colunas e Restrições

                     Tabela                Coluna  Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILASTATUSPEDIDOECOMMERCE                    ID  NUMBER(10,0)                         Identificador do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCFILASTATUSPEDIDOECOMMERCE NUMEROPEDIDOECOMMERCE  NUMBER(10,0)                     Número do pedido do ecommerce            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE       NUMEROPEDIDOERP  NUMBER(10,0)                           Número do pedido do ERP            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE             CODFILIAL   VARCHAR2(2)                                  Código da filial            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE                  DATA          DATE                                  Data de inclusão            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE                  ACAO VARCHAR2(100)                                              Ação            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE          STATUSPEDIDO VARCHAR2(100)                                  Status do pedido            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE   STATUSPROCESSAMENTO VARCHAR2(100)                           Status do processamento            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE             TENTATIVA  NUMBER(10,0)                                         Tentativa            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE     DATAPROCESSAMENTO          DATE                             Data do processamento            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE     TIPOSINCRONIZACAO VARCHAR2(100)                             Tipo de sincronização            OPERACIONAL                        NaN
PCFILASTATUSPEDIDOECOMMERCE          IDREMESSAWEB  NUMBER(22,0) id da remessa web quando pedido for multi remessa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*