# 📊 Tabela: PCWMS

### Estrutura de Colunas e Restrições

Tabela                Coluna Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
 PCWMS               CODPROD  NUMBER(6,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS              NUMBONUS  NUMBER(6,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS                    QT NUMBER(20,8)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS               CODOPER  VARCHAR2(2)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS                NUMCAR  NUMBER(8,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS               NUMLOTE VARCHAR2(15)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS                CODCLI  NUMBER(6,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS            CODVEICULO  NUMBER(4,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS            MAPAGERADO  VARCHAR2(1)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS            ABASTECIDO  VARCHAR2(1)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS               DATAWMS         DATE                                                                 NaN            OPERACIONAL                        NaN
 PCWMS              DTCANCEL         DATE                                                                 NaN            OPERACIONAL                        NaN
 PCWMS             CODROTINA  NUMBER(6,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS               DESTINO VARCHAR2(20)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS                NUMPED NUMBER(10,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS            CODDISTRIB  VARCHAR2(4)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS           NUMVIASMAPA  NUMBER(2,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS           NUMTRANSWMS NUMBER(10,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS               TOTPESO NUMBER(12,4)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS             TOTVOLUME NUMBER(12,4)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS         NUMSEQENTREGA NUMBER(20,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS               NUMNOTA NUMBER(10,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS             CODFILIAL  VARCHAR2(2)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS                 DTENT         DATE                                                                 NaN            OPERACIONAL                        NaN
 PCWMS             CODFORNEC  NUMBER(9,0)                                          Descricao coluna CODFORNEC            OPERACIONAL                        NaN
 PCWMS           NUMTRANSENT NUMBER(10,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS               VLTOTAL NUMBER(12,2)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS   TIPOEMBALAGEMPEDIDO  VARCHAR2(1)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS                PVENDA NUMBER(18,6)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS             DTENTREGA         DATE                                                                 NaN            OPERACIONAL                        NaN
 PCWMS              CODPRACA  NUMBER(4,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS           CODFUNCCONF  NUMBER(8,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS      CODFUNCEMBALADOR  NUMBER(8,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS        HORAINICIALSEP  NUMBER(2,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS      MINUTOINICIALSEP  NUMBER(2,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS          HORAFINALSEP  NUMBER(2,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS        MINUTOFINALSEP  NUMBER(2,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS            PVENDABASE NUMBER(10,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS            QTSEPARADA NUMBER(20,8)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS         NUMTRANSVENDA NUMBER(10,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS    SEPARACAOCONCLUIDA  VARCHAR2(1)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS              TIPOMAPA  VARCHAR2(1)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS              QTUNITCX NUMBER(12,2)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS            QTTOTPALCX NUMBER(10,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS              QTPALETE NUMBER(10,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS                  QTCX NUMBER(10,0)                                               Descricao coluna QTCX            OPERACIONAL                        NaN
 PCWMS                  QTUN NUMBER(16,6)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS                NUMSEQ  NUMBER(8,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS                 QTBOX NUMBER(20,8)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS             DTGERACAO         DATE                                                                 NaN            OPERACIONAL                        NaN
 PCWMS           CODFUNCGERA  NUMBER(8,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS            FRACIONADO  VARCHAR2(1)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS               BLOCADO  VARCHAR2(1)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS              QTAVARIA NUMBER(20,6)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS        NUMSEQMONTAGEM  NUMBER(4,0)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS           QTBLOQUEADA NUMBER(20,6)                                      Indica a quantidade bloqueada.            OPERACIONAL                        NaN
 PCWMS       CODFILIALORIGEM  VARCHAR2(2) Indica o código da filial de gestão que originou o registro no WMS.            OPERACIONAL                        NaN
 PCWMS                 NUMOP VARCHAR2(20)                    Numero da ordem de produção gerada no módulo 16.            OPERACIONAL                        NaN
 PCWMS               QTPECAS NUMBER(20,8)                                           Campo para peso variável.            OPERACIONAL                        NaN
 PCWMS           QTPECASORIG NUMBER(14,6)                                        QUANTIDADE DE PEÇAS ORIGINAL            OPERACIONAL                        NaN
 PCWMS              QTCXORIG NUMBER(14,6)                                       QUANTIDADE DE CAIXAS ORIGINAL            OPERACIONAL                        NaN
 PCWMS          LISTARPEDIDO  VARCHAR2(1)                 VALIDAR SE UM DETERMINADO PEDIDO JÁ FOI PROCESSADO.            OPERACIONAL                        NaN
 PCWMS     DTINICIOPROMOLOTE         DATE                                            Data inicial da promoção            OPERACIONAL                        NaN
 PCWMS        DTFIMPROMOLOTE         DATE                                              Data final da promoção            OPERACIONAL                        NaN
 PCWMS NUMTRANSABASTECIMENTO NUMBER(10,0)                                      Número transação abastecimento            OPERACIONAL                        NaN
 PCWMS          QTANTECIPADA NUMBER(20,8)                              A qtde que foi antecipada na separação            OPERACIONAL                        NaN
 PCWMS           CODPRODACAB  NUMBER(8,0)                                         "Código do produto acabado"            OPERACIONAL                        NaN
 PCWMS                 QTANT NUMBER(14,6)                                                                 NaN            OPERACIONAL                        NaN
 PCWMS            DTMXSALTER         DATE                                                                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*