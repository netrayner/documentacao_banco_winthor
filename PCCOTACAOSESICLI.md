# 📊 Tabela: PCCOTACAOSESICLI

### Estrutura de Colunas e Restrições

          Tabela     Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTACAOSESICLI CODCOTACAO NUMBER(10,0)               Código da cotação.    CHAVE PRIMÁRIA (PK)              PCCOTACAOSESI
PCCOTACAOSESICLI     CODCLI  NUMBER(6,0)    Código do cliente da cotação.            OPERACIONAL                        NaN
PCCOTACAOSESICLI       CNPJ VARCHAR2(14)                 CNPJ do cliente.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTACAOSESICLI   APROVADO  VARCHAR2(1) Informa cliente aprovado ou não.            OPERACIONAL                        NaN
PCCOTACAOSESICLI  CODMOTIVO  NUMBER(2,0)                Código do motivo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*