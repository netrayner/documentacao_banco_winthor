# 📊 Tabela: PCRAZAOFORNEC

### Estrutura de Colunas e Restrições

       Tabela        Coluna Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRAZAOFORNEC        NUMSEQ NUMBER(12,0)                                       Indica o número de sequência.    CHAVE PRIMÁRIA (PK)                        NaN
PCRAZAOFORNEC     CODFORNEC  NUMBER(6,0)                                      Indica o código do fornecedor.            OPERACIONAL                        NaN
PCRAZAOFORNEC          DATA         DATE                                        Indica a data do lançamento.            OPERACIONAL                        NaN
PCRAZAOFORNEC     HISTORICO VARCHAR2(60)                                   Indica o historico do lançamento.            OPERACIONAL                        NaN
PCRAZAOFORNEC       NUMNOTA NUMBER(10,0)                                             Indica o número de nota            OPERACIONAL                        NaN
PCRAZAOFORNEC   NUMTRANSENT NUMBER(12,0)                                       Indica o número da transação.            OPERACIONAL                        NaN
PCRAZAOFORNEC         DUPLI  VARCHAR2(2)                               Indica o número da duplicata/percela.            OPERACIONAL                        NaN
PCRAZAOFORNEC         VALOR NUMBER(18,2)                                       Indica o valor do lançamento.            OPERACIONAL                        NaN
PCRAZAOFORNEC      VLDEBITO NUMBER(18,2)                                           Indica o valor do débito.            OPERACIONAL                        NaN
PCRAZAOFORNEC     VLCREDITO NUMBER(18,2)                                          Indica o valor do crédito.            OPERACIONAL                        NaN
PCRAZAOFORNEC          TIPO  VARCHAR2(3)                                        Indica o tipo de lançamento.            OPERACIONAL                        NaN
PCRAZAOFORNEC        RECNUM  NUMBER(8,0)                                      Numero de lançamento do título            OPERACIONAL                        NaN
PCRAZAOFORNEC FORMAAPURACAO  VARCHAR2(1) Forma de apuração dos lançamentos (P - Pagamento / C - Compensação)            OPERACIONAL                        NaN
PCRAZAOFORNEC   DATAGERACAO         DATE                  Data em que os lançamentos foram gerados na tabela            OPERACIONAL                        NaN
PCRAZAOFORNEC     CODFILIAL  VARCHAR2(2)                                          Indica o código da filial.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*