# 📊 Tabela: PCCENTRONOTIFICDOCFISCAL

### Estrutura de Colunas e Restrições

                  Tabela          Coluna   Tipo/Tamanho                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCENTRONOTIFICDOCFISCAL  CODNOTIFICACAO   NUMBER(10,0)                                                                       Sequencial do registro na tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCCENTRONOTIFICDOCFISCAL TIPONOTIFICACAO    VARCHAR2(8) Identificador do tipo da notificação (warning(amarelo), danger=(vermelho), success(verde), info(azul))            OPERACIONAL                        NaN
PCCENTRONOTIFICDOCFISCAL     NOTIFICACAO VARCHAR2(1000)                                                                                   Texto da notificação            OPERACIONAL                        NaN
PCCENTRONOTIFICDOCFISCAL  TEXTOADICIONAL           CLOB                                                                          Texto adicional a notificação            OPERACIONAL                        NaN
PCCENTRONOTIFICDOCFISCAL     VISUALIZADO    VARCHAR2(1)                                                                      Marca a mensagem como visualizada            OPERACIONAL                        NaN
PCCENTRONOTIFICDOCFISCAL DATANOTIFICACAO           DATE                                                                                    Data da notificação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*