# 📊 Tabela: PCPRECARREG

### Estrutura de Colunas e Restrições

     Tabela         Coluna   Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRECARREG      NUMPRECAR    NUMBER(8,0)                                      Número do pré-carga    CHAVE PRIMÁRIA (PK)                        NaN
PCPRECARREG        DTSAIDA           DATE                               Data de saída da pré-carga            OPERACIONAL                        NaN
PCPRECARREG   CODMOTORISTA    NUMBER(8,0)                                      Código do motorista            OPERACIONAL                        NaN
PCPRECARREG     CODVEICULO    NUMBER(4,0)                                        Código do veículo            OPERACIONAL                        NaN
PCPRECARREG        TOTPESO   NUMBER(12,4)                               Total do peso da pré-carga            OPERACIONAL                        NaN
PCPRECARREG      TOTVOLUME   NUMBER(12,4)                             Total do volume da pré-carga            OPERACIONAL                        NaN
PCPRECARREG        VLTOTAL   NUMBER(12,4)                                 Valor total da pré-carga            OPERACIONAL                        NaN
PCPRECARREG   CODFUNCFECHA    NUMBER(8,0)             Código do funcionário que fechou a pré-carga            OPERACIONAL                        NaN
PCPRECARREG        DTFECHA           DATE                          Data do fechamento da pré-carga            OPERACIONAL                        NaN
PCPRECARREG        DESTINO   VARCHAR2(20)                                        Destino principal            OPERACIONAL                        NaN
PCPRECARREG       NUMNOTAS    NUMBER(4,0)                     Número de notas fiscais da pré-carga            OPERACIONAL                        NaN
PCPRECARREG       PREVCHEQ           DATE                              Data de previsão de entrega            OPERACIONAL                        NaN
PCPRECARREG      DTRETORNO           DATE                               Data de retorno da entrega            OPERACIONAL                        NaN
PCPRECARREG        CODCONF    NUMBER(8,0)                                     Código do conferente            OPERACIONAL                        NaN
PCPRECARREG     CODFUNCMON    NUMBER(8,0)                          Código do montador da pré-carga            OPERACIONAL                        NaN
PCPRECARREG        DATAMON           DATE                            Data de montagem da pré-carga            OPERACIONAL                        NaN
PCPRECARREG        QTITENS    NUMBER(4,0)                         Quantidade de itens na pré-carga            OPERACIONAL                        NaN
PCPRECARREG DTSAIDAVEICULO           DATE                                 Data de saída do veículo            OPERACIONAL                        NaN
PCPRECARREG   CODROTAPRINC    NUMBER(4,0)                                 Código da rota principal            OPERACIONAL                        NaN
PCPRECARREG      QTPEDIDOS    NUMBER(4,0)                                    Quantidade de pedidos            OPERACIONAL                        NaN
PCPRECARREG       OBSFRETE VARCHAR2(4000)                                      Observação de frete            OPERACIONAL                        NaN
PCPRECARREG CODTIPOVEICULO    NUMBER(3,0)                                Código do tipo do veículo            OPERACIONAL                        NaN
PCPRECARREG     OBSDESTINO   VARCHAR2(80)                                    Observação do destino            OPERACIONAL                        NaN
PCPRECARREG     NUMPEDTV10   NUMBER(10,0) Número do pedido TV10 gerado para transferir os produtos            OPERACIONAL                        NaN
PCPRECARREG        NUMONDA   NUMBER(18,6)                                  Indica o número da onda            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*