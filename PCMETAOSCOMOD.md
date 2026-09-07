# 📊 Tabela: PCMETAOSCOMOD

### Estrutura de Colunas e Restrições

       Tabela                Coluna Tipo/Tamanho                                                                                                                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETAOSCOMOD               NUMMETA  NUMBER(8,0)                                                                                                                                                    Campo para armazenar o código da meta            OPERACIONAL                        NaN
PCMETAOSCOMOD            CODSERVICO  NUMBER(6,0)                                                                                                                              Código do serviço\tCampo para armazenar o código do serviço            OPERACIONAL                        NaN
PCMETAOSCOMOD            QTDSERVICO NUMBER(10,0)                                                                                                                            Quantidade serviço\tCampo para armazenar a quantidade serviço            OPERACIONAL                        NaN
PCMETAOSCOMOD             CODPRODUT  NUMBER(6,0)                                                                                                                              Código do produto\tCampo para armazenar o código do produto            OPERACIONAL                        NaN
PCMETAOSCOMOD             QTDPRODUT NUMBER(10,0)                                                                                                                            Quantidade produto\tCampo para armazenar a quantidade produto            OPERACIONAL                        NaN
PCMETAOSCOMOD             CODCLIENT  NUMBER(6,0)                                                                                                                                 Código cliente\tCampo para armazenar o código do cliente            OPERACIONAL                        NaN
PCMETAOSCOMOD             QTDCLIENT NUMBER(10,0)                                                                                                                         Quantidade cliente\tCampo para armazenar a quantidade de cliente            OPERACIONAL                        NaN
PCMETAOSCOMOD PORQTDCLIENTVISITADOS  VARCHAR2(1) Apurar meta por quantidade de clientes visitados\tCampo para armazenar se a meta será apurada por quantidade de clientes visitados (indicador utilizado apenas para a meta por ranking).            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*