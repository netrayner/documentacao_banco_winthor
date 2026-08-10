# 📊 Tabela: PCREINFR2020I

### Estrutura de Colunas e Restrições

       Tabela        Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2020I            ID   NUMBER(8,0)                               Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2020I     R2020C_ID   NUMBER(8,0) Identificador do registro 2020 do cabeçalho            OPERACIONAL                        NaN
PCREINFR2020I NUMTRANSVENDA  NUMBER(22,0)                Numero de transação de venda            OPERACIONAL                        NaN
PCREINFR2020I        STATUS VARCHAR2(100)                          Status do registro            OPERACIONAL                        NaN
PCREINFR2020I   RETIFICACAO   VARCHAR2(1)        Controle de processo em retificação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*