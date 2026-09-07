# 📊 Tabela: PCPEDIFILHO

### Estrutura de Colunas e Restrições

     Tabela       Coluna Tipo/Tamanho     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIFILHO       NUMPED NUMBER(10,0)        Número do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFILHO      CODPROD  NUMBER(6,0)       Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFILHO       NUMSEQ NUMBER(20,0)     Número de sequencia    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFILHO CODPRODFILHO  NUMBER(6,0) Código do produto filho    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFILHO         QTDE NUMBER(20,6)        Qtde. do produto            OPERACIONAL                        NaN
PCPEDIFILHO   QTSEPARADA NUMBER(20,6)          Qtde. separada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*