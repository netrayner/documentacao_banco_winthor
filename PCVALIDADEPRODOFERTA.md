# 📊 Tabela: PCVALIDADEPRODOFERTA

### Estrutura de Colunas e Restrições

              Tabela      Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVALIDADEPRODOFERTA     CODPROD  NUMBER(6,0)                         Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCVALIDADEPRODOFERTA CODAUXILIAR NUMBER(16,0)                       Código da embalagem    CHAVE PRIMÁRIA (PK)                        NaN
PCVALIDADEPRODOFERTA   CODFILIAL  VARCHAR2(2)                          Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCVALIDADEPRODOFERTA NUMVALIDADE  NUMBER(2,0)           Índice da validade da embalagem    CHAVE PRIMÁRIA (PK)                        NaN
PCVALIDADEPRODOFERTA  DTVALIDADE         DATE Data de validade do produto por embalagem            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*