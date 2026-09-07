# 📊 Tabela: PCFILAMENSAGEMHISTORICO

### Estrutura de Colunas e Restrições

                 Tabela              Coluna  Tipo/Tamanho                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILAMENSAGEMHISTORICO          IDMENSAGEM  NUMBER(10,0)                                                                      Idmensagem            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO       DATATRANSACAO          DATE                                                                   Datatransacao            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO           CODFILIAL   VARCHAR2(2)                                                              Codfilial da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO            NUMCAIXA   VARCHAR2(4)                                                               Numcaixa da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO             NUMNOTA  NUMBER(10,0)                                                                Numnota da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO               SERIE   NUMBER(4,0)                                                                 Serie da venda             OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO          CHAVESEFAZ  VARCHAR2(44)                                                                      Chavesefaz            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO           PROTOCOLO  VARCHAR2(20)                                                                      Protocolo             OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO        CONTINGENCIA   VARCHAR2(1)                                                           Contingencia da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO           IDEXTERNO VARCHAR2(100)                                                                      Idexterno             OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO              STATUS   NUMBER(1,0)                                                                 Status da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO     QTPROCESSAMENTO   NUMBER(1,0)                                                                Qtprocessamento             OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO       TIPODOCUMENTO   VARCHAR2(3)                                                          Tipodocumento de venda            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO        TIPOOPERACAO   VARCHAR2(5)                                                                    Tipooperacao            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO            MENSAGEM          CLOB                                                               Mensagem de venda            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO        TIPOMENSAGEM   NUMBER(1,0)                                                                   Tipomensagem             OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO          CODIGOERRO   NUMBER(4,0)                                                                     Codigoerro             OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO DATAULTIMAALTERACAO          DATE                                                             Dataultimaalteracao            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO           PDVORIGEM  VARCHAR2(20)                                                              PDVORIGEM da venda            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO     DATAFATURAMENTO          DATE                                                                 Datafaturamento            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO           IDWINTHOR VARCHAR2(100) REPRESENTA O NUMTRASNVENDA CASOS PARA VENDA OU NUMVALE PARA CASO DE SANG OU SUP            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO            SEQDOCTO  NUMBER(10,0)                                        CAMPO REPRESENTADO A INTEGRACAO CONSINCO            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO   VERSAOFATURAMENTO  VARCHAR2(20)                                              Versão do servidor de faturamento             OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO            TERMINAL VARCHAR2(100)                                                    Terminal que inseriu a linha            OPERACIONAL                        NaN
PCFILAMENSAGEMHISTORICO       DATADOCUMENTO          DATE                                                 Data de referencia do documento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*