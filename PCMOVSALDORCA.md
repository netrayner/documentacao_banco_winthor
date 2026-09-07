# 📊 Tabela: PCMOVSALDORCA

### Estrutura de Colunas e Restrições

       Tabela           Coluna Tipo/Tamanho                                                                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVSALDORCA          CODUSUR  NUMBER(6,0)                                                                  Código do RCA. |Campo do tipo numérico, de tamanho 6, sem casas decimais.            OPERACIONAL                        NaN
PCMOVSALDORCA          VLSALDO NUMBER(12,6)                                                       Valor do saldo atual do RCA. |Campo do tipo numérico, de tamanho 12, com 6 decimais.            OPERACIONAL                        NaN
PCMOVSALDORCA       VLSALDOANT NUMBER(12,6)                                      Valor do saldo anterior a última atualização. |Campo do tipo numérico, de tamanho 12, com 6 decimais.            OPERACIONAL                        NaN
PCMOVSALDORCA             DATA         DATE                                                                                 Data e hora da movimentação do Saldo. |Campo do tipo data.            OPERACIONAL                        NaN
PCMOVSALDORCA          CODFUNC  NUMBER(6,0)                                    Código do funcionário que realizou a movimentação. |Campo do tipo numérico, de tamanho 6, sem decimais.            OPERACIONAL                        NaN
PCMOVSALDORCA           ROTINA  NUMBER(6,0)                                            Código da rotina que gerou a movimentação. |Campo do tipo numérico, de tamanho 6, sem decimais.            OPERACIONAL                        NaN
PCMOVSALDORCA             TIPO  VARCHAR2(1) Indica se é uma operação de Crédito (valor "D") ou de Débito (valor "C"). É assim mesmo, invertido. |Campo do tipo caracter, de tamanho 1.            OPERACIONAL                        NaN
PCMOVSALDORCA            VALOR NUMBER(12,6)                                                      Valor da movimentação gerada. |Campo do tipo numérico, de tamanho 12, com 6 decimais.            OPERACIONAL                        NaN
PCMOVSALDORCA        HISTORICO VARCHAR2(60)                                                          Histórico referente à alteração do Saldo. |Campo do tipo caracter, de tamanho 60.            OPERACIONAL                        NaN
PCMOVSALDORCA    NUMTRANSVENDA NUMBER(10,0)                                                                                    Número da transação de saída que gerou a movimentação.             OPERACIONAL                        NaN
PCMOVSALDORCA      NUMTRANSENT NUMBER(10,0)                                                                                  Número da transação de entrada que gerou a movimentação.             OPERACIONAL                        NaN
PCMOVSALDORCA           NUMPED NUMBER(10,0)                                                                                                                   Indica número do pedido.            OPERACIONAL                        NaN
PCMOVSALDORCA        VLRESERVA NUMBER(18,6)                                                                                                                          Valor da reserva.            OPERACIONAL                        NaN
PCMOVSALDORCA PERCSALDORESERVA  NUMBER(5,2)                                                                                                                  Percentual saldo reserva.            OPERACIONAL                        NaN
PCMOVSALDORCA       DTMXSALTER         DATE                                                                                                                                        NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*