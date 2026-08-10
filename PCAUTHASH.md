# 📊 Tabela: PCAUTHASH

### Estrutura de Colunas e Restrições

   Tabela         Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTHASH         CODCLI  NUMBER(6,0)              Código do cliente PC    CHAVE PRIMÁRIA (PK)               PCAUTLICENCA
PCAUTHASH     AUTLICENCA VARCHAR2(32) Tabela de autenticação de Licença            OPERACIONAL                        NaN
PCAUTHASH        AUTCNPJ VARCHAR2(32)    Tabela de autenticação de CNPJ            OPERACIONAL                        NaN
PCAUTHASH     AUTUSUARIO VARCHAR2(32) Tabela de autenticação de usuário            OPERACIONAL                        NaN
PCAUTHASH      AUTPERFIL VARCHAR2(32)  Tabela de autenticação de perfil            OPERACIONAL                        NaN
PCAUTHASH     CODIGOHASH VARCHAR2(32)                               NaN            OPERACIONAL                        NaN
PCAUTHASH CODIGOHASHFULL VARCHAR2(32)                               NaN            OPERACIONAL                        NaN
PCAUTHASH   AUTPARAMETRO VARCHAR2(32)                               NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*