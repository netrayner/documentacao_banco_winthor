# 📊 Tabela: PCFORMAPGTOPEDIDOFVMANIF

### Estrutura de Colunas e Restrições

                  Tabela         Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMAPGTOPEDIDOFVMANIF      NUMPEDRCA NUMBER(10,0)                                        Indica o número do pedido            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF        CODUSUR NUMBER(10,0)                                      Indica o código do vendedor            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF     DTINCLUSAO         DATE                                       Data de inclusão do pedido            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF         CODCOB  VARCHAR2(4)                                                Indica a cobrança            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF       CODPLPAG  NUMBER(4,0)            Indica o plano de pagamento para determinada cobrança            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF         DTVENC         DATE                                      Indica a data de vencimento            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF          VALOR NUMBER(18,6)                                   Indica o valor para a cobrança            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF TIPOINTEGRACAO  NUMBER(4,0)                                    Indica o número de integração            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF CNPJCREDCARTAO VARCHAR2(20)                  Indica o CNPJ da operadora do cartão de crédito            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF NUMAUTORIZACAO VARCHAR2(30) Indica o número de autorização da operadora do cartão de crédito            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF       VLRTROCO NUMBER(18,6)                          Indica o valor de troco para a cobrança            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDOFVMANIF      VLENTRADA NUMBER(16,3)              Indica o valor da entrada para a forma de pagamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*