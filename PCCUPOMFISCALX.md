# 📊 Tabela: PCCUPOMFISCALX

### Estrutura de Colunas e Restrições

        Tabela                Coluna  Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCUPOMFISCALX                CODIGO   NUMBER(3,0)                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCUPOMFISCALX                  DATA          DATE                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCUPOMFISCALX                NUMECF   NUMBER(4,0)                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCUPOMFISCALX             SITTRIBUT   VARCHAR2(4)                                     NaN            OPERACIONAL                        NaN
PCCUPOMFISCALX                 VALOR  NUMBER(12,2)                                     NaN            OPERACIONAL                        NaN
PCCUPOMFISCALX             CODFILIAL   VARCHAR2(2)                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCUPOMFISCALX             EXPORTADO   VARCHAR2(1)                                     NaN            OPERACIONAL                        NaN
PCCUPOMFISCALX          DTEXPORTACAO          DATE                                     NaN            OPERACIONAL                        NaN
PCCUPOMFISCALX        NUMCAIXAFISCAL   NUMBER(4,0)                                     NaN            OPERACIONAL                        NaN
PCCUPOMFISCALX      EXPORTADOSERVINT   VARCHAR2(1)                                     NaN            OPERACIONAL                        NaN
PCCUPOMFISCALX   DTEXPORTACAOSERVINT          DATE                                     NaN            OPERACIONAL                        NaN
PCCUPOMFISCALX DTIMPORTACAOSERVPRINC          DATE                                     NaN            OPERACIONAL                        NaN
PCCUPOMFISCALX    IMPORTADOSERVPRINC   VARCHAR2(1)                                     NaN            OPERACIONAL                        NaN
PCCUPOMFISCALX           VALORMOVECF  NUMBER(14,2)       Valor para operações não-fiscais.            OPERACIONAL                        NaN
PCCUPOMFISCALX              NUMSERIE  VARCHAR2(30) Indica o número de série do equipamento            OPERACIONAL                        NaN
PCCUPOMFISCALX            ASSINATURA VARCHAR2(255)                             Código Md-5            OPERACIONAL                        NaN
PCCUPOMFISCALX               POSICAO   VARCHAR2(7)                        Posição aliquota            OPERACIONAL                        NaN
PCCUPOMFISCALX           NUMREDUCAOZ   NUMBER(6,0)                       Número da redução            OPERACIONAL                        NaN
PCCUPOMFISCALX            ROTINALANC  VARCHAR2(48)          ROTINA QUE GRAVOU A INFORMACAO            OPERACIONAL                        NaN
PCCUPOMFISCALX                MD5PAF VARCHAR2(200)       Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN
PCCUPOMFISCALX              NUMCAIXA   NUMBER(4,0)                         Número do caixa            OPERACIONAL                        NaN
PCCUPOMFISCALX   NUMEROORDEMOPERACAO   NUMBER(8,0)     Número contador de operações da ecf            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*