# 📊 Tabela: PCAGENDAPEDIDO

### Estrutura de Colunas e Restrições

        Tabela                Coluna  Tipo/Tamanho                                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDAPEDIDO                NUMPED  NUMBER(10,0)                                                                                Numero pedido de compra             OPERACIONAL                        NaN
PCAGENDAPEDIDO               NUMPED1  NUMBER(10,0) Numero pedido de compra isso ocorre porque no caminhão pode vir uma carga com até 5 pedidos diferentes.            OPERACIONAL                        NaN
PCAGENDAPEDIDO               NUMPED2  NUMBER(10,0) Numero pedido de compra isso ocorre porque no caminhão pode vir uma carga com até 5 pedidos diferentes.            OPERACIONAL                        NaN
PCAGENDAPEDIDO               NUMPED3  NUMBER(10,0) Numero pedido de compra isso ocorre porque no caminhão pode vir uma carga com até 5 pedidos diferentes.            OPERACIONAL                        NaN
PCAGENDAPEDIDO               NUMPED4  NUMBER(10,0) Numero pedido de compra isso ocorre porque no caminhão pode vir uma carga com até 5 pedidos diferentes.            OPERACIONAL                        NaN
PCAGENDAPEDIDO              DTAGENDA          DATE                                                                                    Data do agendamento     CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAPEDIDO            HORAAGENDA   VARCHAR2(5)                                                                                    Hora do agendamento     CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAPEDIDO           HORACHEGADA   VARCHAR2(5)                                                                              Hora que o caminhão chegou            OPERACIONAL                        NaN
PCAGENDAPEDIDO             TIPOCARGA   NUMBER(1,0)                                                                                  Paletizada ou estivada            OPERACIONAL                        NaN
PCAGENDAPEDIDO        CARACTERISTICA   NUMBER(1,0)                                                                    Seco, Resfriado, Congelado, Perigoso            OPERACIONAL                        NaN
PCAGENDAPEDIDO                  PESO  NUMBER(10,3)                                        Peso da carga de todos os pedidos no caminhão. Igual rotina 209             OPERACIONAL                        NaN
PCAGENDAPEDIDO                VOLUME  NUMBER(10,3)                                      Volume da carga de todos os pedidos no caminhão. Igual rotina 209             OPERACIONAL                        NaN
PCAGENDAPEDIDO              QTCAIXAS  NUMBER(10,2)                                                            Quantidade de caixas que vieram no caminhão             OPERACIONAL                        NaN
PCAGENDAPEDIDO         TEMPODESCARGA   VARCHAR2(5)                                                                     Tempo que demorou para descarregar             OPERACIONAL                        NaN
PCAGENDAPEDIDO             TIPOFRETE   VARCHAR2(1)                                                                                             CIF ou FOB             OPERACIONAL                        NaN
PCAGENDAPEDIDO                   BOX   NUMBER(2,0)                                          Numero do box onde o caminhão será descarregado. Vai de 0 a 9     CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAPEDIDO                   OBS VARCHAR2(200)                                                    Campo observação para anotar algum detalhe da carga             OPERACIONAL                        NaN
PCAGENDAPEDIDO                 SENHA  VARCHAR2(20)                               Campo contém a senha informada ao caminhoneiro. Sua geração é automatica             OPERACIONAL                        NaN
PCAGENDAPEDIDO TEMPODESCARGAPREVISTO   VARCHAR2(5)                                                                   Previsão de tempo do descarregamento             OPERACIONAL                        NaN
PCAGENDAPEDIDO             HORASAIDA   VARCHAR2(5)                                                                        Hora que o caminhão esta saindo             OPERACIONAL                        NaN
PCAGENDAPEDIDO       HORALIBERACAONF   VARCHAR2(5)                                        Hora que a nota fiscal caminhoneiro foi liberada pela expedição             OPERACIONAL                        NaN
PCAGENDAPEDIDO           AGENDAMENTO   VARCHAR2(1)                                                         Campo para informar se é um agendamento ou não             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*