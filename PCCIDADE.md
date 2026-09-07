# 📊 Tabela: PCCIDADE

### Estrutura de Colunas e Restrições

  Tabela             Coluna Tipo/Tamanho                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCIDADE          CODCIDADE  NUMBER(6,0)                                                                              NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCIDADE         NOMECIDADE VARCHAR2(80)                                                                              NaN            OPERACIONAL                        NaN
PCCIDADE            CODIBGE NUMBER(10,0)                                                                              NaN            OPERACIONAL                        NaN
PCCIDADE                 UF  VARCHAR2(2)                                                                              NaN            OPERACIONAL                        NaN
PCCIDADE          POPULACAO  NUMBER(8,0)                                         Indica o numero de habitantes da cidade.            OPERACIONAL                        NaN
PCCIDADE     CODMUNESTADUAL  NUMBER(8,0)                                          Indica o código do município no estado.            OPERACIONAL                        NaN
PCCIDADE UTILIZAFRETETRANSP  VARCHAR2(1) Identifica se irá utilizar o o processo de frete de transportadora para a cidade            OPERACIONAL                        NaN
PCCIDADE        CODMUNSIAFI NUMBER(10,0)                                                           Código Municipio SIAFI            OPERACIONAL                        NaN
PCCIDADE           LATITUDE VARCHAR2(20)                                                    Latitude geografica da cidade            OPERACIONAL                        NaN
PCCIDADE          LONGITUDE VARCHAR2(20)                                                   Longitude geografica da cidade            OPERACIONAL                        NaN
PCCIDADE         DTMXSALTER         DATE                                                                              NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*