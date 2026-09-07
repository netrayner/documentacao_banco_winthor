# 📊 Tabela: PCMOVAVARIA

### Estrutura de Colunas e Restrições

     Tabela          Coluna Tipo/Tamanho                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVAVARIA            DATA         DATE                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA         CODPROD  NUMBER(6,0)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA          CODCLI  NUMBER(9,0)                                                                   Descricao coluna CODCLI            OPERACIONAL                        NaN
PCMOVAVARIA              QT NUMBER(20,6)                                                                       Descricao coluna QT            OPERACIONAL                        NaN
PCMOVAVARIA         CODOPER  VARCHAR2(2)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA  NUMTRANSCPAGAR  NUMBER(8,0)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA     CODFUNCLANC  NUMBER(8,0)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA         NUMNOTA NUMBER(10,0)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA     NUMTRANSENT NUMBER(10,0)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA   NUMTRANSVENDA NUMBER(10,0)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA             OBS VARCHAR2(60)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA        DTMOVLOG         DATE                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA       CODFILIAL  VARCHAR2(2)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA         NUMLOTE VARCHAR2(15)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA   CODROTINALANC  NUMBER(6,0)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA        CODDEVOL  NUMBER(4,0)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVAVARIA       CODROTINA  NUMBER(6,0)                                         Indica o código da rotina que incluiu o registro.            OPERACIONAL                        NaN
PCMOVAVARIA     NUMTRANSWMS NUMBER(10,0)                                                        Numero de transação gerada no WMS.            OPERACIONAL                        NaN
PCMOVAVARIA DTEXPORTACAOWMS         DATE                                                                 Data da exportação do WMS            OPERACIONAL                        NaN
PCMOVAVARIA DTIMPORTACAOWMS         DATE                                                                 Data de importação do WMS            OPERACIONAL                        NaN
PCMOVAVARIA     CODDEPOSITO NUMBER(10,0)                                                                        Código do Depósito            OPERACIONAL                        NaN
PCMOVAVARIA   IDENTIFICADOR NUMBER(10,0) Número da transação de entrada, saída ou bônus usado para movimentar o estoque bloqueado.            OPERACIONAL                        NaN
PCMOVAVARIA       DTESTORNO         DATE                       Data do estorno da operação de bloqueio do estoque na tabela PCEST.            OPERACIONAL                        NaN
PCMOVAVARIA  CODFUNCESTORNO  NUMBER(8,0)                                            Código do funcionário que estornou o bloqueio.            OPERACIONAL                        NaN
PCMOVAVARIA   ROTINAESTORNO VARCHAR2(48)                                         Código da rotina que fez o estorno do lançamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*