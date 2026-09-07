# 📊 Tabela: PCTEMP_PISCOFINS

### Estrutura de Colunas e Restrições

          Tabela                   Coluna  Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTEMP_PISCOFINS                  TIPOMOV       CHAR(1)                                      Tipo Movimentação            OPERACIONAL                        NaN
PCTEMP_PISCOFINS              NAT_BC_CRED   VARCHAR2(2)                               Natureza Base do Crédito            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                  CODPROD  VARCHAR2(60)                                         Código Produto            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                  CST_PIS   NUMBER(3,0)                         Código Situação Tributária PIS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS               CST_COFINS   NUMBER(3,0)                      Código Situação Tributária COFINS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                   VLOPER  NUMBER(18,2)                                         Valor Operação            OPERACIONAL                        NaN
PCTEMP_PISCOFINS          VLBASEPISCOFINS  NUMBER(18,2)                                  Valor Base PIS/COFINS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                   PERPIS  NUMBER(10,4)                                         Percentual PIS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                    VLPIS  NUMBER(18,2)                                              Valor PIS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                PERCOFINS  NUMBER(10,4)                                      Percentual COFINS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                 VLCOFINS  NUMBER(18,2)                                          Valor CO}FINS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                 REGISTRO   VARCHAR2(4)                                               Registro            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                   MODELO   VARCHAR2(2)                                                 Modelo            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                  CODCONT   NUMBER(2,0)                                        Código Contábil            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                CODFISCAL   NUMBER(4,0)                                          Código Fiscal            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                  CODCRED   NUMBER(3,0)                                         Código Crédito            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                      NCM  VARCHAR2(15)                                                    NCM            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                  NAT_REC  NUMBER(10,0)                                  Natureza Recolhimento            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                    IDREG   NUMBER(2,0)                                            ID Registro            OPERACIONAL                        NaN
PCTEMP_PISCOFINS           BASE_QUANT_PIS  NUMBER(18,3)                                    Base Quantidade PIS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS             PERPIS_REAIS  NUMBER(18,4)                                   Percentual PIS Reais            OPERACIONAL                        NaN
PCTEMP_PISCOFINS        BASE_QUANT_COFINS  NUMBER(18,3)                                 Base Quantidade COFINS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS          PERCOFINS_REAIS  NUMBER(18,4)                                Percentual COFINS Reais            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                  COD_CTA  VARCHAR2(60)                                           Código Conta            OPERACIONAL                        NaN
PCTEMP_PISCOFINS               DESC_COMPL VARCHAR2(200)                                 Descrição Complementar            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                  CODCEST   VARCHAR2(7)                                                    NaN            OPERACIONAL                        NaN
PCTEMP_PISCOFINS         CODCONTACONTSPED VARCHAR2(255)        Código de Contas Contábeis para geração do SPED            OPERACIONAL                        NaN
PCTEMP_PISCOFINS DEDUZIRICMSBASEPISCOFINS   VARCHAR2(1) Deduzir Valor do ICMS na Base de Cálculo do PIS/COFINS            OPERACIONAL                        NaN
PCTEMP_PISCOFINS                   VLICMS  NUMBER(22,6)                                          Valor do ICMS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*