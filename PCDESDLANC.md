# 📊 Tabela: PCDESDLANC

### Estrutura de Colunas e Restrições

    Tabela        Coluna  Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESDLANC        RECNUM   NUMBER(8,0)                         Indica o número do lançamento de destino            OPERACIONAL                        NaN
PCDESDLANC        DTLANC          DATE                   Indica a data do lançamento do título original            OPERACIONAL                        NaN
PCDESDLANC        DTDESD          DATE                                   Indica a data do desdobramento            OPERACIONAL                        NaN
PCDESDLANC   CODFUNCDESD   NUMBER(8,0)                      Indica o código do usuário do desdobramento            OPERACIONAL                        NaN
PCDESDLANC      CODCONTA  NUMBER(10,0)                                         Indica o código da conta            OPERACIONAL                        NaN
PCDESDLANC         VALOR  NUMBER(18,6)                              Indica o valor do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC      VALORDEV  NUMBER(18,6)                 Indica o valor de devolução do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC   DESCONTOFIN  NUMBER(18,6)       Indica o valor de desconto financeiro do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC        TXPERM  NUMBER(18,6)                      Indica o valor de juro do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC       NUMNOTA  NUMBER(10,0)                     Indica o número da nota do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC        DUPLIC   VARCHAR2(1)                  Indica a duplicata da nota do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC     CODFILIAL   VARCHAR2(2)                             Indica a filial do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC        INDICE   VARCHAR2(1)                             Indica o índice do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC   NUMTRANSENT  NUMBER(10,0)              Número da transação de entrada do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC     CODFORNEC   NUMBER(8,0)                          Código do parceiro do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC  TIPOPARCEIRO   VARCHAR2(1)                            Tipo do parceiro do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC     HISTORICO VARCHAR2(200)                                   Histórico do título desdobrado            OPERACIONAL                        NaN
PCDESDLANC    RECNUMORIG   NUMBER(8,0)    Indica o número do lançameto original antes do desdobramento.            OPERACIONAL                        NaN
PCDESDLANC RECNUMDESTINO   NUMBER(8,0)       Indica o número do lançamento gerado após o desdobramento.            OPERACIONAL                        NaN
PCDESDLANC        DTVENC          DATE  Grava data de vencimento do ultimo titulos desdobrado pela 737.            OPERACIONAL                        NaN
PCDESDLANC    DTVENCORIG          DATE Grava data de vencimento do primeiro titulo desdobrado pela 737.            OPERACIONAL                        NaN
PCDESDLANC  ROTINAINSERT  VARCHAR2(30)                       Informaç.ão da rotna que realizou o insert            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*