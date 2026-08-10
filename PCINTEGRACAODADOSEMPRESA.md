# 📊 Tabela: PCINTEGRACAODADOSEMPRESA

### Estrutura de Colunas e Restrições

                  Tabela              Coluna   Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAODADOSEMPRESA                  ID   NUMBER(10,0)                                                Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAODADOSEMPRESA                NOME   VARCHAR2(40)                                                     Nome da empresa API            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA             URLBASE   VARCHAR2(80)                                                 Url base da empresa API            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA        TOKENCLIENTE           CLOB                                         Armazena o token da empresa API            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA                 WTA    VARCHAR2(1)                               Registra se a empresa API pertence ao WTA            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA  DTSOLICITACAOTOKEN           DATE                                            Data da solicitação do token            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA TOKENTEMPOEXPIRACAO   NUMBER(10,0)                                  Armazena o tempo de expiração do token            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA              VERSAO   VARCHAR2(20)                                   Armazena a versão do layout instalado            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA         PROJETONOME   VARCHAR2(40)                                     Armazena o nome do layout instalado            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA     CONFIGURACAOERP           CLOB                                                                     NaN            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA         MULTIFILIAL    VARCHAR2(1) Informa se a empresa irá trabalhar com o processo de multiplas filiais.            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA        REFRESHTOKEN           CLOB                                           Refresh token da empresa API.            OPERACIONAL                        NaN
PCINTEGRACAODADOSEMPRESA           DESCRICAO VARCHAR2(4000)                                                 Descricao da Integracao            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*