# 📊 Tabela: PCTROCAFVMANIF

### Estrutura de Colunas e Restrições

        Tabela           Coluna Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTROCAFVMANIF        NUMPEDRCA NUMBER(10,0)                                                  Número do pedido manifesto.            OPERACIONAL                        NaN
PCTROCAFVMANIF        NUMPEDTV5 NUMBER(10,0)              Número do pedido bonificado utilizado para indenizar o cliente.            OPERACIONAL                        NaN
PCTROCAFVMANIF        NUMPEDFAT NUMBER(10,0)                      Número do pedido já faturado que está sendo indenizado.            OPERACIONAL                        NaN
PCTROCAFVMANIF           CODCLI  NUMBER(6,0)                                       Código do cliente do pedido manifesto.            OPERACIONAL                        NaN
PCTROCAFVMANIF          CODUSUR  NUMBER(4,0)                                                  RCA responsável pela troca.            OPERACIONAL                        NaN
PCTROCAFVMANIF          CODPROD  NUMBER(6,0)                                    Código do produto que está sendo trocado.            OPERACIONAL                        NaN
PCTROCAFVMANIF               QT NUMBER(18,6)                                Quantidade do produto que está sendo trocado.            OPERACIONAL                        NaN
PCTROCAFVMANIF          PTABELA NUMBER(18,6)                           Preço de tabela do produto que está sendo trocado.            OPERACIONAL                        NaN
PCTROCAFVMANIF        DTVALPROD         DATE                          Data de validade do produto que está sendo trocado.            OPERACIONAL                        NaN
PCTROCAFVMANIF     CODPRODTROCA  NUMBER(6,0)                                   Código do produto que está sendo entregue.            OPERACIONAL                        NaN
PCTROCAFVMANIF          QTTROCA NUMBER(18,6)                               Quantidade do produt oque está sendo entregue.            OPERACIONAL                        NaN
PCTROCAFVMANIF     PTABELATROCA NUMBER(18,6)                          Preço de tabela do produto que está sendo entregue.            OPERACIONAL                        NaN
PCTROCAFVMANIF   DTVALPRODTROCA         DATE                         Data de validade do produto que está sendo entregue.            OPERACIONAL                        NaN
PCTROCAFVMANIF           AVARIA  VARCHAR2(1)                            Informa se o produto a ser trocado está avariado.            OPERACIONAL                        NaN
PCTROCAFVMANIF       NUMINDENIZ NUMBER(10,0)                                      Número da indenizacao gerada na pcindc.            OPERACIONAL                        NaN
PCTROCAFVMANIF          DTDEVOL         DATE Data da devolução. Preenchido após a entrada da mercadoria pela rotina 1303.            OPERACIONAL                        NaN
PCTROCAFVMANIF           MOTIVO VARCHAR2(30)                 Motivo selecionado no momento da devolução pela rotina 1303.            OPERACIONAL                        NaN
PCTROCAFVMANIF      CODAUXILIAR NUMBER(20,0)                                         Codigo de barras do produto enviado.            OPERACIONAL                        NaN
PCTROCAFVMANIF CODAUXILIARTROCA NUMBER(20,0)                                 Codigo de barras do produto a ser recolhido.            OPERACIONAL                        NaN
PCTROCAFVMANIF          NUMNOTA NUMBER(10,0)                                 Recebe o número da nota gerada na devolução.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*