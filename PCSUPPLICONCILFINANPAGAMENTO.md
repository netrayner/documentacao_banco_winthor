# 📊 Tabela: PCSUPPLICONCILFINANPAGAMENTO

### Estrutura de Colunas e Restrições

                      Tabela          Coluna  Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPPLICONCILFINANPAGAMENTO         AGENCIA   VARCHAR2(9)           Número da agência para onde foi enviado o pagamento            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO           BANCO   VARCHAR2(3)             Número do banco para onde foi enviado o pagamento            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO         BORDERO  VARCHAR2(50)                                             Número do bôrdero            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO   CODIGOEMPRESA   VARCHAR2(2)                                  Código da empresa do cliente            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO      CODIGOLOJA   VARCHAR2(4)                                     Código da loja do cliente            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO           CONTA  VARCHAR2(20)             Número da conta para onde foi enviado o pagamento            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO   DATAPAGAMENTO          DATE                                    Data de envio do pagamento            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO          EVENTO   VARCHAR2(7)                                                Tipo de evento            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO       HISTORICO VARCHAR2(100)                   Histórico informado referente ao lançamento            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO              ID   NUMBER(8,0)                                               Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCSUPPLICONCILFINANPAGAMENTO     NOMECREDITO  VARCHAR2(60)                                       Razão social do cliente            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO           SINAL   NUMBER(2,0) Sinal que indica se o lançamento é a Débito (-) ou Crédito(+)            OPERACIONAL                        NaN
PCSUPPLICONCILFINANPAGAMENTO VALORLANCAMENTO  NUMBER(16,4)                                            Valor do pagamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*