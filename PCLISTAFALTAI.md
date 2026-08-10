# 📊 Tabela: PCLISTAFALTAI

### Estrutura de Colunas e Restrições

       Tabela    Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLISTAFALTAI  NUMLISTA  NUMBER(6,0)        Numero da lista de compras    CHAVE PRIMÁRIA (PK)              PCLISTAFALTAC
PCLISTAFALTAI CODFILIAL  VARCHAR2(2)                  Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCLISTAFALTAI   CODPROD  NUMBER(6,0)                 Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCLISTAFALTAI    NUMPED NUMBER(10,0)                  Número do pedido            OPERACIONAL                        NaN
PCLISTAFALTAI    NUMSEQ  NUMBER(6,0) Número da sequencia de lançamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*