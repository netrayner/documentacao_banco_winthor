# 📊 Tabela: PCCONTROLELOCK

### Estrutura de Colunas e Restrições

        Tabela   Coluna  Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTROLELOCK  CODUSUR   NUMBER(8,0)                                 Código do usuário            OPERACIONAL                        NaN
PCCONTROLELOCK NOMEUSUR  VARCHAR2(40)                                   Nome de usuário            OPERACIONAL                        NaN
PCCONTROLELOCK DATAHORA  TIMESTAMP(6)               Data e hora de inserção do registro            OPERACIONAL                        NaN
PCCONTROLELOCK   ROTINA  VARCHAR2(40)           Rotina que inseriu o registro na tabela            OPERACIONAL                        NaN
PCCONTROLELOCK   NUMCAR   NUMBER(8,0)                     Número do carregamento da 410            OPERACIONAL                        NaN
PCCONTROLELOCK   TABELA VARCHAR2(255)                              Nome da Tabela Usada            OPERACIONAL                        NaN
PCCONTROLELOCK REGISTRO VARCHAR2(255)                                      ID da Tabela            OPERACIONAL                        NaN
PCCONTROLELOCK    EMUSO   VARCHAR2(1) Identifica se o registro ainda está em uso ou não            OPERACIONAL                        NaN
PCCONTROLELOCK TERMINAL VARCHAR2(200)                               Terminal do usuário            OPERACIONAL                        NaN
PCCONTROLELOCK   OSUSER VARCHAR2(200)                                 Usuário da sessão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*