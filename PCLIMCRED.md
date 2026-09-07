# 📊 Tabela: PCLIMCRED

### Estrutura de Colunas e Restrições

   Tabela      Coluna Tipo/Tamanho                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLIMCRED      CODIGO  NUMBER(6,0)                                                   Indica o código do lançamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCLIMCRED     CODDCLI  NUMBER(6,0)                                                      Indica o código do cliente.            OPERACIONAL                        NaN
PCLIMCRED   DESCRICAO VARCHAR2(30)                                              Indica a descrição da sazonalidade.            OPERACIONAL                        NaN
PCLIMCRED    DTINICIO         DATE                                                         Indica a data de inicio.            OPERACIONAL                        NaN
PCLIMCRED       DTFIM         DATE                                                             Indica a data final.            OPERACIONAL                        NaN
PCLIMCRED PERCAUMENTO  NUMBER(7,3)                                                  Indica o percentual de aumento.            OPERACIONAL                        NaN
PCLIMCRED     CODUSUR  NUMBER(4,0)                                                          Indica o código do RCA.            OPERACIONAL                        NaN
PCLIMCRED       VALOR NUMBER(18,6) Valor para calcular o percentual de aumento referente a sazonalidade de crédito.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*