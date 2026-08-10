# 📊 Tabela: PCMONITORDFESPRESOS

### Estrutura de Colunas e Restrições

             Tabela              Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMONITORDFESPRESOS        NUMTRANSACAO NUMBER(10,0)                      Transação do documento    CHAVE PRIMÁRIA (PK)                        NaN
PCMONITORDFESPRESOS             TIPOMOV  VARCHAR2(2)        Tipo do movimento (entrada ou saída)    CHAVE PRIMÁRIA (PK)                        NaN
PCMONITORDFESPRESOS             TIPODOC  VARCHAR2(2)              Tipo do documento (NF, CT, MD)    CHAVE PRIMÁRIA (PK)                        NaN
PCMONITORDFESPRESOS DATAULTIMAALTERACAO         DATE Data/ hora da última interação no documento            OPERACIONAL                        NaN
PCMONITORDFESPRESOS     ULTIMA_SITUACAO NUMBER(10,0)                Última situação do documento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*