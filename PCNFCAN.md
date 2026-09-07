# 📊 Tabela: PCNFCAN

### Estrutura de Colunas e Restrições

 Tabela                Coluna  Tipo/Tamanho                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFCAN           NUMTRANSENT  NUMBER(10,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN         NUMTRANSVENDA  NUMBER(10,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN          CODFUNCEMITE   NUMBER(8,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN           DATAEMISSAO          DATE                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN           CODFUNCCANC   NUMBER(8,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN              DATACANC          DATE                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN               VLTOTAL  NUMBER(18,3)                                                                                        Indica a condição de venda.             OPERACIONAL                        NaN
PCNFCAN                CODCLI   NUMBER(6,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN             CODFORNEC   NUMBER(6,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN                MOTIVO  VARCHAR2(60)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN                NUMPED  NUMBER(10,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN                NUMCAR   NUMBER(8,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN          NUMPEDCOMPRA  NUMBER(10,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN             CODROTINA   NUMBER(6,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN             DESCRICAO VARCHAR2(120)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN               CODUSUR   NUMBER(4,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN             NUMPEDRCA  NUMBER(10,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN              CODPLPAG   NUMBER(4,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN                CODCOB   VARCHAR2(4)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN             CODFILIAL   VARCHAR2(2)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN             ORIGEMPED   VARCHAR2(1)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN             CONDVENDA   NUMBER(5,0)                                                                                        Indica a condição de venda.             OPERACIONAL                        NaN
PCNFCAN               TOTPESO  NUMBER(18,6)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN             TOTVOLUME  NUMBER(18,6)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN         NUMORCAFILIAL  NUMBER(10,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN               NUMORCA  NUMBER(10,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN      EXPORTADOSERVINT   VARCHAR2(1)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN   DTEXPORTACAOSERVINT          DATE                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN      NUMTRANSVENDAECF  NUMBER(10,0)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN    IMPORTADOSERVPRINC   VARCHAR2(1)                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN DTIMPORTACAOSERVPRINC          DATE                                                                                                                 NaN            OPERACIONAL                        NaN
PCNFCAN              HORACANC          DATE                                                                                     Indica a hora do cancelamento.             OPERACIONAL                        NaN
PCNFCAN             NUMPEDCLI  VARCHAR2(15)                                                                               Indica o número pedido de importação.            OPERACIONAL                        NaN
PCNFCAN         INTEGRACAOWMS   VARCHAR2(1)                                                                    Identificação de cancelamento de pedido de venda            OPERACIONAL                        NaN
PCNFCAN       DTEXPORTACAOWMS          DATE                                                                                          Data  e hora de exportação            OPERACIONAL                        NaN
PCNFCAN           NUMPEDAGRUP  NUMBER(10,0)                                                                                           Número do Pedido Agrupado            OPERACIONAL                        NaN
PCNFCAN            DTDENEGADA          DATE                                                                                                       Data denegada            OPERACIONAL                        NaN
PCNFCAN          HORADENEGADA          DATE                                                                                                Data e Hora denegada            OPERACIONAL                        NaN
PCNFCAN      POSICAOANTCANCEL   VARCHAR2(2)                                                                             Posição do pedido antes do cancelamento            OPERACIONAL                        NaN
PCNFCAN         CODSUPERVISOR   NUMBER(4,0)                                                                                       Indica o código do SUPERVISOR            OPERACIONAL                        NaN
PCNFCAN     DTABERTURAPEDPALM          DATE                                                                         Indica a Data de Abertura do Pedido no Palm            OPERACIONAL                        NaN
PCNFCAN          EMAILENVIADO   VARCHAR2(1)                                                                                                       EMAIL ENVIADO            OPERACIONAL                        NaN
PCNFCAN                TIPOFV   VARCHAR2(2)                                                                                             Tipo de Força de Vendas            OPERACIONAL                        NaN
PCNFCAN        CODPROMOCAOMED   NUMBER(9,0)                                                                                      Código da Promoção Medicamento            OPERACIONAL                        NaN
PCNFCAN           SERVICO_WTA  VARCHAR2(48)                                                       Indica a versão do serviço do WTA que inseriu aquele registro            OPERACIONAL                        NaN
PCNFCAN      ORIGEMINTEGRACAO  VARCHAR2(50) Campo destinado a informar a origem da integração, em caso de pedidos oriundos de integrações feitas com o WinThor.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*