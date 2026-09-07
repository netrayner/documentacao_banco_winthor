# 📊 Tabela: PCAUTUSUARIO

### Estrutura de Colunas e Restrições

      Tabela      Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTUSUARIO      CODCLI  NUMBER(6,0)             Código do cliente PC    CHAVE PRIMÁRIA (PK)               PCAUTLICENCA
PCAUTUSUARIO   CODPERFIL  NUMBER(6,0)       Código do perfil do client    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTUSUARIO      TIPOBD  VARCHAR2(1) Tipo do banco: Produção ou Teste    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTUSUARIO  QUANTIDADE  NUMBER(6,0)  Quantidade de acesso por perfil            OPERACIONAL                        NaN
PCAUTUSUARIO DTEXPIRACAO         DATE      Data de expiração do perfil            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*