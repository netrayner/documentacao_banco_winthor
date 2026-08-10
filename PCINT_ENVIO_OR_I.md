# 📊 Tabela: PCINT_ENVIO_OR_I

### Estrutura de Colunas e Restrições

          Tabela           Coluna  Tipo/Tamanho                                                                                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINT_ENVIO_OR_I ORDEMRECEBIMENTO   NUMBER(7,0)                                                                                                                                                         NUMERO DA OR            OPERACIONAL                        NaN
PCINT_ENVIO_OR_I    CODIGOPRODUTO  VARCHAR2(20)                                                                                                                                                       Codigo Produto            OPERACIONAL                        NaN
PCINT_ENVIO_OR_I             QTDE   VARCHAR2(6)                                                                                                                                                           Quantidade            OPERACIONAL                        NaN
PCINT_ENVIO_OR_I       NUMEROLOTE  VARCHAR2(20)                                                                                                                                     Identificador do lote do produto            OPERACIONAL                        NaN
PCINT_ENVIO_OR_I           ESTADO  VARCHAR2(15)                                                                                                                 Estado do Produto. NORMAL, DANIFICADO e T ¿ TRUNCADO            OPERACIONAL                        NaN
PCINT_ENVIO_OR_I           STATUS   VARCHAR2(1) Determina se o status da linha de registro, podendo o status definir se houve integração, se houve erro na tentativa de integração ou se está aguardando integração.            OPERACIONAL                        NaN
PCINT_ENVIO_OR_I       OBSERVACAO VARCHAR2(500)                                                                                                       Observação a ser gravada quando a integração resultar em erro.            OPERACIONAL                        NaN
PCINT_ENVIO_OR_I       DTVALIDADE          DATE                                                                                                                                             Data de validade do lote            OPERACIONAL                        NaN
PCINT_ENVIO_OR_I     DTFABRICACAO          DATE                                                                                                                                           Data de fabricação do lote            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*