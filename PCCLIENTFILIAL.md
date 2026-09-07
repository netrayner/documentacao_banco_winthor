# 📊 Tabela: PCCLIENTFILIAL

### Estrutura de Colunas e Restrições

        Tabela             Coluna Tipo/Tamanho                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIENTFILIAL          CODFILIAL  VARCHAR2(2)                                               Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTFILIAL             CODCLI  NUMBER(6,0)                                              Indica o código do cliente.    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTFILIAL          PERCOMCLI  NUMBER(6,2)                                     Indica o percentual de comissão RCA.            OPERACIONAL                        NaN
PCCLIENTFILIAL          PERCOMMOT  NUMBER(6,2)                               Indica o percentual de comissão motorista.            OPERACIONAL                        NaN
PCCLIENTFILIAL PERCOMFILIALBROKER  NUMBER(6,2)    Indica a comissão da Filial paga pela indústria por cliente e filial.            OPERACIONAL                        NaN
PCCLIENTFILIAL   PERCOMTERCBROKER  NUMBER(6,2) Indica a comissão de terceiros pago pela indústria por cliente e filial.            OPERACIONAL                        NaN
PCCLIENTFILIAL     PERFRETEBROKER  NUMBER(6,2) Indica a comissão de terceiros pago pela indústria por cliente e filial.            OPERACIONAL                        NaN
PCCLIENTFILIAL         PERCSEGURO NUMBER(18,6)                                                     Percentual de Seguro            OPERACIONAL                        NaN
PCCLIENTFILIAL           VLSEGURO NUMBER(18,6)                                                          Valor do Seguro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*