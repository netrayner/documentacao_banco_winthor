# 📊 Tabela: PCPEDIFVCULTURA

### Estrutura de Colunas e Restrições

         Tabela              Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIFVCULTURA           NUMPEDRCA NUMBER(10,0)          Número Pedido RCA    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFVCULTURA             CODUSUR  NUMBER(4,0)          Código do Usuário    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFVCULTURA   DTABERTURAPEDPALM         DATE       Data Abertura Pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFVCULTURA DTFECHAMENTOPEDPALM         DATE  Data Fechamento do Pedido            OPERACIONAL                        NaN
PCPEDIFVCULTURA             CODPROD  NUMBER(6,0)          Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFVCULTURA              NUMSEQ NUMBER(20,0)        Número da Sequencia    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFVCULTURA          QUANTIDADE NUMBER(20,6)                 Quantidade            OPERACIONAL                        NaN
PCPEDIFVCULTURA          CODCULTURA  NUMBER(4,0) Código da Cultura Agrícola    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFVCULTURA         CODAUXILIAR NUMBER(20,0)            Código Auxiliar            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*