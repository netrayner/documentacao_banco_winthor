# 📊 Tabela: PCFORMAPGTOPEDIDO

### Estrutura de Colunas e Restrições

           Tabela            Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMAPGTOPEDIDO            NUMPED NUMBER(10,0)                                        Indica o número do pedido            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO            CODCOB  VARCHAR2(4)                                                Indica a cobrança            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO          CODPLPAG  NUMBER(4,0)            Indica o plano de pagamento para determinada cobrança            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO            DTVENC         DATE                                      Indica a data de vencimento            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO             VALOR NUMBER(18,6)                                   Indica o valor para a cobrança            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO    TIPOINTEGRACAO  NUMBER(4,0)                                    Indica o número de integração            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO    CNPJCREDCARTAO VARCHAR2(20)                  Indica o CNPJ da operadora do cartão de crédito            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO    NUMAUTORIZACAO VARCHAR2(30) Indica o número de autorização da operadora do cartão de crédito            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO          VLRTROCO NUMBER(18,6)                          Indica o valor de troco para a cobrança            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO CODBANDEIRACARTAO  NUMBER(6,0)                          Número da bandeira do cartão de crédito            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO         VLENTRADA NUMBER(16,3)              Indica o valor da entrada para a forma de pagamento            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO       CODCOBSEFAZ  VARCHAR2(4)                       Indica o valor da cobrança junto ao sefaz.            OPERACIONAL                        NaN
PCFORMAPGTOPEDIDO  CODMOVINSERVIVEL  NUMBER(6,0)  Código sequencial para identificação do movimento de inservível            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*