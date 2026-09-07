# 📊 Tabela: PCAUTORI

### Estrutura de Colunas e Restrições

  Tabela                Coluna Tipo/Tamanho                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTORI         NRAUTORIZACAO NUMBER(10,0)                                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTORI       DATAAUTORIZACAO         DATE                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI               CODUSUR  NUMBER(4,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI                CODCLI  NUMBER(6,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI               CODPROD NUMBER(10,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI              CODPLPAG  NUMBER(4,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI         PERCDESCAUTOR NUMBER(18,6)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI       DATA_UTILIZACAO         DATE                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI         CODFUNCUTILIZ  NUMBER(8,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI          STATUSUTILIZ  VARCHAR2(1)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI           PVENDAATUAL NUMBER(18,6)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI                NUMPED NUMBER(10,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI              PVENDIDO NUMBER(12,3)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI            EXCEDECOTA  VARCHAR2(1)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI       CODFUNCCADASTRO  NUMBER(8,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI             NUMREGIAO  NUMBER(4,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI             CODFILIAL  VARCHAR2(2)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI            GERADEBRCA  VARCHAR2(1)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI       INICIOINTERVALO NUMBER(18,6)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI          FIMINTERVALO NUMBER(18,6)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI              NUMCAIXA  NUMBER(4,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI              NUMCUPOM NUMBER(10,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI            SERIEEQUIP VARCHAR2(30)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI        BASECREDDEBRCA  VARCHAR2(1)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI                   OBS VARCHAR2(80)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI            QTVENDAECF NUMBER(20,6)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI          AFETAPERDESC  VARCHAR2(1)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI           CODAUXILIAR NUMBER(16,0)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI   DTEXPORTACAOSERVINT         DATE                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI      EXPORTADOSERVINT  VARCHAR2(1)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI DTIMPORTACAOSERVPRINC         DATE                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI    IMPORTADOSERVPRINC  VARCHAR2(1)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI                PERCOM  NUMBER(6,2)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI        APENASPLPAGMAX  VARCHAR2(1)                 Definir se esta autorização será valida para outros planos.            OPERACIONAL                        NaN
PCAUTORI             CODFUNCCX  NUMBER(8,0)                                    Indica o código do funcionário do caixa.            OPERACIONAL                        NaN
PCAUTORI             NUMPEDECF NUMBER(10,0)                                    Indica o código do funcionário do caixa.            OPERACIONAL                        NaN
PCAUTORI      NRAUTORIZACAOECF NUMBER(10,0)                                    Indica o número de autorização do caixa.            OPERACIONAL                        NaN
PCAUTORI              ENVIARFV  VARCHAR2(1)                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI     TIPOCONTACORRENTE  VARCHAR2(1)              Tipo de conta corrente movimentada: RCA, Supervisor ou Gerente            OPERACIONAL                        NaN
PCAUTORI              NUMVERBA  NUMBER(8,0)                                          Nr. da verba atribuída a campanha.            OPERACIONAL                        NaN
PCAUTORI        PERCCUSTFORNEC NUMBER(12,4)                                        Percentual custeado pelo fornecedor.            OPERACIONAL                        NaN
PCAUTORI            DTMXSALTER         DATE                                                                         NaN            OPERACIONAL                        NaN
PCAUTORI     NUMPEDSOLICITANTE NUMBER(10,0)            Numero do pedido que solicitou aprovação automática de desconto.            OPERACIONAL                        NaN
PCAUTORI   PVENDIDOSOLICITANTE NUMBER(12,3)                                   Preço de venda solicitado para aprovação.            OPERACIONAL                        NaN
PCAUTORI         NUMSEQITEMPED NUMBER(20,0)                                       Numero de sequencia do item do pedido            OPERACIONAL                        NaN
PCAUTORI        QTDSOLICITANTE NUMBER(18,6) Quantidade vendida no momento da criação do pedido de autorização de venda.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*