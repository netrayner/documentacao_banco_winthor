# 📊 Tabela: PCMONITORBANCOSESSAOSQL

### Estrutura de Colunas e Restrições

                 Tabela      Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMONITORBANCOSESSAOSQL   CODSESSAO  NUMBER(10,0)    Identificador do monitaramento CHAVE ESTRANGEIRA (FK)       PCMONITORBANCOSESSAO
PCMONITORBANCOSESSAOSQL      SQL_ID VARCHAR2(100) Código de identificação da sessão            OPERACIONAL                        NaN
PCMONITORBANCOSESSAOSQL        HASH VARCHAR2(100)                       Hash do SQL            OPERACIONAL                        NaN
PCMONITORBANCOSESSAOSQL         SQL          CLOB           SQL capturada da sessão            OPERACIONAL                        NaN
PCMONITORBANCOSESSAOSQL CAPTURETIME          DATE    Data e hora da gravação do SQL            OPERACIONAL                        NaN
PCMONITORBANCOSESSAOSQL LOCK_NUMBER  NUMBER(10,0)        Número da sessão bloqueada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*