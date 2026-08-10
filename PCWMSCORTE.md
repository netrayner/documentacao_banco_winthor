# 📊 Tabela: PCWMSCORTE

### Estrutura de Colunas e Restrições

    Tabela       Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSCORTE         DATA         DATE                            Data atual do Registro            OPERACIONAL                        NaN
PCWMSCORTE    CODFILIAL  VARCHAR2(2)                                   Filial de Corte            OPERACIONAL                        NaN
PCWMSCORTE  NUMTRANSWMS NUMBER(10,0)                                   Registro do WMS            OPERACIONAL                        NaN
PCWMSCORTE       NUMCAR NUMBER(10,0)                         Carregamento do Pedido(s)            OPERACIONAL                        NaN
PCWMSCORTE       NUMPED NUMBER(10,0)                                  Numero do Pedido            OPERACIONAL                        NaN
PCWMSCORTE        NUMOS NUMBER(12,0)                                      Numero da OS            OPERACIONAL                        NaN
PCWMSCORTE       TIPOOS  NUMBER(3,0)                        Tipo de OS definida na 528            OPERACIONAL                        NaN
PCWMSCORTE    NUMPALETE  NUMBER(6,0)                      Palete que foi feito o corte            OPERACIONAL                        NaN
PCWMSCORTE  CODENDERECO NUMBER(10,0)                                Endereço do Palete            OPERACIONAL                        NaN
PCWMSCORTE      CODPROD  NUMBER(6,0)                                 Codigo do Produto            OPERACIONAL                        NaN
PCWMSCORTE    QTCORTADA NUMBER(20,8)                                        Qt Cortada            OPERACIONAL                        NaN
PCWMSCORTE           QT NUMBER(20,8)                                      Qt do Pedido            OPERACIONAL                        NaN
PCWMSCORTE    CODFUNCOS  NUMBER(8,0)                            Funcionario Conferente            OPERACIONAL                        NaN
PCWMSCORTE CODFUNCCORTE  NUMBER(8,0)                              Funcionario de Corte            OPERACIONAL                        NaN
PCWMSCORTE    CODMOTIVO  NUMBER(6,0)                                   Motivo do Corte            OPERACIONAL                        NaN
PCWMSCORTE    CODROTINA  NUMBER(8,0)                               Rotina que efetivou            OPERACIONAL                        NaN
PCWMSCORTE      CODOPER      CHAR(1) Indica qual é a operação associada com o registro            OPERACIONAL                        NaN
PCWMSCORTE    TIPOCORTE      CHAR(1)                                        Tipo Corte            OPERACIONAL                        NaN
PCWMSCORTE      NUMLOTE VARCHAR2(15)                            Número do lote cortado            OPERACIONAL                        NaN
PCWMSCORTE          OBS VARCHAR2(30)                               Observacao do corte            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*