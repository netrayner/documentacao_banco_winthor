# 📊 Tabela: PCPLANOCONTA

### Estrutura de Colunas e Restrições

      Tabela                   Coluna Tipo/Tamanho                                                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPLANOCONTA            CODPLANOCONTA  NUMBER(5,0)                                                                                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPLANOCONTA          NOME_PLANOCONTA VARCHAR2(50)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA                  MASCARA VARCHAR2(40)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA              NIVEL_ATIVO VARCHAR2(10)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA            NIVEL_PASSIVO VARCHAR2(10)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA            NIVEL_RECEITA VARCHAR2(10)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA            NIVEL_DESPESA VARCHAR2(10)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA              NIVEL_CUSTO VARCHAR2(10)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA               CONTALUCRO VARCHAR2(12)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA            CONTAPREJUIZO VARCHAR2(12)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA           CONTARESULTADO VARCHAR2(12)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA    TODACONTARECEBELANCTO      CHAR(1)                                                                                                                NaN            OPERACIONAL                        NaN
PCPLANOCONTA  CODCONTASINTETICAFORNEC VARCHAR2(20) Indica grupo de fornecedores no plano de contas do contábil, para fins de integração e utilização da rotina 2124.             OPERACIONAL                        NaN
PCPLANOCONTA   UTILIZA_PLANOCONTASPED  VARCHAR2(1)                                                                   Indica se utiliza o plano de contas referencial.            OPERACIONAL                        NaN
PCPLANOCONTA CODCONTASINTETICACLIENTE VARCHAR2(20)                                                                                  Indica a conta sintética cliente.            OPERACIONAL                        NaN
PCPLANOCONTA     CODCONTASINTETICARCA VARCHAR2(20)                                                                          Código da Conta Contábil Sintética do RCA            OPERACIONAL                        NaN
PCPLANOCONTA        TIPOPLANOCONTAREF  VARCHAR2(2)                                                                                   Indica o tipo do plano de contas            OPERACIONAL                        NaN
PCPLANOCONTA  UTILIZACONTAUNICAFORNEC  VARCHAR2(1)                       Determina se plano de conta utiliza uma conta para cada fornecedor ou somente uma para todos            OPERACIONAL                        NaN
PCPLANOCONTA UTILIZACONTAUNICACLIENTE  VARCHAR2(1)                          Determina se plano de conta utiliza uma conta para cada cliente ou somente uma para todos            OPERACIONAL                        NaN
PCPLANOCONTA     UTILIZACONTAUNICARCA  VARCHAR2(1)                              Determina se plano de conta utiliza uma conta para cada RCA ou somente uma para todos            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*