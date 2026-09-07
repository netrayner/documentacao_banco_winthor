# 📊 Tabela: PCLICENCA

### Estrutura de Colunas e Restrições

   Tabela           Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLICENCA        LICENCAID VARCHAR2(100)        Identificação do registro de licença    CHAVE PRIMÁRIA (PK)                        NaN
PCLICENCA           VERSAO  NUMBER(22,0)                          Versão do contrato            OPERACIONAL                        NaN
PCLICENCA EMAILRESPONSAVEL  VARCHAR2(60) E-mail do responsável pela chave no cliente            OPERACIONAL                        NaN
PCLICENCA           STATUS   NUMBER(5,0)          Status atual do cliente junto a PC            OPERACIONAL                        NaN
PCLICENCA     MODELOVERSAO   NUMBER(1,0)          Modelo de Versionamento de Rotinas            OPERACIONAL                        NaN
PCLICENCA    VERSAOWINTHOR   NUMBER(4,0)                     Versão Atual do WinThor            OPERACIONAL                        NaN
PCLICENCA      VERSAOPATCH   NUMBER(4,0)                 Versão do Patch de Correção            OPERACIONAL                        NaN
PCLICENCA           MODELO   NUMBER(1,0)                                         NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*