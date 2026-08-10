# 📊 Tabela: PCLOGRCA

### Estrutura de Colunas e Restrições

  Tabela                         Coluna  Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGRCA                           DATA          DATE                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                     DTBLOQUEIO          DATE                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                    DTBLOQCOMIS          DATE                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                        CODFUNC   NUMBER(8,0)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                        CODUSUR   NUMBER(8,0)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                         ROTINA   NUMBER(6,0)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                     VLCORRENTE  NUMBER(10,2)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                      VLLIMCRED  NUMBER(10,2)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                  VLCORRENTEANT  NUMBER(10,2)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                   VLLIMCREDANT  NUMBER(10,2)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                      HISTORICO  VARCHAR2(60)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                         NUMPED  NUMBER(10,0)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                        POSICAO   VARCHAR2(1)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                  NUMTRANSVENDA  NUMBER(10,0)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                    NUMTRANSENT  NUMBER(10,0)                                            Número Transentrada            OPERACIONAL                        NaN
PCLOGRCA                        CODPROD   NUMBER(6,0)                                      Indica o produto vendido.            OPERACIONAL                        NaN
PCLOGRCA                         NUMSEQ  NUMBER(20,0)                          Número de seqüência do item na venda.            OPERACIONAL                        NaN
PCLOGRCA                     HISTORICO2 VARCHAR2(300)     Indica o historico do motivo da alteração do saldo do RCA.            OPERACIONAL                        NaN
PCLOGRCA                    VLDIFERENCA  NUMBER(14,6)                                    Percentual restante do RCA.            OPERACIONAL                        NaN
PCLOGRCA                      VLRESERVA  NUMBER(18,6)                                              Valor da reserva.            OPERACIONAL                        NaN
PCLOGRCA               PERCSALDORESERVA   NUMBER(5,2)                                      Percentual saldo reserva.            OPERACIONAL                        NaN
PCLOGRCA                      CODFILIAL   VARCHAR2(2)                                               Código da filial            OPERACIONAL                        NaN
PCLOGRCA                HISTORICOTRANSF VARCHAR2(200)          Histórico da transferência, RCA que esta movimentando            OPERACIONAL                        NaN
PCLOGRCA                      SEQLOGRCA  NUMBER(18,0)       Campo utlizado para gravar a ordem da inserção na tabela            OPERACIONAL                        NaN
PCLOGRCA                      CODMXSMOV VARCHAR2(100)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                     NOMEMXSMOV VARCHAR2(500)                                                            NaN            OPERACIONAL                        NaN
PCLOGRCA                         PVENDA  NUMBER(18,6)                                                 Preço de Venda            OPERACIONAL                        NaN
PCLOGRCA                             ST  NUMBER(18,6)                               Valor da Substituição Tributária            OPERACIONAL                        NaN
PCLOGRCA                       PBASERCA  NUMBER(18,6)                                           Preço da Base do RCA            OPERACIONAL                        NaN
PCLOGRCA                     STPBASERCA  NUMBER(18,6)                                     ST do Preço da Base do RCA            OPERACIONAL                        NaN
PCLOGRCA                        PTABELA  NUMBER(18,6)                                                Preço de Tabela            OPERACIONAL                        NaN
PCLOGRCA                      STPTABELA  NUMBER(18,6)                                          St do Preço de Tabela            OPERACIONAL                        NaN
PCLOGRCA                        BONIFIC   VARCHAR2(1)                                                    Bonificação            OPERACIONAL                        NaN
PCLOGRCA                             QT  NUMBER(20,6)                                                     Quantidade            OPERACIONAL                        NaN
PCLOGRCA             USADEBCREDRCABRIND   VARCHAR2(1)                                  Usa Débito Crédito RCA Brinde            OPERACIONAL                        NaN
PCLOGRCA      MOVIMENTACONTACORRENTERCA   VARCHAR2(1)                                Movimenta Conta Corrente do RCA            OPERACIONAL                        NaN
PCLOGRCA        AUTORIZEDICAOITEMPEDMED   VARCHAR2(1)                              Autoriza Ediçaõ do Item do Pedido            OPERACIONAL                        NaN
PCLOGRCA  MOTIVOAUTORIZEDICAOITEMPEDMED VARCHAR2(200)                       Motivo Autoriza Edição do Item do Pedido            OPERACIONAL                        NaN
PCLOGRCA CODFUNCAUTORIZEDICAOITEMPEDMED   NUMBER(8,0) Código do Funcionário que Autorizou a Edição do Item do Pedido            OPERACIONAL                        NaN
PCLOGRCA                 CODPROMOCAOMED   NUMBER(9,0)                                             Código da Promoção            OPERACIONAL                        NaN
PCLOGRCA                          PREST   VARCHAR2(2)                                                     Prestação             OPERACIONAL                        NaN
PCLOGRCA          PERCRATEIOLIQUIDEZMED  NUMBER(18,6)                                  Percentual de Rateio Liquidez            OPERACIONAL                        NaN
PCLOGRCA    PERCRATEIOCREDRCASUPERVISOR  NUMBER(12,2)                 Percentual de Rateio do Crédito RCA/Supervisor            OPERACIONAL                        NaN
PCLOGRCA                 NUMREGISTROMED  NUMBER(20,0)                                             Número de Registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*