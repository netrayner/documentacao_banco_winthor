# 📊 Tabela: PCPARAMSALDO

### Estrutura de Colunas e Restrições

      Tabela         Coluna Tipo/Tamanho                                                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMSALDO        DESCMAX NUMBER(12,6) Percentual do desconto máximo permitido, porém este campo somente é utilizado na fórmula de cálculo do saldo da conta corrente do RCA.            OPERACIONAL                        NaN
PCPARAMSALDO     QTMINITENS  NUMBER(4,0)                             Quantidade mínima de itens que um pedido deverá ter, para que seja permitido informar desconto financeiro.            OPERACIONAL                        NaN
PCPARAMSALDO           FIXO NUMBER(20,8)                                                          Valor fixo utilizado na fórmula de cálculo do saldo da conta corrente do RCA.            OPERACIONAL                        NaN
PCPARAMSALDO PERCMAXDESCFIN NUMBER(12,6)                                                  Percentual máximo de desconto financeiro que poderá ser informado no pedido de venda.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*