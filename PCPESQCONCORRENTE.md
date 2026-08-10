# 📊 Tabela: PCPESQCONCORRENTE

### Estrutura de Colunas e Restrições

           Tabela       Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPESQCONCORRENTE      CODPESQ  NUMBER(6,0)             Código da pesquisa.    CHAVE PRIMÁRIA (PK)                        NaN
PCPESQCONCORRENTE    CODFILIAL  VARCHAR2(2)               Código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCPESQCONCORRENTE    DTCRIACAO         DATE    Data de criação da pesquisa.            OPERACIONAL                        NaN
PCPESQCONCORRENTE      CODPROD  NUMBER(6,0)  Código do produtos pesquisado.    CHAVE PRIMÁRIA (PK)                        NaN
PCPESQCONCORRENTE      CODCONC  VARCHAR2(4)          Código do concorrente.    CHAVE PRIMÁRIA (PK)                        NaN
PCPESQCONCORRENTE DTREALIZACAO         DATE Data de realização da pesquisa.            OPERACIONAL                        NaN
PCPESQCONCORRENTE       PVENDA NUMBER(18,6)                 Preço de venda.            OPERACIONAL                        NaN
PCPESQCONCORRENTE  CODAUXILIAR NUMBER(20,0)    Código de barras do produto.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*