# 📊 Tabela: PCBENEFICFISCALCREDPRES

### Estrutura de Colunas e Restrições

                 Tabela                Coluna   Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICFISCALCREDPRES    CODBENEFICIOFISCAL   VARCHAR2(10)                                             Código do Benefício Fiscal            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES                 CODST    NUMBER(4,0)                                 Código da figura tributária rotina 514            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES            ALIQICMSNF VARCHAR2(1000)                                                    Alíquota ICMS da NF            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES     ALIQCREDPRESUMIDO   NUMBER(12,4)                                             Alíquota Crédito Presumido            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES       FORMULACREDPRES  VARCHAR2(200)                     Código do cadastro de Formula do Crédito Presumido            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES          ORIGMERCTRIB   VARCHAR2(20)                                                   Origem da Mercadoria            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES             SITTRIBUT VARCHAR2(1000)                                                    Situação Tributária            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES             CODFISCAL VARCHAR2(1000)                       Código Fiscal de Operações e de Prestações(CFOP)            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES           TIPOEMPRESA    VARCHAR2(4)                                                           Tipo Empresa            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES            TIPOPESSOA    VARCHAR2(1)                                                            Tipo Pessoa            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES CONTRIBUINTECONSFINAL    VARCHAR2(1)                                          Contribuinte Consumidor Final            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES                   NCM VARCHAR2(1000)                                         Nomenclatura Comum do Mercosul            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES            DTCADASTRO           DATE                                                       Data de Cadastro            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES        CCREDPRESUMIDO   VARCHAR2(10) Código de Benefício Fiscal de Crédito Presumido na UF aplicado ao item            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES      DESCONSIDERARNCM    VARCHAR2(1)                                                      Desconsiderar NCM            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES     DESCONSIDERARCFOP    VARCHAR2(1)                                                     Desconsiderar CFOP            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRES                IDPRES   NUMBER(10,0)                                                   ID Crédito Presumido    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICFISCALCREDPRES             DESCRICAO  VARCHAR2(100)                               Descrição da Figura do Crédito Presumido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*