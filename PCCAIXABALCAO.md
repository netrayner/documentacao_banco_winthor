# 📊 Tabela: PCCAIXABALCAO

### Estrutura de Colunas e Restrições

       Tabela          Coluna   Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCAIXABALCAO          NUMSEQ   NUMBER(12,0)          Número sequencial dos registros, chave da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCCAIXABALCAO       CODFILIAL    VARCHAR2(2)                                          Código da filial.            OPERACIONAL                        NaN
PCCAIXABALCAO         DTFECHA           DATE                                        Data do fechamento.            OPERACIONAL                        NaN
PCCAIXABALCAO       DTINICIAL           DATE                                   Data inicial do período.            OPERACIONAL                        NaN
PCCAIXABALCAO         DTFINAL           DATE                                     Data final do período.            OPERACIONAL                        NaN
PCCAIXABALCAO CODFUNCCHECKOUT    NUMBER(8,0)             Código do funcionário do checkout (se houver).            OPERACIONAL                        NaN
PCCAIXABALCAO     NUMCHECKOUT    NUMBER(8,0)                            Número do checkout (se houver).            OPERACIONAL                        NaN
PCCAIXABALCAO         CODFUNC    NUMBER(8,0)            Código do funcionário que efetuou o fechamento.            OPERACIONAL                        NaN
PCCAIXABALCAO       CODROTINA    NUMBER(6,0)                                          Código da rotina.            OPERACIONAL                        NaN
PCCAIXABALCAO     CODCOBBANCO    VARCHAR2(4)                              Código do caixa (tesouraria).            OPERACIONAL                        NaN
PCCAIXABALCAO   FAIXANUMTRANS VARCHAR2(2000) Faixa de números de transação da tesouraria do fechamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*