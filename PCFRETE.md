# 📊 Tabela: PCFRETE

### Estrutura de Colunas e Restrições

 Tabela             Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFRETE           CODFRETE NUMBER(10,0)                                                              NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFRETE          CODFORNEC  NUMBER(6,0)                                                              NaN            OPERACIONAL                        NaN
PCFRETE     CODPRACAORIGEM  NUMBER(4,0)                                                              NaN            OPERACIONAL                        NaN
PCFRETE    CODPRACADESTINO  NUMBER(4,0)                                                              NaN            OPERACIONAL                        NaN
PCFRETE           VLMINIMO NUMBER(12,2)                                                              NaN            OPERACIONAL                        NaN
PCFRETE           PERFRETE  NUMBER(8,4)                                                              NaN            OPERACIONAL                        NaN
PCFRETE           ALIQICMS  NUMBER(8,4)                                                              NaN            OPERACIONAL                        NaN
PCFRETE VLFRETEKGEXCEDENTE NUMBER(12,4)                                                              NaN            OPERACIONAL                        NaN
PCFRETE           SITUACAO  VARCHAR2(1)                                                              NaN            OPERACIONAL                        NaN
PCFRETE           VLFRETE1 NUMBER(12,2)                                                    Valor Frete 1            OPERACIONAL                        NaN
PCFRETE           VLFRETE2 NUMBER(12,2)                                                    Valor Frete 2            OPERACIONAL                        NaN
PCFRETE           VLFRETE3 NUMBER(12,2)                                                    Valor Frete 3            OPERACIONAL                        NaN
PCFRETE           VLFRETE4 NUMBER(12,2)                                                    Valor Frete 4            OPERACIONAL                        NaN
PCFRETE           VLFRETE5 NUMBER(12,2)                                                    Valor Frete 5            OPERACIONAL                        NaN
PCFRETE           VLFRETE6 NUMBER(12,2)                                                    Valor Frete 6            OPERACIONAL                        NaN
PCFRETE           VLFRETE7 NUMBER(12,2)                                                    Valor Frete 7            OPERACIONAL                        NaN
PCFRETE           VLFRETE8 NUMBER(12,2)                                                    Valor Frete 8            OPERACIONAL                        NaN
PCFRETE           VLFRETE9 NUMBER(12,2)                                                    Valor Frete 9            OPERACIONAL                        NaN
PCFRETE          VLFRETE10 NUMBER(12,2)                                                   Valor Frete 10            OPERACIONAL                        NaN
PCFRETE              VLTAS NUMBER(18,6)                                                              NaN            OPERACIONAL                        NaN
PCFRETE        ZONAFLUVIAL  VARCHAR2(1)                                                              NaN            OPERACIONAL                        NaN
PCFRETE         DTEXCLUSAO         DATE                                                              NaN            OPERACIONAL                        NaN
PCFRETE    CODFUNCEXCLUSAO  NUMBER(6,0)                                                              NaN            OPERACIONAL                        NaN
PCFRETE          VLPERGRIS  NUMBER(8,4)                                                              NaN            OPERACIONAL                        NaN
PCFRETE          VLPEDAGIO NUMBER(12,2)                                                              NaN            OPERACIONAL                        NaN
PCFRETE            PERGRIS  NUMBER(8,4)                                                              NaN            OPERACIONAL                        NaN
PCFRETE VALORCOMISSAOFRETE NUMBER(12,2)                  Indica o valor da comissão paga a esta entrega.            OPERACIONAL                        NaN
PCFRETE   VLFAIXAPEDAGIOKG NUMBER(12,4)                                         FAIXA DE PEDÁGIO POR KG.            OPERACIONAL                        NaN
PCFRETE         VLDESPACHO NUMBER(12,4)                                                VALOR DE DESPACHO            OPERACIONAL                        NaN
PCFRETE               VLKG NUMBER(12,4)                                                    VALOR POR KG.            OPERACIONAL                        NaN
PCFRETE          PERSEGURO NUMBER(12,4)                                             PERCENTUAL DO SEGURO            OPERACIONAL                        NaN
PCFRETE              VLTDE NUMBER(12,4)                          VALOR DA TAXA DE DIFILCUDADE DE ENTREGA            OPERACIONAL                        NaN
PCFRETE           VLPALETE NUMBER(12,4)                                                 VALOR POR PALETE            OPERACIONAL                        NaN
PCFRETE          VLCUBAGEM NUMBER(12,4)                                           VALOR POR METRO CÚBICO            OPERACIONAL                        NaN
PCFRETE  TRANSPPRIORITARIA  VARCHAR2(1)                              DEFINE PRIORIDADE DA TRANSPORTADORA            OPERACIONAL                        NaN
PCFRETE          TIPOFRETE  VARCHAR2(1)                                      Tipo do frete a considerar.            OPERACIONAL                        NaN
PCFRETE         PERCFRETE1 NUMBER(12,2)                                            Percentual do Frete 1            OPERACIONAL                        NaN
PCFRETE         PERCFRETE2 NUMBER(12,2)                                            Percentual do Frete 2            OPERACIONAL                        NaN
PCFRETE         PERCFRETE3 NUMBER(12,2)                                            Percentual do Frete 3            OPERACIONAL                        NaN
PCFRETE         PERCFRETE4 NUMBER(12,2)                                            Percentual do Frete 4            OPERACIONAL                        NaN
PCFRETE         PERCFRETE5 NUMBER(12,2)                                            Percentual do Frete 5            OPERACIONAL                        NaN
PCFRETE         PERCFRETE6 NUMBER(12,2)                                            Percentual do Frete 6            OPERACIONAL                        NaN
PCFRETE         PERCFRETE7 NUMBER(12,2)                                            Percentual do Frete 7            OPERACIONAL                        NaN
PCFRETE         PERCFRETE8 NUMBER(12,2)                                            Percentual do Frete 8            OPERACIONAL                        NaN
PCFRETE         PERCFRETE9 NUMBER(12,2)                                            Percentual do Frete 9            OPERACIONAL                        NaN
PCFRETE        PERCFRETE10 NUMBER(12,2)                                           Percentual do Frete 10            OPERACIONAL                        NaN
PCFRETE         VLKGFRETE1 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE         VLKGFRETE2 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE         VLKGFRETE3 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE         VLKGFRETE4 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE         VLKGFRETE5 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE         VLKGFRETE6 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE         VLKGFRETE7 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE         VLKGFRETE8 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE         VLKGFRETE9 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE        VLKGFRETE10 NUMBER(12,2)                                               VALOR FRETE POR KG            OPERACIONAL                        NaN
PCFRETE          CODFILIAL  VARCHAR2(2)                                                 CÓDIGO DA FILIAL            OPERACIONAL                        NaN
PCFRETE        COLUNAFRETE  VARCHAR2(2)                                                  COLUNA DO FRETE            OPERACIONAL                        NaN
PCFRETE        KMDISTANCIA  NUMBER(8,0)                           KM da distância entre origem e destino            OPERACIONAL                        NaN
PCFRETE  APLICAROUTRASDESP  VARCHAR2(1) Aplicar o frete automático no valor do frete ou outras despesas.            OPERACIONAL                        NaN
PCFRETE          VLFRETENF NUMBER(12,4)                                                Valor nota fiscal            OPERACIONAL                        NaN
PCFRETE       VLTAXACOLETA NUMBER(12,2)                                 Valor da taxa de coleta do frete            OPERACIONAL                        NaN
PCFRETE             TIPOFJ  VARCHAR2(1)                             Tipo do cliente (físico ou jurídico)            OPERACIONAL                        NaN
PCFRETE   VLMINIMOCOBFRETE NUMBER(12,2)                                                     NUMBER(12,2)            OPERACIONAL                        NaN
PCFRETE    VLMINIMOENTREGA NUMBER(12,2)                                                     NUMBER(12,2)            OPERACIONAL                        NaN
PCFRETE         DTMXSALTER         DATE                                                              NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*