# 📊 Tabela: PCLOGROTINA

### Estrutura de Colunas e Restrições

     Tabela                  Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGROTINA              DATAINICIO         DATE                                NaN            OPERACIONAL                        NaN
PCLOGROTINA               CODROTINA  NUMBER(6,0)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA                 CODFUNC  NUMBER(8,0)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA               DATAFINAL         DATE                                NaN            OPERACIONAL                        NaN
PCLOGROTINA             EQUIPAMENTO VARCHAR2(40)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA                 CODPROD  NUMBER(6,0)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA               PVENDAANT NUMBER(10,2)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA                  PVENDA NUMBER(10,2)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA                  MARGEM  NUMBER(6,2)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA               MARGEMANT  NUMBER(6,2)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA               NUMREGIAO  NUMBER(4,0)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA                 CODEPTO  NUMBER(6,0)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA             TIPOMERCANT  VARCHAR2(6)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA           TIPOMERCATUAL  VARCHAR2(6)                                NaN            OPERACIONAL                        NaN
PCLOGROTINA                  QTUNIT NUMBER(18,6)                     Qtde.Unitária.            OPERACIONAL                        NaN
PCLOGROTINA              FATORPRECO NUMBER(20,8)                       Fator Preço.            OPERACIONAL                        NaN
PCLOGROTINA      PERVARIACAOPTABELA NUMBER(20,8)                 Variação de Preço.            OPERACIONAL                        NaN
PCLOGROTINA               QTUNITANT NUMBER(18,6)            Qtde.Unitária Anterior.            OPERACIONAL                        NaN
PCLOGROTINA           FATORPRECOANT NUMBER(20,8)              Fator Preço Anterior.            OPERACIONAL                        NaN
PCLOGROTINA   PERVARIACAOPTABELAANT NUMBER(20,8)        Variação de Preço Anterior.            OPERACIONAL                        NaN
PCLOGROTINA         MARGEMIDEALATAC  NUMBER(6,2)                    Margem Atacado.            OPERACIONAL                        NaN
PCLOGROTINA      MARGEMIDEALATACANT  NUMBER(6,2)           Margem Atacado Anterior.            OPERACIONAL                        NaN
PCLOGROTINA         QTMINIMAATACADO NUMBER(18,6)              Qtde. Minima Atacado.            OPERACIONAL                        NaN
PCLOGROTINA      QTMINIMAATACADOANT NUMBER(18,6)     Qtde. Minima Atacado Anterior.            OPERACIONAL                        NaN
PCLOGROTINA              QTMULTIPLA  NUMBER(6,0)                    Qtde. Multipla.            OPERACIONAL                        NaN
PCLOGROTINA           QTMULTIPLAANT  NUMBER(6,0)           Qtde. Multipla Anterior.            OPERACIONAL                        NaN
PCLOGROTINA    ACEITAPRECOREPLICADO  VARCHAR2(1)             Aceita Replicar Preço.            OPERACIONAL                        NaN
PCLOGROTINA ACEITAPRECOREPLICADOANT  VARCHAR2(1)    Aceita Replicar Preço Anterior.            OPERACIONAL                        NaN
PCLOGROTINA     PERMITEVENDAATACADO  VARCHAR2(1)          Permite Venda no Atacado.            OPERACIONAL                        NaN
PCLOGROTINA  PERMITEVENDAATACADOANT  VARCHAR2(1) Permite Venda no Atacado Anterior.            OPERACIONAL                        NaN
PCLOGROTINA             CODAUXILIAR NUMBER(16,0)          Indica o código auxiliar.            OPERACIONAL                        NaN
PCLOGROTINA               CODFILIAL  VARCHAR2(2)            Indica o código filial.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*