# 📊 Tabela: PCMONITORBANCOSESSAO

### Estrutura de Colunas e Restrições

              Tabela           Coluna  Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMONITORBANCOSESSAO        CODSESSAO  NUMBER(10,0)                  Identificador único    CHAVE PRIMÁRIA (PK)                        NaN
PCMONITORBANCOSESSAO       CODMONITOR  NUMBER(10,0)       Identificador do monitaramento CHAVE ESTRANGEIRA (FK)             PCMONITORBANCO
PCMONITORBANCOSESSAO              SID VARCHAR2(100)    Código de identificação da sessão            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO          MACHINE VARCHAR2(100) Intervalo de monitoramento da sessão            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO           MODULE VARCHAR2(100)      Dados comlementares do programa            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO           OSUSER VARCHAR2(100)      Usuário do sistesma operacional            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO          PROGRAM VARCHAR2(100)           Nome do programa da sessão            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO           ACTION VARCHAR2(100)          Descrição da ação da sessão            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO      CLIENT_INFO VARCHAR2(100) Informações complementares da sessão            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO       LOGON_TIME          DATE       Data e hora de logon da sessão            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO BLOCKING_SESSION VARCHAR2(100)     Identificador da sessão com lock            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO      MISSINGTIME          DATE                 Data final da sessão            OPERACIONAL                        NaN
PCMONITORBANCOSESSAO      LOCK_NUMBER  NUMBER(10,0)      Quantidade de sessões bloqueada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*