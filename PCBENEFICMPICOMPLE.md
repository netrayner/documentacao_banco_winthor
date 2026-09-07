# 📊 Tabela: PCBENEFICMPICOMPLE

### Estrutura de Colunas e Restrições

            Tabela        Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICMPICOMPLE CODBENEFICMPI  NUMBER(8,0)  Código da matéria prima desdobrada    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICMPICOMPLE        NUMPED NUMBER(10,0)   Número do pedido de materia prima CHAVE ESTRANGEIRA (FK)               PCBENEFICMPI
PCBENEFICMPICOMPLE       CODPROD NUMBER(10,0)             Código da materia prima CHAVE ESTRANGEIRA (FK)               PCBENEFICMPI
PCBENEFICMPICOMPLE       CODPROD NUMBER(10,0)             Código da materia prima CHAVE ESTRANGEIRA (FK)                   PCPRODUT
PCBENEFICMPICOMPLE       CODPROD NUMBER(10,0)             Código da materia prima CHAVE ESTRANGEIRA (FK)               PCBENEFICMPI
PCBENEFICMPICOMPLE       CODPROD NUMBER(10,0)             Código da materia prima CHAVE ESTRANGEIRA (FK)                   PCPRODUT
PCBENEFICMPICOMPLE        NUMSEQ  NUMBER(5,0)         Número sequencial dos itens CHAVE ESTRANGEIRA (FK)               PCBENEFICMPI
PCBENEFICMPICOMPLE      NUMPEDPA NUMBER(10,0) Número do pedido de produto acabado CHAVE ESTRANGEIRA (FK)               PCBENEFICPAI
PCBENEFICMPICOMPLE     CODPRODPA NUMBER(10,0)           Código do produto acabado CHAVE ESTRANGEIRA (FK)               PCBENEFICPAI
PCBENEFICMPICOMPLE      NUMSEQPA  NUMBER(5,0)         Número sequencial dos itens CHAVE ESTRANGEIRA (FK)               PCBENEFICPAI

---
*Documentação gerada automaticamente.*