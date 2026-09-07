# 📊 Tabela: PCPRODUSUR

### Estrutura de Colunas e Restrições

    Tabela     Coluna Tipo/Tamanho      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUSUR     CODIGO  NUMBER(8,0)                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUSUR     CODCLI  NUMBER(6,0)                      NaN            OPERACIONAL                        NaN
PCPRODUSUR    CODUSUR  NUMBER(4,0)                      NaN            OPERACIONAL                        NaN
PCPRODUSUR    CODPROD  NUMBER(6,0)                      NaN            OPERACIONAL                        NaN
PCPRODUSUR DATAINICIO         DATE                      NaN            OPERACIONAL                        NaN
PCPRODUSUR    DATAFIM         DATE                      NaN            OPERACIONAL                        NaN
PCPRODUSUR QTMAXVENDA NUMBER(20,6)                      NaN            OPERACIONAL                        NaN
PCPRODUSUR  NUMREGIAO  NUMBER(4,0)                      NaN            OPERACIONAL                        NaN
PCPRODUSUR   TIPOCOTA  VARCHAR2(1)                      NaN            OPERACIONAL                        NaN
PCPRODUSUR  GRUPOCOTA  NUMBER(8,0) Indica o grupo de cotas.            OPERACIONAL                        NaN
PCPRODUSUR DTMXSALTER         DATE                      NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*