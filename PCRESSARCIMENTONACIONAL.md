# 📊 Tabela: PCRESSARCIMENTONACIONAL

### Estrutura de Colunas e Restrições

                 Tabela                         Coluna  Tipo/Tamanho                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRESSARCIMENTONACIONAL                      CODFILIAL   VARCHAR2(2)                                                                     Código da Filial            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                   NUMTRANSACAO  NUMBER(10,0)                                        Número da transação pode ser entrada ou saída            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                  DATA_OPERACAO          DATE                                         Data do movimento, pode ser entrada ou saída            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                  TIPO_OPERACAO   VARCHAR2(2)                 Tipo da operação SI para Saldo Inicial S para saída e E para Entrada            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                   TIPO_CLIENTE   VARCHAR2(2)    Tipo do cliente, consumidor, contribuinte, ou um dos três tipos de órgão público.            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                  CODIGO_MOTIVO  VARCHAR2(10) Código do motivo utilizado na escrituração, pode ser de ressarcimento ou complemento            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                        NUMNOTA   NUMBER(9,0)                                  Número da nota fiscal, pode ser de Entrada ou Saída            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                        CODPROD   NUMBER(9,0)                                                                    Código do produto            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                         NUMSEQ   NUMBER(9,0)                            Número sequencial, pode ser NITEMXML, NUMSEQENT ou NUMSEQ            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                        CODOPER   VARCHAR2(2)                                                     Código da Operação conforme cfop            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                            CST   VARCHAR2(3)                                                        Código da Situação Tributária            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                      CODFISCAL   VARCHAR2(4)                                                                   Código Fiscal CFOP            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                        UNIDADE   VARCHAR2(6)                                                                  Unidade da operação            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                      DESCRICAO VARCHAR2(140)                                                                Descrição do produto             OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                        CODCEST   VARCHAR2(7)                                                               Código CEST do produto            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                          QTEST  NUMBER(22,8)                                                                         Saldo (H010)            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                         QTCONT  NUMBER(22,8)                                               Quantidade Saída e Entrada (UNIFICADO)            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                      PUNITCONT  NUMBER(22,8)                                                            Vl. unitário do produto,             OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL            VLMEDIABASEST_SALDO  NUMBER(18,6)                                                               Saldo médio BC ICMS ST            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL              VLMEDIAICMS_SALDO  NUMBER(18,6)                                                               Saldo Médio do ICMS OP            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                VLMEDIAST_SALDO  NUMBER(18,6)                                                               Saldo médio do ICMS/ST            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL             VLMEDIAFCPST_SALDO  NUMBER(18,6)                                                                Saldo Médio do FCP ST            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL           VLMEDIABASEST_DIARIA  NUMBER(18,6)                                           Média diária BC ST proporcional a QT saída            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL             VLMEDIAICMS_DIARIA  NUMBER(18,6)                                         Média diária ICMS OP proporcional a QT saída            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL               VLMEDIAST_DIARIA  NUMBER(18,6)                                         Média diária ICMS ST proporcional a QT saída            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL            VLMEDIAFCPST_DIARIA  NUMBER(18,6)                                          Média diária FCP ST proporcional a QT saída            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL           VLBASEICMSST_ENTRADA  NUMBER(18,6)                                          Vl. Unitário da BC ICMS ST da NF de entrada            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                 VLICMS_ENTRADA  NUMBER(18,6)                                                   Vl. Unitário ICMS OP NF de entrada            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL               VLICMSST_ENTRADA  NUMBER(18,6)                                                      Vl. Unitário ICMS ST NF entrada            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                VLFCPST_ENTRADA  NUMBER(18,6)                                                     Vl. Unitário ICMS FCP ST entrada            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL             VLMEDIABASEST_UNIT  NUMBER(18,6)                                                 Vl. Média BC ICMS ST Unitário (H030)            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                 VLMEDIAST_UNIT  NUMBER(18,6)                                                           Vl. Média ICMS ST Unitário            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL               VLMEDIAICMS_UNIT  NUMBER(18,6)                                                              Vl. Média ICMS Unitário            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL              VLMEDIAFCPST_UNIT  NUMBER(18,6)                                                            Vl. Média FCP ST Unitário            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL          C185_C10_VL_UNIT_ICMS  NUMBER(18,6)                                                            Campo 10 do registro C185            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL   C185_C12_VL_UNIT_ICMS_OP_EST  NUMBER(18,6)                                                            Campo 12 do registro C185            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL   C185_C13_VL_UNIT_ICMS_ST_EST  NUMBER(18,6)                                                            Campo 13 do registro C185            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL    C185_C14_VL_UNIT_FCP_ST_EST  NUMBER(18,6)                                                            Campo 14 do registro C185            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL  C185_C15_VL_UNIT_ICMS_ST_REST  NUMBER(18,6)                                                            Campo 15 do Registro C185            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL   C185_C16_VL_UNIT_FCP_ST_REST  NUMBER(18,6)                                                            Campo 16 do registro C185            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL C185_C17_VL_UNIT_ICMS_ST_COMPL  NUMBER(18,6)                                                            Campo 17 do registro C185            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL  C185_C18_VL_UNIT_FCP_ST_COMPL  NUMBER(18,6)                                                            Campo 18 do registro C185            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL   REG_1255_C03_CREDITO_ICMS_OP  NUMBER(18,6)                                                            Campo 03 do registro 1255            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL      REG_1255_C04_ICMS_ST_REST  NUMBER(18,6)                                                            Campo 04 do registro 1255            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL       REG_1255_C05_FCP_ST_REST  NUMBER(18,6)                                                            Campo 05 do registro 1255            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL     REG_1255_C06_ICMS_ST_COMPL  NUMBER(18,6)                                                            Campo 06 do registro 1255            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL      REG_1255_C07_FCP_ST_COMPL  NUMBER(18,6)                                                            Campo 17 do registro 1255            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL               UNIDADECOMERCIAL   VARCHAR2(6)                                                           Unidade de Comercialização            OPERACIONAL                        NaN
PCRESSARCIMENTONACIONAL                       QTUNITCX  NUMBER(10,2)                                                                    Quantidade Master            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*