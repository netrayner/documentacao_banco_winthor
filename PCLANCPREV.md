# 📊 Tabela: PCLANCPREV

### Estrutura de Colunas e Restrições

    Tabela       Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLANCPREV  NUMLANCPREV NUMBER(10,0)                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLANCPREV     CODCONTA NUMBER(10,0)                               NaN            OPERACIONAL                        NaN
PCLANCPREV    CODFILIAL  VARCHAR2(2)                               NaN            OPERACIONAL                        NaN
PCLANCPREV       VLPREV NUMBER(12,2)                               NaN            OPERACIONAL                        NaN
PCLANCPREV          DIA  NUMBER(2,0)                               NaN            OPERACIONAL                        NaN
PCLANCPREV    HISTORICO VARCHAR2(40)                               NaN            OPERACIONAL                        NaN
PCLANCPREV   HISTORICO2 VARCHAR2(40)                               NaN            OPERACIONAL                        NaN
PCLANCPREV TIPOPARCEIRO  VARCHAR2(1)   Tipo do parceiro do lançamento.            OPERACIONAL                        NaN
PCLANCPREV  CODPARCEIRO  NUMBER(8,0) Código do parceiro do lançamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*