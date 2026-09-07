# 📊 Tabela: PCPEDICANCECF

### Estrutura de Colunas e Restrições

       Tabela                    Coluna  Tipo/Tamanho                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDICANCECF                 EXPORTADO   VARCHAR2(1)                                                       Flag se a exportação ocorreu.            OPERACIONAL                        NaN
PCPEDICANCECF                 NUMPEDECF  NUMBER(10,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                 CODFUNCCX   NUMBER(8,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                  NUMCAIXA   NUMBER(4,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF             NUMSERIEEQUIP  VARCHAR2(30)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                   CODPROD   NUMBER(6,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                    NUMSEQ  NUMBER(20,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF               DTCANCELECF          DATE                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF          CODFUNCCANCELECF   NUMBER(8,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                      DATA          DATE                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                    CODCLI   NUMBER(6,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                   CODUSUR   NUMBER(4,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                        QT  NUMBER(20,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                    PVENDA  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                   PTABELA  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                        ST  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                    PERCOM   NUMBER(8,4)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                   PERDESC  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                VLCUSTOFIN  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF               VLCUSTOREAL  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                VLCUSTOREP  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF               VLCUSTOCONT  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                   QTFALTA   NUMBER(8,2)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF               CODAUXILIAR  NUMBER(16,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                     CODST   NUMBER(4,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                 PORIGINAL  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF        PERCBASEREDSTFONTE   NUMBER(8,4)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                     VLIPI  NUMBER(18,6)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                   PERCIPI  NUMBER(12,4)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF             PERCBASEREDST   NUMBER(8,4)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF               PERFRETECMV   NUMBER(8,4)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                    NUMCAR   NUMBER(8,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                    NUMPED  NUMBER(10,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                 IMPORTADO   VARCHAR2(1)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF            POSICAORETORNO   VARCHAR2(1)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                  DTCANCEL          DATE                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF             CODFUNCCANCEL   NUMBER(8,0)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF               PERCBASERED   NUMBER(8,4)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                   PERCICM   NUMBER(8,4)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                 CODFILIAL   VARCHAR2(2)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF     DTIMPORTACAOSERVPRINC          DATE                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF        IMPORTADOSERVPRINC   VARCHAR2(1)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF       DTEXPORTACAOSERVINT          DATE                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF          EXPORTADOSERVINT   VARCHAR2(1)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF              DTEXPORTACAO          DATE                                                             Totalizador ato cotepe             OPERACIONAL                        NaN
PCPEDICANCECF               TOTALIZADOR   VARCHAR2(7)                                                                                 NaN            OPERACIONAL                        NaN
PCPEDICANCECF                  NUMCUPOM  NUMBER(10,0)                                                              NUMERO DO CUPOM FISCAL            OPERACIONAL                        NaN
PCPEDICANCECF                    NUMCCF  NUMBER(10,0)                                                        NUMERO CONTADOR CUPOM FISCAL            OPERACIONAL                        NaN
PCPEDICANCECF                ROTINALANC  VARCHAR2(48)                                                      ROTINA QUE GRAVOU A INFORMACAO            OPERACIONAL                        NaN
PCPEDICANCECF              CUPOMFECHADO   VARCHAR2(1)                                                       Cancelamento de cupom fechado            OPERACIONAL                        NaN
PCPEDICANCECF        MOTIVOCANCELAMENTO VARCHAR2(150)                                                              Motivo do cancelamento            OPERACIONAL                        NaN
PCPEDICANCECF              DESCRICAOPAF VARCHAR2(200)                                           Descrição do produto que apareceu na tela            OPERACIONAL                        NaN
PCPEDICANCECF                CANCMANUAL   VARCHAR2(1)                                                  Indicador de cancelamento manual.             OPERACIONAL                        NaN
PCPEDICANCECF                    MD5PAF VARCHAR2(200)                                                   Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN
PCPEDICANCECF                   CODCEST   VARCHAR2(7)                                                                codigo ceste produto            OPERACIONAL                        NaN
PCPEDICANCECF OFERTATERCEIROSPROCESSADA   VARCHAR2(1)                                 Indica se a oferta foi processada ou não pelo motor            OPERACIONAL                        NaN
PCPEDICANCECF                TIPOCANCEL   VARCHAR2(1)                               Define se o cancelamento do item foi parcial ou total            OPERACIONAL                        NaN
PCPEDICANCECF       INDDEDUZDESONERACAO   NUMBER(1,0) Identifica se houve ou não desoneração ( 0 -sem desoneração / 1 - com desoneração).            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*