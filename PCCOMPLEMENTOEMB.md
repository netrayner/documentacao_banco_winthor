# 📊 Tabela: PCCOMPLEMENTOEMB

### Estrutura de Colunas e Restrições

          Tabela          Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMPLEMENTOEMB         CODPROD  NUMBER(8,0)                   Código do produto            OPERACIONAL                        NaN
PCCOMPLEMENTOEMB         CODCOMP  NUMBER(8,0)               Código do complemento            OPERACIONAL                        NaN
PCCOMPLEMENTOEMB         CODEPTO  NUMBER(8,0)              Código do departamento            OPERACIONAL                        NaN
PCCOMPLEMENTOEMB          CODSEC  NUMBER(8,0)                     Código da seção            OPERACIONAL                        NaN
PCCOMPLEMENTOEMB    CODCATEGORIA  NUMBER(8,0)                 Código da categoria            OPERACIONAL                        NaN
PCCOMPLEMENTOEMB CODSUBCATEGORIA  NUMBER(8,0)              Código da subcategoria            OPERACIONAL                        NaN
PCCOMPLEMENTOEMB     CODAUXILIAR NUMBER(20,0)                 Código da embalagem            OPERACIONAL                        NaN
PCCOMPLEMENTOEMB     COMPLEMENTO VARCHAR2(25)          Complemento a ser inserido            OPERACIONAL                        NaN
PCCOMPLEMENTOEMB       ACRESCIMO  NUMBER(6,2) Acréscimo  inserido por complemento            OPERACIONAL                        NaN
PCCOMPLEMENTOEMB      STATUSCOMP  VARCHAR2(2)               Status do complemento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*