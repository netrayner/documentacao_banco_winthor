# 📊 Tabela: PCINT_ENVIO_INVENTARIO

### Estrutura de Colunas e Restrições

                Tabela          Coluna  Tipo/Tamanho                                                                                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINT_ENVIO_INVENTARIO CNPJDEPOSITANTE  VARCHAR2(20)                                                                                                                                       CNPJ do depositante do produto            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO           BARRA  VARCHAR2(20)                                                                                                                              Código de barra da embalagem do produto            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO          ESTADO   VARCHAR2(1)                                                                                                              Estado do produto. D - Danificado, T - Truncado/Vencido            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO      NUMEROLOTE  VARCHAR2(20)                                                                                                                                     Identificador do lote do produto            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO      DTVALIDADE          DATE                                                                                                                                             Data de validade do lote            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO    DTFABRICACAO          DATE                                                                                                                                           Data de fabricação do lote            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO          STATUS   VARCHAR2(1) Determina se o status da linha de registro, podendo o status definir se houve integração, se houve erro na tentativa de integração ou se está aguardando integração.            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO      OBSERVACAO VARCHAR2(500)                                                                                                       Observação a ser gravada quando a integração resultar em erro.            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO   CODIGOINTERNO  VARCHAR2(20)                                                                                                                                                    Codigo do produto            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO           DESCR  VARCHAR2(80)                                                                                                                                                 Descrição do Produto            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO         ESTOQUE  NUMBER(12,0)                                                                                                                                                   Estoque do sistema            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO    INVENTARIADO  NUMBER(12,0)                                                                                                                                              Quantidade Inventáriado            OPERACIONAL                        NaN
PCINT_ENVIO_INVENTARIO    IDINVENTARIO  NUMBER(12,0)                                                                                                                                          Identificação do Inventário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*