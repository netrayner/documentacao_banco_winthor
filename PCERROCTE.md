# 📊 Tabela: PCERROCTE

### Estrutura de Colunas e Restrições

   Tabela       Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCERROCTE NUMTRANSACAO NUMBER(10,0)          Número da Transação.    CHAVE PRIMÁRIA (PK)                        NaN
PCERROCTE  CODMENSAGEM NUMBER(10,0)     Código Principal do Erro.    CHAVE PRIMÁRIA (PK)                        NaN
PCERROCTE CODAUXILIAR1 NUMBER(10,0) Indica o processo com erro 1.    CHAVE PRIMÁRIA (PK)                        NaN
PCERROCTE CODAUXILIAR2 NUMBER(10,0) Indica o processo com erro 2.            OPERACIONAL                        NaN
PCERROCTE CODAUXILIAR3 NUMBER(10,0) Indica o processo com erro 3.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*