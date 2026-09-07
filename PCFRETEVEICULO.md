# 📊 Tabela: PCFRETEVEICULO

### Estrutura de Colunas e Restrições

        Tabela        Coluna   Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFRETEVEICULO    CODVEICULO    NUMBER(4,0)                        Código do veículo.            OPERACIONAL                        NaN
PCFRETEVEICULO        NUMCAR    NUMBER(8,0)                   Código do carregamento.            OPERACIONAL                        NaN
PCFRETEVEICULO         QTPED    NUMBER(4,0)                  Qtde. Pedidos entregues.            OPERACIONAL                        NaN
PCFRETEVEICULO       VLTOTAL   NUMBER(14,2)        Vl. total dos pedidos entregues. .            OPERACIONAL                        NaN
PCFRETEVEICULO         EXTRA   NUMBER(14,2)       Vl. extras para o cálculo de frete.            OPERACIONAL                        NaN
PCFRETEVEICULO       PEDAGIO   NUMBER(14,2)                         Valor de pedágio.            OPERACIONAL                        NaN
PCFRETEVEICULO  VLTOTALFRETE   NUMBER(14,2)                     Valor final do frete.            OPERACIONAL                        NaN
PCFRETEVEICULO       DTFRETE           DATE                 Data de geração do frete.            OPERACIONAL                        NaN
PCFRETEVEICULO    DTALTFRETE           DATE               Data de alteração do frete.            OPERACIONAL                        NaN
PCFRETEVEICULO        ROTINA   VARCHAR2(40)                 Rotina geradora do frete.            OPERACIONAL                        NaN
PCFRETEVEICULO       USUARIO   VARCHAR2(30)                 Usuário gerador do frete.            OPERACIONAL                        NaN
PCFRETEVEICULO      DESCARGA   NUMBER(14,2)                        Valor de descarga.            OPERACIONAL                        NaN
PCFRETEVEICULO        VLFIXO   NUMBER(14,2)           Valor fixo de entrega da carga.            OPERACIONAL                        NaN
PCFRETEVEICULO         VLPED   NUMBER(14,2)              Valor de entrega por pedido.            OPERACIONAL                        NaN
PCFRETEVEICULO        RECNUM    NUMBER(8,0)                     Número de lançamento.            OPERACIONAL                        NaN
PCFRETEVEICULO     CODFILIAL    VARCHAR2(2)               Número da filial do pedido.            OPERACIONAL                        NaN
PCFRETEVEICULO        VLGRIS   NUMBER(14,2)                    Valor Gris do Veículo.            OPERACIONAL                        NaN
PCFRETEVEICULO      VLSEGURO   NUMBER(14,2)               Valor do seguro do veiculo.            OPERACIONAL                        NaN
PCFRETEVEICULO PESOVSVALORKG   NUMBER(14,2) Peso em relação ao valor kg transportado.            OPERACIONAL                        NaN
PCFRETEVEICULO      OBSFRETE VARCHAR2(4000)               Observação de frete veículo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*