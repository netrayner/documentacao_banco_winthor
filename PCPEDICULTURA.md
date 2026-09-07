# 📊 Tabela: PCPEDICULTURA

### Estrutura de Colunas e Restrições

       Tabela      Coluna Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDICULTURA      NUMPED NUMBER(10,0) Número do pedido no winthor    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICULTURA     CODPROD  NUMBER(6,0)           Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICULTURA      NUMSEQ NUMBER(20,0)         Número da Sequência    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICULTURA  QUANTIDADE NUMBER(20,6)                  Quantidade            OPERACIONAL                        NaN
PCPEDICULTURA CODAUXILIAR NUMBER(20,0)             Código Auxiliar            OPERACIONAL                        NaN
PCPEDICULTURA  CODCULTURA  NUMBER(4,0)           Código da Cultura    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*