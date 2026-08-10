# 📊 Tabela: PCDESDRECEBIMENTOFV

### Estrutura de Colunas e Restrições

             Tabela                        Coluna Tipo/Tamanho                                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESDRECEBIMENTOFV         NUMTRANSVENDA_PCPREST NUMBER(10,0)                                                                      Número transação de venda do título no contas a receber            OPERACIONAL                        NaN
PCDESDRECEBIMENTOFV                 PREST_PCPREST  VARCHAR2(2)                                                                                      Prestação do título no contas a receber            OPERACIONAL                        NaN
PCDESDRECEBIMENTOFV NUMTRANSVENDA_PCRECEBIMENTOFV NUMBER(10,0)                                                                  Número transação de venda no recebimento do força de vendas            OPERACIONAL                        NaN
PCDESDRECEBIMENTOFV         PREST_PCRECEBIMENTOFV  VARCHAR2(2)                                                                        Prestação do título no recebimento do força de vendas            OPERACIONAL                        NaN
PCDESDRECEBIMENTOFV         DESDOBRAMENTOEFETUADO  VARCHAR2(1)                                                           INDICA SE O DESDOBRAMENTO FOI APLICADO NA PCPREST (S = SIM, N=NAO)            OPERACIONAL                        NaN
PCDESDRECEBIMENTOFV      SEQUENCIAL_DESDOBRAMENTO  NUMBER(8,0) CODIGO DE IDENTICAÇÃO (SEQUENCIAL) DA OPERAÇÃO, SE FOI ENVOLVIDO VARIOS TITULOS, TODOS ELES DEVEM TER O MESMO IDENTIFICADOR.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*