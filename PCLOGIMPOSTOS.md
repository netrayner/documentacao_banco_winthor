# 📊 Tabela: PCLOGIMPOSTOS

### Estrutura de Colunas e Restrições

       Tabela        Coluna   Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGIMPOSTOS     SEQUENCIA   NUMBER(20,0)                   Indica o sequencial da tabela            OPERACIONAL                        NaN
PCLOGIMPOSTOS          DATA           DATE   Indica a data que foi feita a inserção do log            OPERACIONAL                        NaN
PCLOGIMPOSTOS        NUMPED   NUMBER(10,0)                       Indica o número do pedido            OPERACIONAL                        NaN
PCLOGIMPOSTOS       CODPROD    NUMBER(6,0)                      Indica o código do produto            OPERACIONAL                        NaN
PCLOGIMPOSTOS        NUMSEQ   NUMBER(20,0)         Indica o número de sequencia do produto            OPERACIONAL                        NaN
PCLOGIMPOSTOS NUMTRANSVENDA   NUMBER(20,0)           Indica o número de transação de venda            OPERACIONAL                        NaN
PCLOGIMPOSTOS        OBJETO   VARCHAR2(30) Indica qual o objeto que está armazenando o LOG            OPERACIONAL                        NaN
PCLOGIMPOSTOS     DESCRICAO VARCHAR2(4000)                           Indica o texto do log            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*