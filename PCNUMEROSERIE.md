# 📊 Tabela: PCNUMEROSERIE

### Estrutura de Colunas e Restrições

       Tabela    Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNUMEROSERIE CODFILIAL  VARCHAR2(2)    Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCNUMEROSERIE   CODPROD  NUMBER(6,0)   Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCNUMEROSERIE   NUMLOTE VARCHAR2(15)      Número do lote            OPERACIONAL                        NaN
PCNUMEROSERIE  NUMSERIE VARCHAR2(60)     Número de série    CHAVE PRIMÁRIA (PK)                        NaN
PCNUMEROSERIE  BLOQUEIO  VARCHAR2(1)            Bloqueio            OPERACIONAL                        NaN
PCNUMEROSERIE    AVARIA  VARCHAR2(1)              Avaria            OPERACIONAL                        NaN
PCNUMEROSERIE RESERVADA  VARCHAR2(1)           Reservada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*