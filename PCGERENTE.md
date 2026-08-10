# 📊 Tabela: PCGERENTE

### Estrutura de Colunas e Restrições

   Tabela             Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGERENTE         CODGERENTE   NUMBER(4,0)                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCGERENTE        NOMEGERENTE  VARCHAR2(40)                                    NaN            OPERACIONAL                        NaN
PCGERENTE         VLCORRENTE  NUMBER(22,6)                Valor do conta corrente            OPERACIONAL                        NaN
PCGERENTE          VLLIMCRED  NUMBER(22,6)             Valor do limite do crédito            OPERACIONAL                        NaN
PCGERENTE         USADEBCRED   VARCHAR2(1)                   Usa débito e crédito            OPERACIONAL                        NaN
PCGERENTE         COD_CADRCA   NUMBER(4,0) Código de RCA que representa o gerente            OPERACIONAL                        NaN
PCGERENTE                CPF  VARCHAR2(20)                         CPF do Gerente            OPERACIONAL                        NaN
PCGERENTE              EMAIL VARCHAR2(100)                       email do Gerente            OPERACIONAL                        NaN
PCGERENTE               TIPO   VARCHAR2(1)                        Tipo de Gerente            OPERACIONAL                        NaN
PCGERENTE CODGERENTESUPERIOR   NUMBER(4,0)             Código do Gerente Superior            OPERACIONAL                        NaN
PCGERENTE         DTMXSALTER          DATE                                    NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*