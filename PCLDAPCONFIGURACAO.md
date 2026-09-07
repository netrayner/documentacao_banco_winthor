# 📊 Tabela: PCLDAPCONFIGURACAO

### Estrutura de Colunas e Restrições

            Tabela               Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLDAPCONFIGURACAO               CODIGO        NUMBER         Identificador único da configuração    CHAVE PRIMÁRIA (PK)                        NaN
PCLDAPCONFIGURACAO                 NOME VARCHAR2(100)             Nome descritivo da configuração            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO        LDAPPROTOCOLO  VARCHAR2(10)                         Protocolo de acesso            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO         LDAPENDERECO VARCHAR2(100)                   Endereço do servidor LDAP            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO            LDAPPORTA  VARCHAR2(10)                             Porta de acesso            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO           SEARCHBASE VARCHAR2(100)                   Texto de consulta no LDAP            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO AUTHENTICATIONMETHOD  VARCHAR2(20)                      metodo de autenticacao            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO           USERNAMEDN VARCHAR2(100)                             Nome de usuario            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO             PASSWORD VARCHAR2(100)                            Senha do usuario            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO          TIMEOUTWAIT  VARCHAR2(10)             Tempo de espera em milisegundos            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO         TIMEOUTRETRY  VARCHAR2(10)        Tempo de espera entre nova tentativa            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO      TIMEOUTATTEMPTS  VARCHAR2(10)                    Quantidade de tentativas            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO        LDAPCLASSUSER VARCHAR2(100)         Identificação da classe de usuarios            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO           USERFILTER VARCHAR2(100)                  Filtro de usuarios no LDAP            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO      USERIDATTRIBUTE VARCHAR2(100)       Nome do atributo que identifica login            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO    REALNAMEATTRIBUTE VARCHAR2(100)      Nome do atributo que identifica o nome            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO       EMAILATTRIBUTE VARCHAR2(100)     Nome do atributo que identifica o email            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO    PASSWORDATTRIBUTE VARCHAR2(100)     Nome do atributo que identifica a senha            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO            GROUPTYPE  VARCHAR2(50)                   Tipo do grupo de usuarios            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO GROUPMEMBERATTRIBUTE VARCHAR2(100)      Nome do atributo que identifica Grupos            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO     LDAPGROUPASROLES   VARCHAR2(1)          Importar grupos como perfil S ou N            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO          USERSUBTREE   VARCHAR2(1)              Usuario sem sub-arvores S ou N            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO           TYPEDOMAIN   VARCHAR2(1) Define o tipo de dominio de usuario do LDAP            OPERACIONAL                        NaN
PCLDAPCONFIGURACAO           USERDOMAIN VARCHAR2(100)      Descreve o nome do dominio de usuarios            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*