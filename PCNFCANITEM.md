# 📊 Tabela: PCNFCANITEM

### Estrutura de Colunas e Restrições

     Tabela                Coluna  Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFCANITEM           NUMTRANSENT  NUMBER(10,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM         NUMTRANSVENDA  NUMBER(10,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM          CODFUNCEMITE   NUMBER(8,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM           DATAEMISSAO          DATE                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM           CODFUNCCANC   NUMBER(8,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM              DATACANC          DATE                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM               CODPROD   NUMBER(6,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM                    QT  NUMBER(20,6)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM                PVENDA  NUMBER(18,6)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM               PTABELA  NUMBER(18,6)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM                NUMSEQ  NUMBER(20,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM                CODCLI   NUMBER(6,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM             CODFORNEC   NUMBER(6,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM                MOTIVO  VARCHAR2(60)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM                NUMPED  NUMBER(10,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM                NUMCAR   NUMBER(8,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM          NUMPEDCOMPRA  NUMBER(10,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM             CODROTINA   NUMBER(6,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM             DESCRICAO VARCHAR2(100)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM               CODUSUR   NUMBER(4,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM               NUMORCA  NUMBER(10,0)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM              PBASERCA  NUMBER(18,6)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM DTIMPORTACAOSERVPRINC          DATE                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM    IMPORTADOSERVPRINC   VARCHAR2(1)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM   DTEXPORTACAOSERVINT          DATE                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM      EXPORTADOSERVINT   VARCHAR2(1)                                                           NaN            OPERACIONAL                        NaN
PCNFCANITEM              HORACANC          DATE                               Indica a hora do cancelamento.             OPERACIONAL                        NaN
PCNFCANITEM    DTPEDIMPORTACAOWMS          DATE                   Data de importação WMS do pedido cancelado.            OPERACIONAL                        NaN
PCNFCANITEM  CODFUNCEXPORTACAOWMS   NUMBER(8,0)                      Código do funcionário da exportação WMS.            OPERACIONAL                        NaN
PCNFCANITEM       DTEXPORTACAOWMS          DATE                                  Data de exportação para WMS.            OPERACIONAL                        NaN
PCNFCANITEM           CODAUXILIAR  NUMBER(20,0)                         Indica o código auxiliar da embalagem            OPERACIONAL                        NaN
PCNFCANITEM         CODSUPERVISOR   NUMBER(4,0)                        Indica o código do SUPERVISOR por item            OPERACIONAL                        NaN
PCNFCANITEM        CODPROMOCAOMED   NUMBER(9,0)                                Código da Promoção Medicamento            OPERACIONAL                        NaN
PCNFCANITEM           SERVICO_WTA  VARCHAR2(48) Indica a versão do serviço do WTA que inseriu aquele registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*