# 📊 Tabela: PCFILAMENSAGEMERRO

### Estrutura de Colunas e Restrições

            Tabela              Coluna  Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILAMENSAGEMERRO          IDMENSAGEM  NUMBER(10,0)                                                          Idmensagem da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO       DATATRANSACAO          DATE                                                       Datatransacao da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO           CODFILIAL   VARCHAR2(2)                                                           Codfilial da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO            NUMCAIXA   NUMBER(4,0)                                                            Numcaixa da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO             NUMNOTA  NUMBER(10,0)                                                              Número da nota             OPERACIONAL                        NaN
PCFILAMENSAGEMERRO               SERIE   NUMBER(4,0)                                                                Serie da nota            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO          CHAVESEFAZ  VARCHAR2(44)                                                           Chavesefaz da nota            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO           PROTOCOLO  VARCHAR2(20)                                                           Protocolo da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO        CONTINGENCIA   VARCHAR2(1)                                                        Contingencia da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO           IDEXTERNO VARCHAR2(100)                                        Idexterno do pdv que realizou a venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO              STATUS   NUMBER(1,0)                                 Status relacionado ao processamento da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO     QTPROCESSAMENTO   NUMBER(1,0)                                                     Qtprocessamento da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO       TIPODOCUMENTO   VARCHAR2(3)                    Tipodocumento para indentificar o tipo de operação no pdv            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO        TIPOOPERACAO   VARCHAR2(5)                                                        Tipooperacao da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO            MENSAGEM          CLOB                                                      Mensagem dados da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO        TIPOMENSAGEM   NUMBER(1,0) Tipomensagem relacionado qual tipo de dado que está dentro do campo mensagem            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO          CODIGOERRO   NUMBER(4,0)                                                                  Codigoerro             OPERACIONAL                        NaN
PCFILAMENSAGEMERRO DATAULTIMAALTERACAO          DATE                                                          Dataultimaalteracao            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO           PDVORIGEM  VARCHAR2(20)                                                                   Pdvorigem             OPERACIONAL                        NaN
PCFILAMENSAGEMERRO        REPROCESSADO   VARCHAR2(3)                                                                Reprocessado             OPERACIONAL                        NaN
PCFILAMENSAGEMERRO      QTREPROCESSADO   NUMBER(1,0)                                                               Qtreprocessado            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO            SEQDOCTO  NUMBER(10,0)                                     CAMPO REPRESENTADO A INTEGRACAO CONSINCO            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO   VERSAOFATURAMENTO  VARCHAR2(20)                                            Versão do servidor de faturamento            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO            TERMINAL VARCHAR2(100)                                                 Terminal que inseriu a linha            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO       DATADOCUMENTO          DATE                                              Data de referencia do documento            OPERACIONAL                        NaN
PCFILAMENSAGEMERRO             DETALHE          CLOB                                                  Detalhe relacionado ao erro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*