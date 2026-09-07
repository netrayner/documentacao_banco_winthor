# 📊 Tabela: PCCAMPANHAR

### Estrutura de Colunas e Restrições

     Tabela             Coluna Tipo/Tamanho                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCAMPANHAR        CODCAMPANHA NUMBER(10,0)                                                                      Indica o código da campanha.    CHAVE PRIMÁRIA (PK)                        NaN
PCCAMPANHAR            CODUSUR  NUMBER(4,0)                                                               Indica o código do RCA da campanha.    CHAVE PRIMÁRIA (PK)                        NaN
PCCAMPANHAR          CODSUPERV  NUMBER(4,0)                                                 Indica o código do Supervisor do RCA da campanha.            OPERACIONAL                        NaN
PCCAMPANHAR           METAQTDE  NUMBER(6,0)                                                              Indica a meta em quantidade por RCA.            OPERACIONAL                        NaN
PCCAMPANHAR          METAVALOR NUMBER(18,6)                                                                   Indica a meta em valor por RCA.            OPERACIONAL                        NaN
PCCAMPANHAR      METAQTPOSITIV  NUMBER(6,0)                                      Indica a meta em quantidade de clientes positivados por RCA.            OPERACIONAL                        NaN
PCCAMPANHAR    METAPERCPOSITIV  NUMBER(6,2)                                      Indica a meta em percentual de clientes positivados por RCA.            OPERACIONAL                        NaN
PCCAMPANHAR QTMIXMINIMOPOSITIV  NUMBER(6,0)                 Indica a quantidade do mix mínimo a ser vendido para considerar como positivação.            OPERACIONAL                        NaN
PCCAMPANHAR        QTCLIATIVOS  NUMBER(6,0)                         Indica a quantidade de clientes ativos por RCA no fechamento da campanha.            OPERACIONAL                        NaN
PCCAMPANHAR   QTCLIPOSITIVADOS  NUMBER(6,0)                    Indica a quantidade de clientes positivados por RCA no fechamento da campanha.            OPERACIONAL                        NaN
PCCAMPANHAR     QTVENDAPRODRCA NUMBER(14,4) Indica a quantidade total vendida de cada produto da campanha pelo RCA no fechamento da campanha.            OPERACIONAL                        NaN
PCCAMPANHAR     VLVENDAPRODRCA NUMBER(18,6)      Indica o valor total vendido de cada produto da campanha pelo RCA no fechamento da campanha.            OPERACIONAL                        NaN
PCCAMPANHAR        VLPREMIACAO NUMBER(18,6)                          Indica o valor total da premiação paga ao RCA no fechamento da campanha.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*