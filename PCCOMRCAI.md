# 📊 Tabela: PCCOMRCAI

### Estrutura de Colunas e Restrições

   Tabela         Coluna  Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMRCAI         CODCLI   NUMBER(6,0)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI        CODUSUR   NUMBER(4,0)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI  CODSUPERVISOR   NUMBER(8,0)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI         CODCOB   VARCHAR2(4)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI         DUPLIC  NUMBER(10,0)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI         DTVENC          DATE                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI          DTPAG          DATE                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI          VALOR  NUMBER(12,2)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI          VPAGO  NUMBER(12,2)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI     VLCOMISSAO  NUMBER(12,2)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI        VLVENDA  NUMBER(12,2)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI VLBASECOMISSAO  NUMBER(12,2)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI    TIPOCALCULO   VARCHAR2(1)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI    CODCOMISSAO  NUMBER(10,0)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI     DATAINICIO          DATE                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI        DATAFIM          DATE                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI      CODFILIAL   VARCHAR2(2)                                     NaN            OPERACIONAL                        NaN
PCCOMRCAI          PREST   VARCHAR2(2)                    Prestação do título.            OPERACIONAL                        NaN
PCCOMRCAI      DTEMISSAO          DATE              Data de emissão do título.            OPERACIONAL                        NaN
PCCOMRCAI    CODEMITENTE   NUMBER(8,0) Codigo do emitente do pedido de compra.            OPERACIONAL                        NaN
PCCOMRCAI         PERCOM   NUMBER(7,4)          Percentual de comissão do item            OPERACIONAL                        NaN
PCCOMRCAI         NUMSEQ  NUMBER(18,0)                    Vínculo com PCCOMRCA            OPERACIONAL                        NaN
PCCOMRCAI         ORIGEM VARCHAR2(100)                    Origem da Informação            OPERACIONAL                        NaN
PCCOMRCAI    NUMTRANSENT  NUMBER(10,0)                    Transação de Entrada            OPERACIONAL                        NaN
PCCOMRCAI  NUMTRANSVENDA  NUMBER(10,0)                      Transação de Saída            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*