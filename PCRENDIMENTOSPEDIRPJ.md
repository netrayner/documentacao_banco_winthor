# 📊 Tabela: PCRENDIMENTOSPEDIRPJ

### Estrutura de Colunas e Restrições

              Tabela              Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRENDIMENTOSPEDIRPJ          CODSERVICO  NUMBER(10,0)                   Código do serviço    CHAVE PRIMÁRIA (PK)                        NaN
PCRENDIMENTOSPEDIRPJ   CODTIPORENDIMENTO  NUMBER(10,0)       Código natureza do rendimento            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ        VALORBRUTONF  NUMBER(14,2)          Valor total da nota fiscal            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ  VALORBASERENTENCAO  NUMBER(14,2)            Valor base de retenção\t            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ        PERCRETENCAO  NUMBER(14,2)        Percentual alíquota retenção            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ     VALORRETENCAOIR  NUMBER(14,2)                   Valor retenção IR            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ    VALORRETENCAOPIS  NUMBER(14,2)                  Valor retenção PIS            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ VALORRETENCAOCOFINS  NUMBER(14,2)               Valor retenção COFINS            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ   VALORRETENCAOCSLL  NUMBER(14,2)                 Valor retenção CSLL            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ         OBSERVACOES VARCHAR2(200)                Campo de observações            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ     PERCRETENCAOPCC   NUMBER(6,2)    Percentual alíquota retenção PCC            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ    VALORRETENCAOPCC  NUMBER(14,2)                  Valor retenção PCC            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ      PERCRETENCAOIR   NUMBER(6,2)     Percentual alíquota retenção IR            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ     PERCRETENCAOPIS   NUMBER(6,2)    Percentual alíquota retenção PIS            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ  PERCRETENCAOCOFINS   NUMBER(6,2) Percentual alíquota retenção COFINS            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRPJ    PERCRETENCAOCSLL   NUMBER(6,2)   Percentual alíquota retenção CSLL            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*