# 📊 Tabela: PCMOVIMPOSTOS

### Estrutura de Colunas e Restrições

       Tabela               Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVIMPOSTOS        NUMTRANSVENDA NUMBER(10,0)    Número da transação de venda.            OPERACIONAL                        NaN
PCMOVIMPOSTOS              CODPROD  NUMBER(6,0)               Código do produto.            OPERACIONAL                        NaN
PCMOVIMPOSTOS               NUMSEQ NUMBER(20,0)  Número de sequência do produto.            OPERACIONAL                        NaN
PCMOVIMPOSTOS          NUMTRANSENT NUMBER(10,0)  Número da transação de entrada.            OPERACIONAL                        NaN
PCMOVIMPOSTOS PERCICMSCOMPLEMENTAR  NUMBER(8,4) Percentual de ICMS complementar.            OPERACIONAL                        NaN
PCMOVIMPOSTOS   VLICMSCOMPLEMENTAR NUMBER(18,6)      Valor do ICMS complementar.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*