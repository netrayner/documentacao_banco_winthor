# 📊 Tabela: PCBLOQUEIO

### Estrutura de Colunas e Restrições

    Tabela            Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBLOQUEIO    CODMOTBLOQUEIO  NUMBER(8,0)                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCBLOQUEIO     DTMOTBLOQUEIO         DATE                                                       NaN            OPERACIONAL                        NaN
PCBLOQUEIO           CODPROD  NUMBER(6,0)                                                       NaN            OPERACIONAL                        NaN
PCBLOQUEIO         CONDVENDA  NUMBER(5,0)                                                       NaN            OPERACIONAL                        NaN
PCBLOQUEIO          CODPRACA  NUMBER(4,0)                                                       NaN            OPERACIONAL                        NaN
PCBLOQUEIO          CODPLPAG  NUMBER(4,0)                                                       NaN            OPERACIONAL                        NaN
PCBLOQUEIO            CODCLI  NUMBER(6,0)                                                       NaN            OPERACIONAL                        NaN
PCBLOQUEIO         CODMOTIVO  NUMBER(6,0) Indica o código do motivo do bloqueio do pedido de venda.            OPERACIONAL                        NaN
PCBLOQUEIO            CODCOB  VARCHAR2(4)                     Indica o código da cobrança de venda.            OPERACIONAL                        NaN
PCBLOQUEIO CLIENTEMONITORADO  VARCHAR2(1)                              Indica o cliente monitorado.            OPERACIONAL                        NaN
PCBLOQUEIO         ORIGEMPED  VARCHAR2(1)                                   Indica a origem pedido.            OPERACIONAL                        NaN
PCBLOQUEIO     FRETEDESPACHO  VARCHAR2(1)                          Indica bloque por tipo de frete.            OPERACIONAL                        NaN
PCBLOQUEIO     MATRICULAEMPR  NUMBER(8,0)                  Código do funcionário emitente do pedido            OPERACIONAL                        NaN
PCBLOQUEIO       VLMAXPEDIDO NUMBER(18,6)            Campo para restringir valor maximo de pedidos.            OPERACIONAL                        NaN
PCBLOQUEIO          VLMAXPED NUMBER(18,6)                        Valor Maximo para pedidos de venda            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*