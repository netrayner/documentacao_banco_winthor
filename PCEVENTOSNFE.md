# 📊 Tabela: PCEVENTOSNFE

### Estrutura de Colunas e Restrições

      Tabela          Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEVENTOSNFE        CHAVENFE VARCHAR2(44)                       Chave da NFe    CHAVE PRIMÁRIA (PK)                        NaN
PCEVENTOSNFE    CODIGOEVENTO  VARCHAR2(6)     Código identificador do evento    CHAVE PRIMÁRIA (PK)                        NaN
PCEVENTOSNFE    NUMSEQEVENTO  VARCHAR2(3)         Número sequencia do evento    CHAVE PRIMÁRIA (PK)                        NaN
PCEVENTOSNFE PROTOCOLOEVENTO  VARCHAR2(3) Protocolo de autorização do evento            OPERACIONAL                        NaN
PCEVENTOSNFE      DATAEVENTO         DATE      Data de autorização do evento            OPERACIONAL                        NaN
PCEVENTOSNFE       XMLEVENTO         CLOB       XML de autorização do evento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*