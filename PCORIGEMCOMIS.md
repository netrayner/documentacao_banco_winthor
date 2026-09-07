# 📊 Tabela: PCORIGEMCOMIS

### Estrutura de Colunas e Restrições

       Tabela                    Coluna Tipo/Tamanho                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORIGEMCOMIS                    NUMPED NUMBER(10,0)                                                         Número do pedido no Winthor            OPERACIONAL                        NaN
PCORIGEMCOMIS                 ORIGEMPED  VARCHAR2(1)         Origem do pedido, se 'T' Telemarketing, se  'F' Força de vendas, se 'W' Web            OPERACIONAL                        NaN
PCORIGEMCOMIS                   CODPROD  NUMBER(6,0)                                                                   Código do Produto            OPERACIONAL                        NaN
PCORIGEMCOMIS               CODAUXILIAR NUMBER(20,0)                                                           Código de barras auxiliar            OPERACIONAL                        NaN
PCORIGEMCOMIS                    NUMSEQ NUMBER(20,0)                                                               Sequência de inserção            OPERACIONAL                        NaN
PCORIGEMCOMIS                 CODFILIAL  VARCHAR2(2)                                                          Código da filial do pedido            OPERACIONAL                        NaN
PCORIGEMCOMIS                 NUMREGIAO  NUMBER(4,0)                                          Número da região onde o preço foi validado            OPERACIONAL                        NaN
PCORIGEMCOMIS                    PERCOM  NUMBER(8,4)                                                      Percentual de comissão apurado            OPERACIONAL                        NaN
PCORIGEMCOMIS                   PERDESC NUMBER(18,6)                                           Percentual de desconto concedido pelo RCA            OPERACIONAL                        NaN
PCORIGEMCOMIS                   CODUSUR  NUMBER(4,0)                                                                       Código do RCA            OPERACIONAL                        NaN
PCORIGEMCOMIS                    CODCLI  NUMBER(6,0)                                                                   Código do cliente            OPERACIONAL                        NaN
PCORIGEMCOMIS                    CODCOB  VARCHAR2(4)                                                                  Código da cobrança            OPERACIONAL                        NaN
PCORIGEMCOMIS                  CODPLPAG  NUMBER(4,0)                                                        Código do Plano de pagamento            OPERACIONAL                        NaN
PCORIGEMCOMIS            CODROTINACOMIS  VARCHAR2(4)                          Rotina utilizada para lançamento do percentual de comissão            OPERACIONAL                        NaN
PCORIGEMCOMIS                  CODCOMIS  NUMBER(8,0)                                             Código do registro da comissão validada            OPERACIONAL                        NaN
PCORIGEMCOMIS              TIPOCOMISSAO  VARCHAR2(1)                                                        Tipo de comissão da pcprodut            OPERACIONAL                        NaN
PCORIGEMCOMIS                  TIPOVEND  VARCHAR2(2)                                                              tipo venda da pcusuari            OPERACIONAL                        NaN
PCORIGEMCOMIS                 TIPOVENDA  VARCHAR2(2)                                                    tipo venda do plano de pagamento            OPERACIONAL                        NaN
PCORIGEMCOMIS              CODLINHAPROD  NUMBER(6,0)                                                          codigo de linha do produto            OPERACIONAL                        NaN
PCORIGEMCOMIS     TIPOAVALIACAOCOMISSAO  NUMBER(2,0)  Registra o valor do Parâmetro 2273 da rotina 132 no momento do cálculo da comissão            OPERACIONAL                        NaN
PCORIGEMCOMIS ORDEMAVALIACAOCOMISSAORCA  NUMBER(2,0)  Registra o valor do Parâmetro 1185 da rotina 132 no momento do cálculo da comissão            OPERACIONAL                        NaN
PCORIGEMCOMIS         USACOMISSAOPORRCA  VARCHAR2(1)  Registra o valor do Parâmetro 1266 da rotina 132 no momento do cálculo da comissão            OPERACIONAL                        NaN
PCORIGEMCOMIS     USACOMISSAOPORCLIENTE  VARCHAR2(1) Registra o valor do Parâmetro 1265 da  rotina 132 no momento do cálculo da comissão            OPERACIONAL                        NaN
PCORIGEMCOMIS   USACOMISSAOPORLINHAPROD  VARCHAR2(1)  Registra o valor do Parâmetro 1103 da rotina 132 no momento do cálculo da comissão            OPERACIONAL                        NaN
PCORIGEMCOMIS      COMISSAORCATIPOVENDA  VARCHAR2(1)  Registra o valor do Parâmetro 1514 da rotina 132 no momento do cálculo da comissão            OPERACIONAL                        NaN
PCORIGEMCOMIS    CONSIDERARCOMISSAOZERO  VARCHAR2(1)  Registra o valor do Parâmetro 2220 da rotina 132 no momento do cálculo da comissão            OPERACIONAL                        NaN
PCORIGEMCOMIS                DTINCLUSAO         DATE                                                        Data de inclusao do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*