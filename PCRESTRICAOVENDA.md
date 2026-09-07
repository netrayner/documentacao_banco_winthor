# 📊 Tabela: PCRESTRICAOVENDA

### Estrutura de Colunas e Restrições

          Tabela           Coluna Tipo/Tamanho                                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRESTRICAOVENDA     CODRESTRICAO NUMBER(10,0)                                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRESTRICAOVENDA           CODCLI  NUMBER(6,0)                                                                                                               NaN            OPERACIONAL                        NaN
PCRESTRICAOVENDA          CODPROD  NUMBER(6,0)                                                                                                               NaN            OPERACIONAL                        NaN
PCRESTRICAOVENDA        NUMREGIAO  NUMBER(4,0)                                                                                                               NaN            OPERACIONAL                        NaN
PCRESTRICAOVENDA        CODFORNEC  NUMBER(6,0)                                                                                                               NaN            OPERACIONAL                        NaN
PCRESTRICAOVENDA         CODPRACA  NUMBER(4,0)                                                                                                               NaN            OPERACIONAL                        NaN
PCRESTRICAOVENDA          CODUSUR  NUMBER(4,0)                                                                                                               NaN            OPERACIONAL                        NaN
PCRESTRICAOVENDA          CODATIV  NUMBER(6,0)                                                                                                               NaN            OPERACIONAL                        NaN
PCRESTRICAOVENDA    CLASSEPRODUTO  VARCHAR2(1)                                                                                                               NaN            OPERACIONAL                        NaN
PCRESTRICAOVENDA          CODEPTO  NUMBER(6,0)                                                                    Indica a restrição de venda por departamento.             OPERACIONAL                        NaN
PCRESTRICAOVENDA           CODSEC  NUMBER(6,0)                                                                           Indica a restrição de venda por seção.             OPERACIONAL                        NaN
PCRESTRICAOVENDA    CODSUPERVISOR  NUMBER(4,0)                                                                                            Código do Supervisor.             OPERACIONAL                        NaN
PCRESTRICAOVENDA           TIPOFJ  VARCHAR2(1)                                                                           Tipo do cliente (F-Física J-Jurídico).             OPERACIONAL                        NaN
PCRESTRICAOVENDA        CONDVENDA  NUMBER(5,0)                                                                                                     Tipo de venda            OPERACIONAL                        NaN
PCRESTRICAOVENDA        ORIGEMPED  VARCHAR2(1) Origem do pedido (O-Todas, T-Telemarketing, B-Balcão, R-Balcão Reserva, C-Call Center, F-Força de Vendas, W-WEB).            OPERACIONAL                        NaN
PCRESTRICAOVENDA        CODFILIAL  VARCHAR2(2)                                                                                                  Código da Filial            OPERACIONAL                        NaN
PCRESTRICAOVENDA    FRETEDESPACHO  VARCHAR2(1)                                                                                                   Frete despacho.            OPERACIONAL                        NaN
PCRESTRICAOVENDA VALORMINIMOVENDA NUMBER(18,6)                                                                                            Valor mínimo de venda.            OPERACIONAL                        NaN
PCRESTRICAOVENDA      CODAUXILIAR NUMBER(20,0)                                                                            Restrigir venda utilizando codauxiliar            OPERACIONAL                        NaN
PCRESTRICAOVENDA           CODCOB  VARCHAR2(4)                                                                                                Código da cobrança            OPERACIONAL                        NaN
PCRESTRICAOVENDA         CODPLPAG  NUMBER(4,0)                                                                                       Código do plano de pagameno            OPERACIONAL                        NaN
PCRESTRICAOVENDA           MOTIVO VARCHAR2(50)                                                                                      MOTIVO DA RESTRICAO DA VENDA            OPERACIONAL                        NaN
PCRESTRICAOVENDA         CODMARCA  NUMBER(8,0)                                                                                         Indica o código da marca.            OPERACIONAL                        NaN
PCRESTRICAOVENDA       DTMXSALTER         DATE                                                                                                               NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*