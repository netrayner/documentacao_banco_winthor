# 📊 Tabela: PCGRUPOCOMBOCLIC

### Estrutura de Colunas e Restrições

          Tabela     Coluna  Tipo/Tamanho                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGRUPOCOMBOCLIC     CODIGO  NUMBER(10,0)                                                                                 Codigo sequencial    CHAVE PRIMÁRIA (PK)                        NaN
PCGRUPOCOMBOCLIC       TIPO   VARCHAR2(1)                                                               Defini se o tipo da campanha L OU C            OPERACIONAL                        NaN
PCGRUPOCOMBOCLIC    DATAINI          DATE                                                                          Data inicial da vigência            OPERACIONAL                        NaN
PCGRUPOCOMBOCLIC    DATAFIM          DATE                                                                            Data final da vigência            OPERACIONAL                        NaN
PCGRUPOCOMBOCLIC  CODFILIAL   VARCHAR2(2)                                                                      Codigo da filial da campanha            OPERACIONAL                        NaN
PCGRUPOCOMBOCLIC  DESCRICAO VARCHAR2(400)                                                                             Descroção da campanha            OPERACIONAL                        NaN
PCGRUPOCOMBOCLIC QTMINCOMBO   NUMBER(6,0) Indica a quantidade mínima de combos que devem ser vendidos para a campanha poder ser contemplada            OPERACIONAL                        NaN
PCGRUPOCOMBOCLIC DTMXSALTER          DATE                                                                                               NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*