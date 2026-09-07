# 📊 Tabela: PCLOGLC

### Estrutura de Colunas e Restrições

 Tabela                     Coluna   Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGLC                     CODCLI    NUMBER(6,0)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                       DATA           DATE                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                   CODEMITE    NUMBER(8,0)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                   PROGRAMA   VARCHAR2(10)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                   BLOQUEIO    VARCHAR2(1)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                BLOQUEIOANT    VARCHAR2(1)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                    LIMCRED   NUMBER(12,2)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                 LIMCREDANT   NUMBER(12,2)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                DTREGLIMANT           DATE                                                 NaN            OPERACIONAL                        NaN
PCLOGLC              DTVENCLIMCRED           DATE                                                 NaN            OPERACIONAL                        NaN
PCLOGLC               DTVENCLIMANT           DATE                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                        OBS   VARCHAR2(40)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                     OBSANT   VARCHAR2(40)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                      PRAZO    NUMBER(4,0)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                   PRAZOANT    NUMBER(4,0)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                     CODCOB    VARCHAR2(4)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                  CODCOBANT    VARCHAR2(4)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                       OBS1   VARCHAR2(60)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                       OBS2   VARCHAR2(60)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                       OBS3   VARCHAR2(60)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                       OBS4   VARCHAR2(60)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                   CODPLPAG    NUMBER(4,0)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                CODPLPAGANT    NUMBER(4,0)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC                 LIMCREDCPF   NUMBER(14,2)      Indica o limite de crédito por CNPJ/CPF atual.            OPERACIONAL                        NaN
PCLOGLC              LIMCREDCPFANT   NUMBER(14,2)   Indica o limite de crédito por CNPJ/CPF anterior.            OPERACIONAL                        NaN
PCLOGLC             BLOQDEFINITIVO    VARCHAR2(1)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC          BLOQDEFINITIVOANT    VARCHAR2(1)                                                 NaN            OPERACIONAL                        NaN
PCLOGLC    UTILIZAPLPAGMEDICAMENTO    VARCHAR2(1)          Utiliza plano de pagamento  do medicamento            OPERACIONAL                        NaN
PCLOGLC UTILIZAPLPAGMEDICAMENTOANT    VARCHAR2(1) Utiliza plano de pagamento  do medicamento anterior            OPERACIONAL                        NaN
PCLOGLC              CODPLPAGETICO    NUMBER(4,0)                  Código do plano de pagamento ético            OPERACIONAL                        NaN
PCLOGLC           CODPLPAGETICOANT    NUMBER(4,0)         Código do plano de pagamento ético anterior            OPERACIONAL                        NaN
PCLOGLC           CODPLPAGGENERICO    NUMBER(4,0)               Código do plano de pagamento genérico            OPERACIONAL                        NaN
PCLOGLC        CODPLPAGGENERICOANT    NUMBER(4,0)      Código do plano de pagamento genérico anterior            OPERACIONAL                        NaN
PCLOGLC                  DTULTCOMP           DATE                               Data da Última Compra            OPERACIONAL                        NaN
PCLOGLC               DTULTCOMPANT           DATE                      Data Anterior da Última Compra            OPERACIONAL                        NaN
PCLOGLC                     OBSALT VARCHAR2(1000)                            Observações da Alteração            OPERACIONAL                        NaN
PCLOGLC              NUMTRANSVENDA   NUMBER(10,0)                        Número da transação de venda            OPERACIONAL                        NaN
PCLOGLC                     DUPLIC   NUMBER(10,0)                                           Duplicata            OPERACIONAL                        NaN
PCLOGLC                      PREST    VARCHAR2(2)                                           Prestação            OPERACIONAL                        NaN
PCLOGLC          NUMTRANSVENDAORIG   NUMBER(10,0)               Número da transação de venda original            OPERACIONAL                        NaN
PCLOGLC                  PRESTORIG    VARCHAR2(2)                                  Prestação original            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*