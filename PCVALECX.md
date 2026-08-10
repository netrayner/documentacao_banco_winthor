# 📊 Tabela: PCVALECX

### Estrutura de Colunas e Restrições

  Tabela                Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVALECX               NUMVALE  NUMBER(10,0)                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVALECX                DTLANC          DATE                                NaN            OPERACIONAL                        NaN
PCVALECX                  TIPO   VARCHAR2(1)                                NaN            OPERACIONAL                        NaN
PCVALECX             HISTORICO VARCHAR2(200)                                NaN            OPERACIONAL                        NaN
PCVALECX               CODFUNC   NUMBER(8,0)                                NaN            OPERACIONAL                        NaN
PCVALECX                 NUMCX   NUMBER(8,0)                                NaN            OPERACIONAL                        NaN
PCVALECX                CODCOB   VARCHAR2(4)                                NaN            OPERACIONAL                        NaN
PCVALECX                 VALOR  NUMBER(12,2)                                NaN            OPERACIONAL                        NaN
PCVALECX               DTFECHA          DATE                                NaN            OPERACIONAL                        NaN
PCVALECX          CODFUNCFECHA   NUMBER(8,0)                                NaN            OPERACIONAL                        NaN
PCVALECX              CODBANCO   NUMBER(4,0)                                NaN            OPERACIONAL                        NaN
PCVALECX         NUMSERIEEQUIP  VARCHAR2(30)                                NaN            OPERACIONAL                        NaN
PCVALECX            NUMVALEECF  NUMBER(10,0)                                NaN            OPERACIONAL                        NaN
PCVALECX              HORALANC   NUMBER(2,0)                                NaN            OPERACIONAL                        NaN
PCVALECX            MINUTOLANC   NUMBER(2,0)                                NaN            OPERACIONAL                        NaN
PCVALECX      EXPORTADOSERVINT   VARCHAR2(1)                                NaN            OPERACIONAL                        NaN
PCVALECX   DTEXPORTACAOSERVINT          DATE                                NaN            OPERACIONAL                        NaN
PCVALECX    IMPORTADOSERVPRINC   VARCHAR2(1)                                NaN            OPERACIONAL                        NaN
PCVALECX  NUMVALEINTERMEDIARIO  NUMBER(10,0)                                NaN            OPERACIONAL                        NaN
PCVALECX DTIMPORTACAOSERVPRINC          DATE                                NaN            OPERACIONAL                        NaN
PCVALECX             CODCRECLI   NUMBER(6,0)       Indica o crédito de cliente.            OPERACIONAL                        NaN
PCVALECX           TIPOSANGRIA   VARCHAR2(1) Indica o tipo de sangria efetuada.            OPERACIONAL                        NaN
PCVALECX              NUMTRANS  NUMBER(10,0)               Número de transação.            OPERACIONAL                        NaN
PCVALECX    NUMFECHAMENTOMOVCX  NUMBER(10,0)               Numero de fechamento            OPERACIONAL                        NaN
PCVALECX         DTMOVIMENTOCX          DATE                 Data de fechamento            OPERACIONAL                        NaN
PCVALECX         CODUSURAUTORI  NUMBER(13,0) Código usuário liberou SANG ou SUP            OPERACIONAL                        NaN
PCVALECX             NUMMALOTE  VARCHAR2(40)                   Número do malote            OPERACIONAL                        NaN
PCVALECX              NUMLACRE  VARCHAR2(40)                    Número do lacre            OPERACIONAL                        NaN
PCVALECX       DATACONFERENCIA          DATE                Data de conferência            OPERACIONAL                        NaN
PCVALECX        VALORCONFERIDO  NUMBER(12,2)                    Valor conferido            OPERACIONAL                        NaN
PCVALECX       RECNUM_PCCORREN   NUMBER(8,0)          Recnum da tabela PCCORREN            OPERACIONAL                        NaN
PCVALECX    NUMTRANSVENDAPREST  NUMBER(10,0)           NUMTRANSVENDA DO PCPREST            OPERACIONAL                        NaN
PCVALECX                 PREST   VARCHAR2(2)                   PREST DA PCPREST            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*