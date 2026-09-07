# 📊 Tabela: PCINT_ENVIO_OR_N

### Estrutura de Colunas e Restrições

          Tabela           Coluna  Tipo/Tamanho                                                                                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINT_ENVIO_OR_N ORDEMRECEBIMENTO   NUMBER(7,0)                                                                                                                                                         Numero da OR            OPERACIONAL                        NaN
PCINT_ENVIO_OR_N       NOTAFISCAL  VARCHAR2(20)                                                                                                                                                   Numero Nota Fiscal            OPERACIONAL                        NaN
PCINT_ENVIO_OR_N            SERIE  VARCHAR2(20)                                                                                                                                                 Serie da Nota Fiscal            OPERACIONAL                        NaN
PCINT_ENVIO_OR_N    CNPJ_EMITENTE  VARCHAR2(20)                                                                                                                                      CNPJ do Emitente da Nota Fiscal            OPERACIONAL                        NaN
PCINT_ENVIO_OR_N           STATUS   VARCHAR2(1) Determina se o status da linha de registro, podendo o status definir se houve integração, se houve erro na tentativa de integração ou se está aguardando integração.            OPERACIONAL                        NaN
PCINT_ENVIO_OR_N       OBSERVACAO VARCHAR2(500)                                                                                                       Observação a ser gravada quando a integração resultar em erro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*