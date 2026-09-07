# 📊 Tabela: PCVINCULOPEDIDOMATCON

### Estrutura de Colunas e Restrições

               Tabela      Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVINCULOPEDIDOMATCON   IDVINCULO VARCHAR2(50)     Identificador do vínculo, utilizado o valor do PCPEDC.NUMPEDHUBE     CHAVE PRIMÁRIA (PK)                        NaN
PCVINCULOPEDIDOMATCON   NUMPEDTV7 NUMBER(10,0)                                  Número do pedido TV7 gerado pela api            OPERACIONAL                        NaN
PCVINCULOPEDIDOMATCON   NUMPEDTV8 NUMBER(10,0) Número do pedido gerado offline pelo servidor de faturamento - varejo            OPERACIONAL                        NaN
PCVINCULOPEDIDOMATCON DTPEDIDOTV7         DATE                                    Data do pedido TV7 gerado pela Api            OPERACIONAL                        NaN
PCVINCULOPEDIDOMATCON DTPEDIDOTV8         DATE   Data do pedido gerado offline pelo servidor de faturamento - varejo            OPERACIONAL                        NaN
PCVINCULOPEDIDOMATCON        DATA         DATE                                            Data do registro na tabela            OPERACIONAL                        NaN
PCVINCULOPEDIDOMATCON   VINCULADO  VARCHAR2(1)     Armazena a informação se houve ou não vínculo entre o TV7 e o TV8            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*