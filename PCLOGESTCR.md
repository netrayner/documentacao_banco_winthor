# 📊 Tabela: PCLOGESTCR

### Estrutura de Colunas e Restrições

    Tabela              Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGESTCR            PROGRAMA VARCHAR2(80)                    Nome do programa que realizou a movimentação.            OPERACIONAL                        NaN
PCLOGESTCR             DATALOG         DATE                                   Data da movimentação com hora.            OPERACIONAL                        NaN
PCLOGESTCR              CODCOB  VARCHAR2(4)                                  Codigo da cobrança movimentada.            OPERACIONAL                        NaN
PCLOGESTCR            CODBANCO  NUMBER(4,0)                                     Codigo do banco movimentado.            OPERACIONAL                        NaN
PCLOGESTCR               VALOR NUMBER(16,2)                                      Valor Final do saldo banco.            OPERACIONAL                        NaN
PCLOGESTCR           VALOR_OLD NUMBER(16,2)                                    Valor inicial do saldo banco.            OPERACIONAL                        NaN
PCLOGESTCR     VALORCONCILIADO NUMBER(16,2)                                 Valor final do saldo conciliado.            OPERACIONAL                        NaN
PCLOGESTCR VALORCONCILIADO_OLD NUMBER(16,2)                               Valor inicial do saldo conciliado.            OPERACIONAL                        NaN
PCLOGESTCR             MAQUINA VARCHAR2(80)                     Nome da maquina que executou a movimentação.            OPERACIONAL                        NaN
PCLOGESTCR             USUARIO VARCHAR2(80)                     Nome do Usuario que executou a movimentação.            OPERACIONAL                        NaN
PCLOGESTCR                 DIF NUMBER(16,4)            Diferença do saldo inicial e final do saldo do banco.            OPERACIONAL                        NaN
PCLOGESTCR           DIFCONCIL NUMBER(16,4) diferença do saldo inicial e final do saldo conciliado do banco.            OPERACIONAL                        NaN
PCLOGESTCR                  OK  VARCHAR2(1)                           verificação se o processo foi correto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*