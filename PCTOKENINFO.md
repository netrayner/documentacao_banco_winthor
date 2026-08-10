# 📊 Tabela: PCTOKENINFO

### Estrutura de Colunas e Restrições

     Tabela        Coluna  Tipo/Tamanho                                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTOKENINFO         TOKEN VARCHAR2(600)                                                                                                Token de Autenticação            OPERACIONAL                        NaN
PCTOKENINFO        ESTADO  VARCHAR2(40)                                                                                                      Estado do Token            OPERACIONAL                        NaN
PCTOKENINFO   DATACRIACAO  TIMESTAMP(6)                                                                                             Data de Criação do Token            OPERACIONAL                        NaN
PCTOKENINFO DATAEXPIRACAO  TIMESTAMP(6)                                                                                           Data de Expiração do Token            OPERACIONAL                        NaN
PCTOKENINFO     MATRICULA   NUMBER(8,0)                                                                                                 Matrícula do Usuário            OPERACIONAL                        NaN
PCTOKENINFO            ID  NUMBER(11,0)                                                                                                          ID do Token    CHAVE PRIMÁRIA (PK)                        NaN
PCTOKENINFO        ORIGEM  VARCHAR2(20) Campo que define em qual servidor o token de acesso foi gerado. Valores possíveis (WinthorWebServer, WTA, WinthorNG)            OPERACIONAL                        NaN
PCTOKENINFO  REFRESHTOKEN VARCHAR2(100)               Armazena o hash do token de atualização (Refresh Token) emitido durante o processo de autenticação web            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*