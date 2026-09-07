# 📊 Tabela: PCBENSMANUTENCAO

### Estrutura de Colunas e Restrições

          Tabela              Coluna  Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENSMANUTENCAO       CODMANUTENCAO   NUMBER(6,0)                                               Indica o código da manutenção.    CHAVE PRIMÁRIA (PK)                        NaN
PCBENSMANUTENCAO      DESCMANUTENCAO VARCHAR2(100)                                               Indica a descricao manutenção.            OPERACIONAL                        NaN
PCBENSMANUTENCAO           CODFILIAL   VARCHAR2(2)                                                   Indica o código da filial.            OPERACIONAL                        NaN
PCBENSMANUTENCAO        NUMTRANSACAO  NUMBER(10,0)                                                Indica o número da transação.            OPERACIONAL                        NaN
PCBENSMANUTENCAO       TIPOTRANSACAO   VARCHAR2(2)                                                  Indica o tipo da transação.            OPERACIONAL                        NaN
PCBENSMANUTENCAO             CODPROD   NUMBER(6,0)                                                      Indica o código do bem.            OPERACIONAL                        NaN
PCBENSMANUTENCAO     LOCALMANUTENCAO  VARCHAR2(80)                                                Indica o local da manutenção.            OPERACIONAL                        NaN
PCBENSMANUTENCAO      RESPMANUTENCAO  VARCHAR2(40)                                        Indica o responsavel pela manutenção.            OPERACIONAL                        NaN
PCBENSMANUTENCAO   SUSPBEMMANUTENCAO   VARCHAR2(1)                                 Indica se suspende bem durante a manutenção.            OPERACIONAL                        NaN
PCBENSMANUTENCAO           DATASAIDA          DATE                                      Indica a data da saida para manutenção.            OPERACIONAL                        NaN
PCBENSMANUTENCAO     DATAPREVRETORNO          DATE                          Indica a data da previsao de retorno da manutenção.            OPERACIONAL                        NaN
PCBENSMANUTENCAO         DATARETORNO          DATE                                      Indica a data do retorno da manutenção.            OPERACIONAL                        NaN
PCBENSMANUTENCAO     NUMORDEMSERVICO  VARCHAR2(20)                                         Indica o número da ordem de serviço.            OPERACIONAL                        NaN
PCBENSMANUTENCAO SEQBENSPATRIMONIAIS  NUMBER(10,0)                                            Sequência do bem individualizado.            OPERACIONAL                        NaN
PCBENSMANUTENCAO        CODSUSPENSAO   NUMBER(6,0)                                                Indica o código da suspensão.            OPERACIONAL                        NaN
PCBENSMANUTENCAO        ROTINAINSERT VARCHAR2(100)                 Registra o código de rotina e versão que inseriu o registro.            OPERACIONAL                        NaN
PCBENSMANUTENCAO        ROTINAUPDATE VARCHAR2(100) Registra o código de rotina e versão que fez a ultima alteração no registro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*