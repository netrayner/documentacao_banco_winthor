# 📊 Tabela: PCNUMEROSERIEFV

### Estrutura de Colunas e Restrições

         Tabela            Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNUMEROSERIEFV         NUMPEDRCA NUMBER(10,0)               Define o número do pedido do RCA            OPERACIONAL                        NaN
PCNUMEROSERIEFV           CODUSUR  NUMBER(4,0)                         Define o código do RCA            OPERACIONAL                        NaN
PCNUMEROSERIEFV         CODFILIAL  VARCHAR2(2)                      Define o código da Filial            OPERACIONAL                        NaN
PCNUMEROSERIEFV            NUMPED NUMBER(10,0)                      Define o número do pedido            OPERACIONAL                        NaN
PCNUMEROSERIEFV           CODPROD  NUMBER(6,0)                     Define o código do Produto            OPERACIONAL                        NaN
PCNUMEROSERIEFV            NUMSEQ NUMBER(20,0)                     Define o número sequencial            OPERACIONAL                        NaN
PCNUMEROSERIEFV          NUMSERIE VARCHAR2(30)                       Define o número de série            OPERACIONAL                        NaN
PCNUMEROSERIEFV DTABERTURAPEDPALM         DATE Indica a data de inicio da digitação do pedido            OPERACIONAL                        NaN
PCNUMEROSERIEFV            CGCCLI VARCHAR2(18)                        Indica o CGC do cliente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*