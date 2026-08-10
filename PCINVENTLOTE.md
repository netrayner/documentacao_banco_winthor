# 📊 Tabela: PCINVENTLOTE

### Estrutura de Colunas e Restrições

      Tabela               Coluna Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINVENTLOTE            NUMINVENT  NUMBER(8,0)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTLOTE                 DATA         DATE                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE            CODFILIAL  VARCHAR2(2)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTLOTE              CODPROD  NUMBER(6,0)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTLOTE                  QT1 NUMBER(20,8)                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE                  QT2 NUMBER(20,8)                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE                  QT3 NUMBER(20,8)                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE              NUMLOTE VARCHAR2(15)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTLOTE             QTESTGER NUMBER(20,8)                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE               QTLOTE NUMBER(20,8)                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE            DATACONT1         DATE                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE            DATACONT2         DATE                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE            DATACONT3         DATE                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE         DTATUALIZADO         DATE                                                         NaN            OPERACIONAL                        NaN
PCINVENTLOTE         QTATUALIZADA NUMBER(22,2)          Indica o estoque que foi atualizado no inventário.            OPERACIONAL                        NaN
PCINVENTLOTE               DTVAL1         DATE                                          Data de Validade 1            OPERACIONAL                        NaN
PCINVENTLOTE               DTVAL2         DATE                                          Data de Validade 2            OPERACIONAL                        NaN
PCINVENTLOTE               DTVAL3         DATE                                          Data de Validade 3            OPERACIONAL                        NaN
PCINVENTLOTE           DTVALIDADE         DATE                                 Campo para data de validade            OPERACIONAL                        NaN
PCINVENTLOTE                QTEST NUMBER(22,8)                                 Estoque Contábil do produto            OPERACIONAL                        NaN
PCINVENTLOTE QTUTILIZAATUALIZACAO NUMBER(22,8)             Quantidade utilizada na atualização do estoque.            OPERACIONAL                        NaN
PCINVENTLOTE                CUSTO NUMBER(18,6)                               Custo do produto no invetário            OPERACIONAL                        NaN
PCINVENTLOTE             CODLOCAL VARCHAR2(20)                               Código do local do inventário CHAVE ESTRANGEIRA (FK)          PCLOCALINVENTARIO
PCINVENTLOTE       GERARNFENTRADA  VARCHAR2(1) Indica se foi gerada NF de entrada do inventário pela 1188.            OPERACIONAL                        NaN
PCINVENTLOTE         CODAGREGACAO VARCHAR2(20)                                Codigo agregacao do produto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*