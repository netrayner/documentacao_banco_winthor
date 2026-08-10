# 📊 Tabela: PCINT_CONTROLEAVARIA

### Estrutura de Colunas e Restrições

              Tabela           Coluna  Tipo/Tamanho                                                                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINT_CONTROLEAVARIA  CNPJDEPOSITANTE  VARCHAR2(20)                                                                                                                            CNPJ do depositante do produto            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA       CODPRODUTO  VARCHAR2(20)                                                                                                                                         Codigo do produto            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA          PRODUTO  VARCHAR2(80)                                                                                                                                      Descrição do produto            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA            BARRA  VARCHAR2(32)                                                                                                                   Código de barra da embalagem do produto            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA           ESTADO   VARCHAR2(1)                                                                                                   Estado do produto. D - Danificado, T - Truncado/Vencido            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA             QTDE  NUMBER(12,0)                                                                                                                          Quantidade do controle de avaria            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA       NUMEROLOTE  VARCHAR2(20)                                                                                                                          Identificador do lote do produto            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA       DTVALIDADE          DATE                                                                                                                                  Data de validade do lote            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA     DTFABRICACAO          DATE                                                                                                                                Data de fabricação do lote            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA IDCONTROLEAVARIA  NUMBER(12,0)                                                                                                                         Indica o id do controle de avaria            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA        TIPOMOVTO   VARCHAR2(1)                                                                                                     Indica o tipo da movimentacao. E - Entrada, S - Saida            OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA           STATUS   VARCHAR2(1) Determina se o status da linha de registro, podendo o status definir se houve integração, se houve erro na tentativa de integração ou se está aguardando             OPERACIONAL                        NaN
PCINT_CONTROLEAVARIA       OBSERVACAO VARCHAR2(500)                                                                                          Observação a ser gravada quando a integração resultar em erro.              OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*