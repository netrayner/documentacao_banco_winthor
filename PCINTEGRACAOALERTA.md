# 📊 Tabela: PCINTEGRACAOALERTA

### Estrutura de Colunas e Restrições

            Tabela                 Coluna   Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOALERTA                     ID   NUMBER(10,0)                        Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOALERTA                   NOME  VARCHAR2(255)                                 Armazena o nome            OPERACIONAL                        NaN
PCINTEGRACAOALERTA          IDNOTIFICACAO   NUMBER(10,0)   Chave estrangeira pra a tabela da Notificação CHAVE ESTRANGEIRA (FK)    PCINTEGRACAONOTIFICACAO
PCINTEGRACAOALERTA        TIPONOTIFICACAO   VARCHAR2(50)                      Armazena a TIPONOTIFICACAO            OPERACIONAL                        NaN
PCINTEGRACAOALERTA             TIPOALERTA   VARCHAR2(50)                           Armazena o TIPOALERTA            OPERACIONAL                        NaN
PCINTEGRACAOALERTA                  ATIVO    VARCHAR2(1)                     Armazena o status do alerta            OPERACIONAL                        NaN
PCINTEGRACAOALERTA          IDROTASERVICO   NUMBER(10,0)                         Vincula o alerta a rota            OPERACIONAL                        NaN
PCINTEGRACAOALERTA                IDFLUXO   NUMBER(10,0)                       Vincula o alerta ao fluxo            OPERACIONAL                        NaN
PCINTEGRACAOALERTA            DATACRIACAO           DATE                      Data de cadastro do alerta            OPERACIONAL                        NaN
PCINTEGRACAOALERTA       DATAULTIMOALERTA           DATE                           Data do ultimo alerta            OPERACIONAL                        NaN
PCINTEGRACAOALERTA    MENSAGEMINFORMATIVA VARCHAR2(4000)          Armazena uma mensagem padrão do alerta            OPERACIONAL                        NaN
PCINTEGRACAOALERTA TEMPOMAXIMOSEMEXECUTAR   NUMBER(10,0)                     Armazena o tempo em minutos            OPERACIONAL                        NaN
PCINTEGRACAOALERTA    ALERTADESTINATARIOS VARCHAR2(4000) Guarda a lista de destinatários separados por ;            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*