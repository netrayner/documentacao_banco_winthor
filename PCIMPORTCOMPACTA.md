# 📊 Tabela: PCIMPORTCOMPACTA

### Estrutura de Colunas e Restrições

          Tabela          Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCIMPORTCOMPACTA       SEQUENCIA  NUMBER(20,0)                         Sequência da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCIMPORTCOMPACTA     TIPOIMPOSTO  VARCHAR2(20)   Tipo de Imposto (ICMS, PIS, COFINS ou IPI            OPERACIONAL                        NaN
PCIMPORTCOMPACTA IDENTIFICARTRIB VARCHAR2(200)                 Identificação de tributação            OPERACIONAL                        NaN
PCIMPORTCOMPACTA      DESTINACAO  VARCHAR2(50)     Destinação que vem no arquivo importado            OPERACIONAL                        NaN
PCIMPORTCOMPACTA       ICMS_ALIQ  NUMBER(18,4)                            Alíquota de ICMS            OPERACIONAL                        NaN
PCIMPORTCOMPACTA    ICMS_ST_ALIQ  NUMBER(18,4)                         Alíquota de ICMS ST            OPERACIONAL                        NaN
PCIMPORTCOMPACTA     ICMS_ST_MVA  NUMBER(18,4)                     Alíquota de ICMS ST MVA            OPERACIONAL                        NaN
PCIMPORTCOMPACTA  ICMS_ST_MVA_AJ  NUMBER(18,4)            Alíquota de ICMS ST MVA Ajustado            OPERACIONAL                        NaN
PCIMPORTCOMPACTA        PIS_ALIQ  NUMBER(18,4)                             Alíquota do PIS            OPERACIONAL                        NaN
PCIMPORTCOMPACTA     COFINS_ALIQ  NUMBER(18,4)                          Alíquota da COFINS            OPERACIONAL                        NaN
PCIMPORTCOMPACTA         PIS_CST  NUMBER(18,4)           Código Situação Tributária do PIS            OPERACIONAL                        NaN
PCIMPORTCOMPACTA      COFINS_CST  NUMBER(18,4)        Código Situação Tributária da COFINS            OPERACIONAL                        NaN
PCIMPORTCOMPACTA    PIS_P_RED_BC  NUMBER(18,4)    Alíquota da Base Cálc. Da Redução do PIS            OPERACIONAL                        NaN
PCIMPORTCOMPACTA COFINS_P_RED_BC  NUMBER(18,4) Alíquota da Base Cálc. Da Redução da COFINS            OPERACIONAL                        NaN
PCIMPORTCOMPACTA        IPI_ALIQ  NUMBER(18,4)                             Alíquota do IPI            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*