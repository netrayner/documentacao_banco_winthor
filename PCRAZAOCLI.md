# 📊 Tabela: PCRAZAOCLI

### Estrutura de Colunas e Restrições

    Tabela          Coluna Tipo/Tamanho                                                                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRAZAOCLI          NUMSEQ NUMBER(12,0)                                                                                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRAZAOCLI       CODFILIAL  VARCHAR2(2)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI          CODCLI  NUMBER(6,0)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI            DATA         DATE                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI       HISTORICO VARCHAR2(60)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI         NUMNOTA NUMBER(10,0)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI   NUMTRANSVENDA NUMBER(12,0)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI           PREST  VARCHAR2(2)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI          CODCOB  VARCHAR2(4)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI           VALOR NUMBER(18,2)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI        VLDEBITO NUMBER(18,2)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI       VLCREDITO NUMBER(18,2)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI            TIPO  VARCHAR2(3)                                                                                                                                                          NaN            OPERACIONAL                        NaN
PCRAZAOCLI        TIPOLANC  VARCHAR2(1)                                                                                              Tipo de lançamento: Nota Fiscal, Título de Crédito ou Devolução            OPERACIONAL                        NaN
PCRAZAOCLI NUMTRANSVENDANF NUMBER(10,0)                                                                                                                  Número de Transação de Venda da Nota Fiscal            OPERACIONAL                        NaN
PCRAZAOCLI        VLPISDIF NUMBER(18,2)                                                          Valor total do PIS referente nota de saída para órgão público. (PROCESSO DIFERIMENTO DE PIS/COFINS)            OPERACIONAL                        NaN
PCRAZAOCLI     VLCOFINSDIF NUMBER(18,2)                                                       Valor total da COFINS referente nota de saída para órgão público. (PROCESSO DIFERIMENTO DE PIS/COFINS)            OPERACIONAL                        NaN
PCRAZAOCLI    VLCREDPISDIF NUMBER(18,2)     Valor total do PIS referente nota de entrada vinculada a nota de saída para órgão público pelo PEPS (Rotina 1074). (PROCESSO DIFERIMENTO DE PIS/COFINS)             OPERACIONAL                        NaN
PCRAZAOCLI VLCREDCOFINSDIF NUMBER(18,2)  Valor total da COFINS referente nota de entrada vinculada a nota de saída para órgão público pelo PEPS (Rotina 1074). (PROCESSO DIFERIMENTO DE PIS/COFINS)             OPERACIONAL                        NaN
PCRAZAOCLI   FORMAAPURACAO  VARCHAR2(1)                                                                              Forma de apuração dos lançamentos (P - Pagamento / B - Baixa / C - Compensação)            OPERACIONAL                        NaN
PCRAZAOCLI     DATAGERACAO         DATE                                                                                                           Data em que os lançamentos foram gerados na tabela            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*