# 📊 Tabela: PCCODFABRICA

### Estrutura de Colunas e Restrições

      Tabela          Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCODFABRICA         CODPROD   NUMBER(6,0)                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCODFABRICA       CODFORNEC   NUMBER(6,0)                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCODFABRICA          CODFAB  VARCHAR2(30)                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCODFABRICA       TIPOFATOR   VARCHAR2(1)                          NaN            OPERACIONAL                        NaN
PCCODFABRICA FATORAUTOMATICO   VARCHAR2(1) Se é fator automático ou não            OPERACIONAL                        NaN
PCCODFABRICA           FATOR NUMBER(22,15)                          NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*