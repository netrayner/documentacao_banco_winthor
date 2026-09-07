# 📊 Tabela: PCBENSSUSPENSOS

### Estrutura de Colunas e Restrições

         Tabela              Coluna  Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENSSUSPENSOS        CODSUSPENSAO   NUMBER(6,0)                                                Indica o código da suspensão.    CHAVE PRIMÁRIA (PK)                        NaN
PCBENSSUSPENSOS           CODFILIAL   VARCHAR2(2)                                                   Indica o codigo da filial.            OPERACIONAL                        NaN
PCBENSSUSPENSOS        NUMTRANSACAO  NUMBER(10,0)                                                Indica o numero da transação.            OPERACIONAL                        NaN
PCBENSSUSPENSOS       TIPOTRANSACAO   VARCHAR2(2)                                                  Indica o tipo da transação.            OPERACIONAL                        NaN
PCBENSSUSPENSOS             CODPROD   NUMBER(6,0)                                                      Indica o codigo do bem.            OPERACIONAL                        NaN
PCBENSSUSPENSOS       TIPOSUSPENSAO   VARCHAR2(2)                                      Indica qual o tipo da suspensão do bem.            OPERACIONAL                        NaN
PCBENSSUSPENSOS         DATAINICIAL          DATE                                                       Indica a data inicial.            OPERACIONAL                        NaN
PCBENSSUSPENSOS           DATAFINAL          DATE                                                         Indica a data final.            OPERACIONAL                        NaN
PCBENSSUSPENSOS GERADOPORMANUTENCAO   VARCHAR2(1)                                     Suspensão gerada por manutenção de bens.            OPERACIONAL                        NaN
PCBENSSUSPENSOS SEQBENSPATRIMONIAIS  NUMBER(10,0)                                            Sequência do bem individualizado.            OPERACIONAL                        NaN
PCBENSSUSPENSOS        ROTINAINSERT VARCHAR2(100)                 Registra o código de rotina e versão que inseriu o registro.            OPERACIONAL                        NaN
PCBENSSUSPENSOS        ROTINAUPDATE VARCHAR2(100) Registra o código de rotina e versão que fez a ultima alteração no registro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*