# 📊 Tabela: PCBENEFICAGRUPADOR

### Estrutura de Colunas e Restrições

            Tabela            Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICAGRUPADOR            NUMPED NUMBER(10,0)  Número do pedido de materia prima    CHAVE PRIMÁRIA (PK)               PCBENEFICMPI
PCBENEFICAGRUPADOR           CODPROD NUMBER(10,0)    Código do produto materia prima    CHAVE PRIMÁRIA (PK)               PCBENEFICMPI
PCBENEFICAGRUPADOR            NUMSEQ  NUMBER(5,0)        Sequencial de materia prima    CHAVE PRIMÁRIA (PK)               PCBENEFICMPI
PCBENEFICAGRUPADOR CODBENEFAGRUAPADO NUMBER(10,0) Código agrupador de itens faturado    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*