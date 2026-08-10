# 📊 Tabela: PCBLOQUEIOEST

### Estrutura de Colunas e Restrições

       Tabela          Coluna Tipo/Tamanho                                                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBLOQUEIOEST       CODFILIAL  VARCHAR2(2)                                                                                      Indica o código da filial.            OPERACIONAL                        NaN
PCBLOQUEIOEST     CODENDERECO  NUMBER(8,0)                                                                                    Indica o código de endereço.            OPERACIONAL                        NaN
PCBLOQUEIOEST         CODPROD  NUMBER(8,0)                                                                                     Indica´o código do produto.            OPERACIONAL                        NaN
PCBLOQUEIOEST              QT  NUMBER(8,0)                                                                                            Indica a quantidade.            OPERACIONAL                        NaN
PCBLOQUEIOEST       CODMOTIVO  NUMBER(8,0)                                                                                      Indica o código do motivo.            OPERACIONAL                        NaN
PCBLOQUEIOEST          DTLANC         DATE                                                                                    Indica a data de lançamento.            OPERACIONAL                        NaN
PCBLOQUEIOEST     CODFUNCLANC  NUMBER(8,0)                                                                      Indica o código do funcionário lançamento.            OPERACIONAL                        NaN
PCBLOQUEIOEST           QTANT  NUMBER(8,0)                                                                                   Indica a quantidade anterior.            OPERACIONAL                        NaN
PCBLOQUEIOEST       CODROTINA  NUMBER(8,0)                                                                                      Indica o código da rotina.            OPERACIONAL                        NaN
PCBLOQUEIOEST         CODOPER  VARCHAR2(2)                                                                              Indica o tipo de opeção realizada.            OPERACIONAL                        NaN
PCBLOQUEIOEST        FUNCRESP VARCHAR2(50)                                                              Indica o código fucionario responsvel pela avaria.            OPERACIONAL                        NaN
PCBLOQUEIOEST CODENDERECOORIG  NUMBER(8,0)                                            Indica o código do endereço de onde o produto avariado foi retirado.            OPERACIONAL                        NaN
PCBLOQUEIOEST            DATA         DATE                                                                                      Indica a data do bloqueio.            OPERACIONAL                        NaN
PCBLOQUEIOEST            TIPO  VARCHAR2(1)                                                                    indica o tipo da operação (Bloq ou Desbloq).            OPERACIONAL                        NaN
PCBLOQUEIOEST        TIPOBLOQ  VARCHAR2(1)                                                                     Idica tipo do bloqueio (Comercial, Avaria).            OPERACIONAL                        NaN
PCBLOQUEIOEST     RESPONSAVEL VARCHAR2(60)                                                                   Indica o responsável pelo Bloqueio / Desbloq.            OPERACIONAL                        NaN
PCBLOQUEIOEST             OBS VARCHAR2(60)                                                                                                     Observação.            OPERACIONAL                        NaN
PCBLOQUEIOEST        SEMAFORO  NUMBER(2,0)                                                                                    Indica o status do registro.            OPERACIONAL                        NaN
PCBLOQUEIOEST DTPROCESSAMENTO         DATE                                                                                 Indica a data do processamento.            OPERACIONAL                        NaN
PCBLOQUEIOEST     NUMTRANSWMS NUMBER(10,0)                                                                              Numero de transação gerada no WMS.            OPERACIONAL                        NaN
PCBLOQUEIOEST         QTPECAS NUMBER(20,8)                                                                              Numero de transação gerada no WMS.            OPERACIONAL                        NaN
PCBLOQUEIOEST         NUMLOTE VARCHAR2(15) Número do lote lançado na avaria (PCBLOQUEIOEST.NUMLOTE) para gravar na tabela de integração (PCWMSBLOQUEIOEST)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*