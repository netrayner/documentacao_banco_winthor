# 📊 Tabela: PCLIMCREDCOB

### Estrutura de Colunas e Restrições

      Tabela         Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLIMCREDCOB         CODCLI  NUMBER(6,0)                             Código do cliente    CHAVE PRIMÁRIA (PK)                   PCCLIENT
PCLIMCREDCOB         CODCOB  VARCHAR2(4)                            Código da cobrança    CHAVE PRIMÁRIA (PK)                      PCCOB
PCLIMCREDCOB        LIMCRED NUMBER(12,2)                             Limite de crédito            OPERACIONAL                        NaN
PCLIMCREDCOB     LIMCREDANT NUMBER(10,6) Este campo grava o limite de crédito anterior            OPERACIONAL                        NaN
PCLIMCREDCOB DTULTALTERACAO         DATE                      Data da última alteração            OPERACIONAL                        NaN
PCLIMCREDCOB  DTVENCLIMCRED         DATE          Data da vencimento limite de crédito            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*