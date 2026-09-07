# 📊 Tabela: PCDESD

### Estrutura de Colunas e Restrições

Tabela            Coluna Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESD NUMTRANSVENDADEST NUMBER(10,0)                                                     NaN            OPERACIONAL                        NaN
PCDESD         PRESTDEST  VARCHAR2(2)                                                     NaN            OPERACIONAL                        NaN
PCDESD        CODCLIDEST  NUMBER(6,0)                                                     NaN            OPERACIONAL                        NaN
PCDESD NUMTRANSVENDAORIG NUMBER(10,0)                                                     NaN            OPERACIONAL                        NaN
PCDESD         PRESTORIG  VARCHAR2(2)                                                     NaN            OPERACIONAL                        NaN
PCDESD        CODCLIORIG  NUMBER(6,0)                                                     NaN            OPERACIONAL                        NaN
PCDESD            DTLANC         DATE                                                     NaN            OPERACIONAL                        NaN
PCDESD      CODFUNCCXMOT  NUMBER(8,0)                                                     NaN            OPERACIONAL                        NaN
PCDESD         CODROTINA  NUMBER(6,0)    Código da rotina onde o desdobramento foi efetuado.             OPERACIONAL                        NaN
PCDESD        CODCOBORIG  VARCHAR2(4)                             Código da cobrança original            OPERACIONAL                        NaN
PCDESD        CODCOBDEST  VARCHAR2(4)                              Código da cobrança destino            OPERACIONAL                        NaN
PCDESD  NUMTRANSVENDAPAI NUMBER(10,0) Num Trans Venda PAI (Mantem em todos os desdobramentos)            OPERACIONAL                        NaN
PCDESD          PRESTPAI  VARCHAR2(2)          Prest  Pai (Mantem em todos os desdobramentos)            OPERACIONAL                        NaN
PCDESD         CODCOBPAI  VARCHAR2(4)         Cod Cob Pai (Mantem em todos os desdobramentos)            OPERACIONAL                        NaN
PCDESD       DESDINICIAL NUMBER(10,0)                Desdobramento inicial(primeira desdobra)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*