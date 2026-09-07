# 📊 Tabela: PCGIAF_IMPORTACAO_ALIQ

### Estrutura de Colunas e Restrições

                Tabela                 Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_IMPORTACAO_ALIQ CODAPURGIAF_IMPORTACAO       NUMBER Código da Apuração do GIAF para a Importação CHAVE ESTRANGEIRA (FK)          PCGIAF_IMPORTACAO
PCGIAF_IMPORTACAO_ALIQ       CODGIAF_IMP_ALIQ       NUMBER Código do Alíquota do GIAF para a Importação    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_IMPORTACAO_ALIQ        ALIQ_INCIDENTES NUMBER(12,4) Alíquota incidente sobre as importações-base            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO_ALIQ       VL_SAIDAS_INC_PI NUMBER(18,6)                   Saídas incentivadas de PI.            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO_ALIQ VL_IMPORT_BC_CRED_PRES NUMBER(18,6)    Importações-base para o crédito presumido            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO_ALIQ  VL_CRED_PRES_SAID_INT NUMBER(18,6)        Crédito presumido nas saídas internas            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*