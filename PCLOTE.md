# 📊 Tabela: PCLOTE

### Estrutura de Colunas e Restrições

Tabela             Coluna  Tipo/Tamanho                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOTE            CODPROD   NUMBER(6,0)                                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTE                 QT  NUMBER(22,8)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE           QTRESERV  NUMBER(22,8)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        DTULTMOVSAI          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        DTULTMOVENT          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE         DTVALIDADE          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE          CODFUNCRM   NUMBER(8,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE     DATAFABRICACAO          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE            NUMLOTE  VARCHAR2(15)                                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTE        QTBLOQUEADA  NUMBER(20,6)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE         NUMLOTEFAB  VARCHAR2(20)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE      NUMLOTEFORNEC  VARCHAR2(20)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE         FABRICANTE  VARCHAR2(60)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE               OBS1  VARCHAR2(80)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE               OBS2  VARCHAR2(80)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE          EMBALAGEM   VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE            UMIDADE   VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE           IMPUREZA   VARCHAR2(1)                                                                                          Pesquisa de Impurezas            OPERACIONAL                        NaN
PCLOTE              LAUDO   VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        NUMTRANSENT  NUMBER(10,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE      IDENTIFICACAO   VARCHAR2(1)                                                                                       Identificação da Análise            OPERACIONAL                        NaN
PCLOTE           LAUDOFAB   VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE            ANALISE   VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE     NUMCERTIFICADO  VARCHAR2(15)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        DTLIBERACAO          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE         OBSANALISE VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE          CODFUNCCQ   NUMBER(8,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE  NUMTRANSENTDEVCLI  NUMBER(10,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE  OBSBLOQUEIOMANUAL VARCHAR2(150)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE          CODFILIAL   VARCHAR2(2)                                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTE        OBSBLOQUEIO VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        DTBLOQUEIO1          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        DTBLOQUEIO2          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE           PERCTEOR  NUMBER(10,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE       DTINSPVISUAL          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE          QTINDENIZ  NUMBER(20,6)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE          DTPREVLIB          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        FATORPUREZA   NUMBER(5,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE       DTAREANALISE          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE           CODBARRA   VARCHAR2(9)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE         NUMNOTAENT  NUMBER(10,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE  MOTIVOBLOQESTOQUE  VARCHAR2(80)                                                               Indica o motivo do bloqueio do estoque por lote.            OPERACIONAL                        NaN
PCLOTE         DTEXCLUSAO          DATE                                                                             Indica a data de exclusão do lote.            OPERACIONAL                        NaN
PCLOTE    CODFUNCEXCLUSAO   NUMBER(6,0)                                                                      Código do funcionário que excluiu o lote.            OPERACIONAL                        NaN
PCLOTE        PRECOCOMPRA  NUMBER(18,6)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE      NUMNEGOCIACAO  NUMBER(12,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        TXCONVERSAO  NUMBER(18,6)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE    DATACONCILIACAO          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE CODFUNCCONCILIACAO   NUMBER(6,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE    PAGTOANTECIPADO   VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE    NUMTRANSENTORIG  NUMBER(10,0) Número da transação de entrada original, que será alimentado através da rotina de manutenção de lotes (1183).             OPERACIONAL                        NaN
PCLOTE         VLCALORICO VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE           PROTEINA VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE            LIPIDEO VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE     UMIDADEANALISE VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE              COL95 VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE          SALMONELA VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE   BOLORESLEVEDURAS VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        ESTFAUREAUS VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE             MOFADO VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE         TOTDEFEITO VARCHAR2(100)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE      PESQPATOGENOS VARCHAR2(100)                                                                                          Pesquisa de Patógenos            OPERACIONAL                        NaN
PCLOTE        ANALISEDESC VARCHAR2(100)                                                                                           Descontos de Análise            OPERACIONAL                        NaN
PCLOTE          VOLPESMED VARCHAR2(100)                                                                                         Volume / Peso e Medida            OPERACIONAL                        NaN
PCLOTE                 PH VARCHAR2(100)                                                                                                 Pesquisa de PH            OPERACIONAL                        NaN
PCLOTE          DENSIDADE VARCHAR2(100)                                                                                          Pesquisa de Densidade            OPERACIONAL                        NaN
PCLOTE         DOSEAMENTO VARCHAR2(100)                                                                                         Pesquisa de Doseamento            OPERACIONAL                        NaN
PCLOTE     CONTMICROBIANA VARCHAR2(100)                                                                                        Contaminação Microbiana            OPERACIONAL                        NaN
PCLOTE   AN_IDENTIFICACAO VARCHAR2(100)                                                                              Pesquisa de Análise Identificação            OPERACIONAL                        NaN
PCLOTE        AN_IMPUREZA VARCHAR2(100)                                                                                 Pesquisa Análises de Impurezas            OPERACIONAL                        NaN
PCLOTE       FRIABILIDADE VARCHAR2(100)                                                                                       Pesquisa de Friabilidade            OPERACIONAL                        NaN
PCLOTE      DESINTEGRACAO VARCHAR2(100)                                                                                      Pesquisa de Desintegração            OPERACIONAL                        NaN
PCLOTE         DISSOLUCAO VARCHAR2(100)                                                                                         Pesquisa de Dissolução            OPERACIONAL                        NaN
PCLOTE       UNIFORMIDADE VARCHAR2(100)                                                                                       Pesquisa de Uniformidade            OPERACIONAL                        NaN
PCLOTE     PROXNUMSEQLOTE   NUMBER(4,0)                                                                 Indica o próximo número da sequencia de lotes.            OPERACIONAL                        NaN
PCLOTE         NUMREVISAO   NUMBER(6,4)                                                                                    Indica o número da revisão.            OPERACIONAL                        NaN
PCLOTE            DTLAUDO          DATE                                                                     Indica a data do laudo de análise do lote.            OPERACIONAL                        NaN
PCLOTE        QTINDUSTRIA  NUMBER(20,6)                                                                            Estoque físico da industria no lote            OPERACIONAL                        NaN
PCLOTE             CAGREG  VARCHAR2(20)                                                                                    Chave para rastreio de lote            OPERACIONAL                        NaN
PCLOTE       CODAGREGACAO  VARCHAR2(20)                                                                Responsavel por armazenar o código de agregação            OPERACIONAL                        NaN
PCLOTE      IDENTIFICADOR  NUMBER(16,0)                                                           NUMERO DO PEDIDO/ MOVIMENTACAO QUE MOVIMENTOU O LOTE            OPERACIONAL                        NaN
PCLOTE              QTEST  NUMBER(22,8)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE          QTEST_AUX  NUMBER(22,8)                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE        QTCROSSDOCK  NUMBER(22,8)                                                                                  Saldo Estoque em Crossdocking            OPERACIONAL                        NaN
PCLOTE    QTTEMPINDUSTRIA  NUMBER(22,8)                                                                           USO EXCLUSIVO DO INDUSTRIA! NÃO USAR            OPERACIONAL                        NaN
PCLOTE         DTMXSALTER          DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCLOTE          DTALTERC5  TIMESTAMP(6)                                                                                  Data de alteração do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*