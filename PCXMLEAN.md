# 📊 Tabela: PCXMLEAN

### Estrutura de Colunas e Restrições

  Tabela          Coluna  Tipo/Tamanho   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCXMLEAN       CODFILIAL   VARCHAR2(2)         Código filial    CHAVE PRIMÁRIA (PK)                        NaN
PCXMLEAN       CODFORNEC   NUMBER(6,0) Código do fornecedor     CHAVE PRIMÁRIA (PK)                        NaN
PCXMLEAN         CODPROD   NUMBER(6,0)        Código produto    CHAVE PRIMÁRIA (PK)                        NaN
PCXMLEAN          EANXML  VARCHAR2(20)     Codigo EAN do xml    CHAVE PRIMÁRIA (PK)                        NaN
PCXMLEAN FATORAUTOMATICO   VARCHAR2(1)      Fator automatico            OPERACIONAL                        NaN
PCXMLEAN       TIPOFATOR   VARCHAR2(1)         Tipo do Fator            OPERACIONAL                        NaN
PCXMLEAN           FATOR NUMBER(22,15)    Fato de conversao             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*