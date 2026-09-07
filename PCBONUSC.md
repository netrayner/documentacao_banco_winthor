# 📊 Tabela: PCBONUSC

### Estrutura de Colunas e Restrições

  Tabela                 Coluna  Tipo/Tamanho                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBONUSC               NUMBONUS  NUMBER(10,0)                                                  Descricao coluna NUMBONUS    CHAVE PRIMÁRIA (PK)                        NaN
PCBONUSC              DATABONUS          DATE                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                  QTNFS   NUMBER(6,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC             VALORTOTAL  NUMBER(14,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC              PESOTOTAL  NUMBER(14,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                 DATARM          DATE                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC              CODFUNCRM   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                    OBS VARCHAR2(240)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           DTFECHAMENTO          DATE                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           CODFUNCBONUS   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           CODFUNCFECHA   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC              CODFILIAL   VARCHAR2(2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                  PLACA  VARCHAR2(30)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC              TIPOSENHA   VARCHAR2(1)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                   HORA   NUMBER(2,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                 MINUTO   NUMBER(2,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                  SENHA   NUMBER(6,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC              TIPOCARGA   VARCHAR2(1)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                   PESO  NUMBER(10,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC        CODFORNECTRANSP   NUMBER(6,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                   OBS1  VARCHAR2(60)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                   OBS2  VARCHAR2(60)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           TIPODESCARGA   VARCHAR2(1)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC             VLDESCARGA  NUMBER(14,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC             DTDESCARGA          DATE                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC          NUMVIASRECIBO   NUMBER(2,0)                                      Indica a quantidade de vias impressa.            OPERACIONAL                        NaN
PCBONUSC           CALCDESCARGA   VARCHAR2(1)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC            VLDESCARGAP  NUMBER(14,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC            VLDESCARGAV  NUMBER(14,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC        TOTPESODESCARGA  NUMBER(14,4)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC      TOTVOLUMEDESCARGA  NUMBER(14,4)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC               DTCANCEL          DATE                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC          CODFUNCCANCEL   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           MOTIVOCANCEL  VARCHAR2(40)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                   OBS3 VARCHAR2(150)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                   OBS4 VARCHAR2(150)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                   OBS5 VARCHAR2(150)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC            VLINFORMADO  NUMBER(14,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                    BOX   NUMBER(6,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC          NOMEMOTORISTA  VARCHAR2(60)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC    QTBLOQUEADALIBERADA   VARCHAR2(1)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC                EMITIDO   VARCHAR2(1)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC         MINUTOMONTAGEM   NUMBER(2,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           HORAMONTAGEM   NUMBER(2,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           PESOBALANCA1  NUMBER(14,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           PESOBALANCA2  NUMBER(14,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC            VLADICIONAL  NUMBER(20,2)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC    CODBANCORECDESCARGA   NUMBER(4,0)                                     Indica o banco do calculo de descarga.            OPERACIONAL                        NaN
PCBONUSC             VLDESCONTO  NUMBER(20,2)                                   Valor do desconto no recibo de descarga.            OPERACIONAL                        NaN
PCBONUSC           NUMVIASBONUS   NUMBER(3,0)                           Indica a quantidade de cópias emitidas do bonus.            OPERACIONAL                        NaN
PCBONUSC     CODBANCORECREMONTE   NUMBER(4,0)                                                  Indica o código do banco.            OPERACIONAL                        NaN
PCBONUSC   NUMVIASRECIBOREMONTE   NUMBER(2,0)                                      Indica o número de vias de impressão.            OPERACIONAL                        NaN
PCBONUSC       QTPALETESREMONTE   NUMBER(6,0)                                            Indica a quantidade de paletes.            OPERACIONAL                        NaN
PCBONUSC              VLREMONTE  NUMBER(20,2)                                                 Indica o valor do remonte.            OPERACIONAL                        NaN
PCBONUSC      DATAFECHACOMPLETA          DATE                                                  Indica a data fechamento.            OPERACIONAL                        NaN
PCBONUSC             DTMONTAGEM          DATE                                        Indica a data de montagem do bônus.            OPERACIONAL                        NaN
PCBONUSC      DTFECHAMENTOTOTAL          DATE                                  Indica a Data e hora de fechamento bonus.            OPERACIONAL                        NaN
PCBONUSC        NUMTRANSENTLOTE  NUMBER(10,0)                                           NUMERO TRANSAÇÃO ENTRADA DE LOTE            OPERACIONAL                        NaN
PCBONUSC      NUMTRANSVENDALOTE  NUMBER(10,0)                                          NUMERO TRANSAÇÃO DE VENDA DE LOTE            OPERACIONAL                        NaN
PCBONUSC       TIPODOCMOTORISTA   VARCHAR2(3)                                             Tipo do documento do motorista            OPERACIONAL                        NaN
PCBONUSC        NUMDOCMOTORISTA  VARCHAR2(15)                                           Numero do documento do motorista            OPERACIONAL                        NaN
PCBONUSC     DTCHEGADAMOTORISTA          DATE                                        Data e hora de chegada do motorista            OPERACIONAL                        NaN
PCBONUSC ENDERECAMENTOPORPALETE       CHAR(1)                         Informa se o bônus será endereçado palete a palete            OPERACIONAL                        NaN
PCBONUSC         UTILIZOUPREENT   VARCHAR2(1) Verifica se o bônus vai ser utilizando a pré-entrada ou nota fiscal normal            OPERACIONAL                        NaN
PCBONUSC               DATACONF          DATE                              Indica o início da conferência do recebimento            OPERACIONAL                        NaN
PCBONUSC                  USARF   VARCHAR2(1)                                   Validar se a conferência bonus e por RF.            OPERACIONAL                        NaN
PCBONUSC             ESTBONIFIC   VARCHAR2(1)                                                         Estoque bonificado            OPERACIONAL                        NaN
PCBONUSC       LIBERAESTENTMERC   VARCHAR2(1)                                   Libera estoque na entrada de mercadoria             OPERACIONAL                        NaN
PCBONUSC     LIBERAESTFECHBONUS   VARCHAR2(1)                                  Libera estoque bloq. no fechamento bônus.            OPERACIONAL                        NaN
PCBONUSC           CODFUNCMONT6   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC            DTLANCRECEB          DATE                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC            CODFUNCLANC   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           CODFUNCMONT5   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           CODFUNCMONT4   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           CODFUNCMONT3   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           CODFUNCMONT2   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           CODFUNCMONT1   NUMBER(8,0)                                                                        NaN            OPERACIONAL                        NaN
PCBONUSC           DTINTEGRACAO          DATE                                                Data de integração do bônus            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*