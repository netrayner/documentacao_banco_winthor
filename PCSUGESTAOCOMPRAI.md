# 📊 Tabela: PCSUGESTAOCOMPRAI

### Estrutura de Colunas e Restrições

           Tabela                  Coluna  Tipo/Tamanho                                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUGESTAOCOMPRAI             NUMSUGESTAO  NUMBER(10,0)                                                                                O número da sugestão gerada.    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOCOMPRAI                 CODPROD   NUMBER(9,0)                                                          Código do produto para qual foi gerada a sugestão.    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOCOMPRAI              QTSUGERIDA  NUMBER(18,6)                                                                            Quantidade gerada pela sugestão.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI                QTPEDIDO  NUMBER(18,6)                                                                                Quantidade gerada no pedido.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI                  NUMPED  NUMBER(10,0)                                                         Número do pedido de compra gerado no processamento.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI                     OBS VARCHAR2(200) Observação será o campo onde será gravado o motivo de não geração do pedido de compra para o item sugerido.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI                  STATUS   VARCHAR2(1)                                  "Status da sugestão G - Gerado S - Sugerido  C - Cancelado P - Pendente ".            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI CODUSUARIOPROCESSAMENTO   NUMBER(8,0)                                        Código o usuário responsável pelo processamento do pedido de compra.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI       DATAPROCESSAMENTO          DATE                                                        Data do processamento e geração do pedido de compra.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI  CODUSUARIOCANCELAMENTO   NUMBER(8,0)                                                  Código do usuário responsável pelo cancelamento do pedido.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI      PCOMPRALIQSUGERIDO  NUMBER(18,6)                                                                                      Preço Compra Liq. Sug.    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOCOMPRAI               LOTELICIT  VARCHAR2(10)                                                                                           Lote da licitação            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI         NUMEROITEMLICIT   NUMBER(9,0)                                                                                       Número item licitação            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI        PERCICMSDIFERIDO  NUMBER(12,4)                                                                                                         NaN            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI             PERCREDICMS  NUMBER(12,4)                                                                                                         NaN            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI                  PERICM  NUMBER(12,4)                                                                                                         NaN            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI              PERCICMRED  NUMBER(12,4)                                                                                                         NaN            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAI               PESOLIQDI  NUMBER(12,6)                                                                                                         NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*