# 📊 Tabela: PCPRACA

### Estrutura de Colunas e Restrições

 Tabela            Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRACA          CODPRACA   NUMBER(4,0)                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRACA             PRACA  VARCHAR2(25)                                            NaN            OPERACIONAL                        NaN
PCPRACA         NUMREGIAO   NUMBER(4,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA              ROTA   NUMBER(4,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA           SEQROTA   NUMBER(4,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA         POPULACAO  NUMBER(14,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA  PERFRETEPROGRESS   NUMBER(8,4)                                            NaN            OPERACIONAL                        NaN
PCPRACA      CODPRACAORIG   NUMBER(6,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA         DISTANCIA  NUMBER(12,2)                                            NaN            OPERACIONAL                        NaN
PCPRACA      VLPAUTAFRETE  NUMBER(12,2)                                            NaN            OPERACIONAL                        NaN
PCPRACA     CODPRACAORIG2   NUMBER(6,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA     CODPRACAORIG3   NUMBER(6,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA     CODPRACAORIG4   NUMBER(6,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA          CODMUNIC   NUMBER(8,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA          SITUACAO   VARCHAR2(1)                                            NaN            OPERACIONAL                        NaN
PCPRACA        NUMREGIAO2   NUMBER(4,0)                                            NaN            OPERACIONAL                        NaN
PCPRACA        DTCADASTRO          DATE  Data em que foi efetuado o cadastro da praça.            OPERACIONAL                        NaN
PCPRACA        CEPINICIAL   VARCHAR2(9)                Código do CEP Inicial da Praça.            OPERACIONAL                        NaN
PCPRACA          CEPFINAL   VARCHAR2(9)                  Código do CEP Final da Praça.            OPERACIONAL                        NaN
PCPRACA PRIORIDADEENTREGA   VARCHAR2(1)     Prioridade de entrega de pedidos na praça.            OPERACIONAL                        NaN
PCPRACA         TIPOPRACA   VARCHAR2(1)         Tipo de Praça F ou P - Frete ou Praça.            OPERACIONAL                        NaN
PCPRACA               OBS VARCHAR2(300) Indica as obsevações para o cadastro de praça.            OPERACIONAL                        NaN
PCPRACA CODPRACAPRINCIPAL   NUMBER(4,0)            Indica o código da praça principal.            OPERACIONAL                        NaN
PCPRACA       VLMINCARREG  NUMBER(12,2)                     Vl. Mínimo Montagem Carga.            OPERACIONAL                        NaN
PCPRACA     PERCMINCARREG  NUMBER(10,2)              Variação do valor minimo de carga            OPERACIONAL                        NaN
PCPRACA        DTMXSALTER          DATE                                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*