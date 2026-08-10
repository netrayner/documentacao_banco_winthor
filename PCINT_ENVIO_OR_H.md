# 📊 Tabela: PCINT_ENVIO_OR_H

### Estrutura de Colunas e Restrições

          Tabela           Coluna  Tipo/Tamanho                                                                                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINT_ENVIO_OR_H ORDEMRECEBIMENTO   NUMBER(7,0)                                                                                                                                                         Número da OR            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H              ANO   VARCHAR2(4)                                                                                                                                                  Ano de movimentação            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H              MES   VARCHAR2(2)                                                                                                                                                  Mês da movimentação            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H              DIA   VARCHAR2(2)                                                                                                                                                  Dia da movimentação            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H             HORA   VARCHAR2(8)                                                                                                                                                 Hora da movimentação            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H             CNPJ  VARCHAR2(14)                                                                                                                                                  CNPJ do Depositante            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H        CODTRANSP   VARCHAR2(6)                                                                                                                                                Codigo Transportadora            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H    CLASSIFICACAO  VARCHAR2(10)                                                                                                                                                Classificacao Veiculo            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H            PLACA   VARCHAR2(8)                                                                                                                                                                Placa            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H        MOTORISTA  VARCHAR2(30)                                                                                                                                                            Motorista            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H       QTDEVOLUME   VARCHAR2(3)                                                                                                                                                          Qtde Volume            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H             PESO   VARCHAR2(9)                                                                                                                                                                 Peso            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H  TIPORECEBIMENTO   VARCHAR2(1)                                                                                                                                                  Tipo de Recebimento            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H           STATUS   VARCHAR2(1) Determina se o status da linha de registro, podendo o status definir se houve integração, se houve erro na tentativa de integração ou se está aguardando integração.            OPERACIONAL                        NaN
PCINT_ENVIO_OR_H       OBSERVACAO VARCHAR2(500)                                                                                                       Observação a ser gravada quando a integração resultar em erro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*