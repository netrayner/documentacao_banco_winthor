# 📊 Tabela: PCSUPPLICONCILFINANCOMPRA

### Estrutura de Colunas e Restrições

                   Tabela                Coluna Tipo/Tamanho                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPPLICONCILFINANCOMPRA               BORDERO  VARCHAR2(6)                                                                                      Número do bôrdero            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA                  CNPJ VARCHAR2(14)                                                                                        CNPJ do cliente            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA         CODIGOCLIENTE  NUMBER(8,0)                                                                                      Código do cliente CHAVE ESTRANGEIRA (FK)            PCSUPPLICLIENTE
PCSUPPLICONCILFINANCOMPRA  CONFIRMACAOPAGAMENTO  NUMBER(1,0)                                    Indica se o lançamento está agendado (0) ou se será pago no dia (1)            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA         DATAPAGAMENTO         DATE                                                                              Data do pagamento da nota            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA DATAVENCIMENTOPARCELA         DATE                                                                  Data do vencimento da parcela da nota            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA                    ID  NUMBER(8,0)                                                                                        Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCSUPPLICONCILFINANCOMPRA          NUMEROCARTAO VARCHAR2(16)                                                                            Número do cartão do cliente            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA         NUMEROPARCELA  NUMBER(2,0) Número da Parcela. Caso seja efetuado o pagamento de todo o contrato, o campo será preechido com zero.            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA       NUMEROTRANSACAO VARCHAR2(14)                                                                                  Número da Nota Fiscal            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA   PAGAMENTOANTECIPADO  NUMBER(1,0)                                                                                  Pagamento antecipado?            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA      QTDTOTALPARCELAS  NUMBER(2,0)                                                                     Quantidade de Parcelas do Contrato            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA           VALORCOMPRA NUMBER(16,4)                                                                                        Valor da compra            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA         VALORDESCONTO NUMBER(16,4)                                                                                      Valor do desconto            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA         VALORIMPOSTOS NUMBER(16,4)                                                                                     Valor dos impostos            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA       VALORLANCAMENTO NUMBER(16,4)                                                                            Valor do lançamento da nota            OPERACIONAL                        NaN
PCSUPPLICONCILFINANCOMPRA          VALORPARCELA NUMBER(16,4)                                                                               Valor da parcela da nota            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*