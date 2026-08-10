# 📊 Tabela: PCDESCONTORESTRICAO

### Estrutura de Colunas e Restrições

             Tabela     Coluna Tipo/Tamanho                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESCONTORESTRICAO     CODIGO NUMBER(10,0)                                                                            Indica o código da campanha de desconto.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCONTORESTRICAO       TIPO  NUMBER(2,0) Indica o tipo da restrição de desconto: 1-FILIAL, 2-REGIÃO, 3-RAMO, 4-SUPERVISOR, 5-RCA, 6-CLIENTE, 7-DISTRIBUIÇÃO.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCONTORESTRICAO    CODIGOA  VARCHAR2(4)                                                                          Indica o código alfanumérico de restrição.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCONTORESTRICAO    CODIGON NUMBER(10,0)                                                                              Indica o código numérico de restrição.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCONTORESTRICAO     SYNCFV  VARCHAR2(1)                                                                                                                 NaN            OPERACIONAL                        NaN
PCDESCONTORESTRICAO DTMXSALTER         DATE                                                                                                                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*