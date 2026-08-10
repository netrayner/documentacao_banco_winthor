# 📊 Tabela: PCBRINDEEX

### Estrutura de Colunas e Restrições

    Tabela                Coluna   Tipo/Tamanho                                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBRINDEEX               CODBREX    NUMBER(6,0)                                                                       Código da campanha de brinde    CHAVE PRIMÁRIA (PK)                        NaN
PCBRINDEEX             DESCRICAO  VARCHAR2(200)                                                                            \tTítulo da campanha.\t            OPERACIONAL                        NaN
PCBRINDEEX              DTINICIO           DATE                                                   \tInício de vigência da campanha. Data e Hora.\t            OPERACIONAL                        NaN
PCBRINDEEX                 DTFIM           DATE                                                      \tFim de vigência da campanha. Data e Hora.\t            OPERACIONAL                        NaN
PCBRINDEEX              DTCANCEL           DATE                                                                \tData do cancelamento do brinde.\t            OPERACIONAL                        NaN
PCBRINDEEX               VENDAFV    VARCHAR2(1)                                   \tDefine se a campanha deverá ser validada no Força de Vendas.\t            OPERACIONAL                        NaN
PCBRINDEEX                 USAAS    VARCHAR2(1)                          \tS/"N", determina se a campanha estará disponível para o Auto-Serviço.\t            OPERACIONAL                        NaN
PCBRINDEEX              MOVCCRCA    VARCHAR2(1)   \tS/"N", determina se o valor de brinde gerado pela campanha será debitado do C/C Flex do RCA.\t            OPERACIONAL                        NaN
PCBRINDEEX          QTMAXBRINDES   NUMBER(18,6) \tDetermina uma qtde máxima de brindes a serem contemplados pela campanha("Estoque" de brindes).\t            OPERACIONAL                        NaN
PCBRINDEEX           VENDABALCAO    VARCHAR2(1)                                      \tDefine se a campanha deverá ser validada na venda Balcão.\t            OPERACIONAL                        NaN
PCBRINDEEX    VENDABALCAORESERVA    VARCHAR2(1)                              \tDefine se a campanha deverá ser validada na venda Balcão Reserva.\t            OPERACIONAL                        NaN
PCBRINDEEX         VENDATELEMARK    VARCHAR2(1)                                     \tDefine se a campanha deverá ser validada no Telemarketing.\t            OPERACIONAL                        NaN
PCBRINDEEX       VENDACALLCENTER    VARCHAR2(1)                                       \tDefine se a campanha deverá ser validada no Call Center.\t            OPERACIONAL                        NaN
PCBRINDEEX            DTINCLUSAO           DATE                                                  \tData da inclusão do brinde no banco de dados.\t            OPERACIONAL                        NaN
PCBRINDEEX           ACUMULATIVA    VARCHAR2(1)                                                                                        Acumulativa            OPERACIONAL                        NaN
PCBRINDEEX          USAALIENACAO    VARCHAR2(1)                                                                          Usa processo de alienação            OPERACIONAL                        NaN
PCBRINDEEX             ABATERDEV    VARCHAR2(1)                                                               Valida se deve abater as devoluções.            OPERACIONAL                        NaN
PCBRINDEEX       QTMAXBRINDESCLI   NUMBER(18,6)                                                        Qtde máx. de brindes para cliente por item.            OPERACIONAL                        NaN
PCBRINDEEX      QTACUMULADAVENDA   NUMBER(18,6)                                                            Quantidade de multiplos a ser acumulada            OPERACIONAL                        NaN
PCBRINDEEX DESCONSIDERARIMPOSTOS    VARCHAR2(1)                                                                             Desconsiderar impostos            OPERACIONAL                        NaN
PCBRINDEEX         QTBRINDESDISP   NUMBER(18,6)                                                                    Quantidade de brinde disponivel            OPERACIONAL                        NaN
PCBRINDEEX           SISTEMATICA VARCHAR2(4000)                                                                  Sistematica da política de brinde            OPERACIONAL                        NaN
PCBRINDEEX       APENASVALIDATV5    VARCHAR2(1)                                                              Deffini se campanha apenas valida TV5            OPERACIONAL                        NaN
PCBRINDEEX     TIPOCONTACORRENTE    VARCHAR2(1)                                     Tipo de conta corrente movimentada: RCA, Supervisor ou Gerente            OPERACIONAL                        NaN
PCBRINDEEX            PERCFORNEC   NUMBER(10,4)                                                                Percentual custeado pelo fornecedor            OPERACIONAL                        NaN
PCBRINDEEX              NUMVERBA    NUMBER(8,0)                                                                 Nr. da verba atribuída a campanha.            OPERACIONAL                        NaN
PCBRINDEEX        PERCCUSTFORNEC   NUMBER(12,4)                                                               Percentual custeado pelo fornecedor.            OPERACIONAL                        NaN
PCBRINDEEX        VENDAECOMMERCE    VARCHAR2(1)                           Indica se a campanha estará disponível para o tipo de venda "e-Commerce"            OPERACIONAL                        NaN
PCBRINDEEX                SYNCFV    VARCHAR2(1)                                                                                                NaN            OPERACIONAL                        NaN
PCBRINDEEX            DTMXSALTER           DATE                                                                                                NaN            OPERACIONAL                        NaN
PCBRINDEEX            OBSERVACAO  VARCHAR2(100)                                                                 Observações na política de brinde.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*