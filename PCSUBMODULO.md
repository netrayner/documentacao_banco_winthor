# 📊 Tabela: PCSUBMODULO

### Estrutura de Colunas e Restrições

     Tabela       Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUBMODULO    CODMODULO  NUMBER(4,0)                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSUBMODULO CODSUBMODULO  NUMBER(4,0)                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSUBMODULO    SUBMODULO VARCHAR2(40)                                          NaN            OPERACIONAL                        NaN
PCSUBMODULO   EXIBIRMENU  VARCHAR2(1)                                          NaN            OPERACIONAL                        NaN
PCSUBMODULO      AUTMENU NUMBER(10,0)                                          NaN            OPERACIONAL                        NaN
PCSUBMODULO         FIID VARCHAR2(50) Identificação do submodulo no FLUIG Identity            OPERACIONAL                        NaN
PCSUBMODULO   DTMXSALTER         DATE                                          NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*