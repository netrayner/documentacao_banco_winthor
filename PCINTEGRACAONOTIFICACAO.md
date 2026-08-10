# 📊 Tabela: PCINTEGRACAONOTIFICACAO

### Estrutura de Colunas e Restrições

                 Tabela          Coluna  Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAONOTIFICACAO              ID  NUMBER(10,0)             Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAONOTIFICACAO            NOME VARCHAR2(255)                      Armazena o nome            OPERACIONAL                        NaN
PCINTEGRACAONOTIFICACAO TIPONOTIFICACAO  VARCHAR2(50)       Armazena o tipo da notificação            OPERACIONAL                        NaN
PCINTEGRACAONOTIFICACAO        SMTPHOST VARCHAR2(255)   Armazena o host referente ao email            OPERACIONAL                        NaN
PCINTEGRACAONOTIFICACAO        SMTPPORT   NUMBER(8,0)        Armazena o SMTPPORT  do email            OPERACIONAL                        NaN
PCINTEGRACAONOTIFICACAO        USERNAME VARCHAR2(255)         Armazena o USERNAME do email            OPERACIONAL                        NaN
PCINTEGRACAONOTIFICACAO        PASSWORD VARCHAR2(255)        Armazena o PASSWORD  do email            OPERACIONAL                        NaN
PCINTEGRACAONOTIFICACAO      SSLENABLED   VARCHAR2(1)      Armazena o SSLENABLED  do email            OPERACIONAL                        NaN
PCINTEGRACAONOTIFICACAO STARTTLSENABLED   VARCHAR2(1) Armazena o STARTTLSENABLED  do email            OPERACIONAL                        NaN
PCINTEGRACAONOTIFICACAO   DEFAULTSENDER VARCHAR2(255)   Armazena o DEFAULTSENDER  do email            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*