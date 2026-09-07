# 📊 Tabela: PCWMSBOXPALETE

### Estrutura de Colunas e Restrições

        Tabela       Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSBOXPALETE    CODFILIAL  VARCHAR2(2)                  Código da filial            OPERACIONAL                        NaN
PCWMSBOXPALETE       CODBOX  NUMBER(4,0)                     Código do box            OPERACIONAL                        NaN
PCWMSBOXPALETE    NUMPALETE  NUMBER(4,0)                  Número do palete            OPERACIONAL                        NaN
PCWMSBOXPALETE         PESO NUMBER(12,6)                    Peso do palete            OPERACIONAL                        NaN
PCWMSBOXPALETE       VOLUME NUMBER(12,6)                     Volume do Box            OPERACIONAL                        NaN
PCWMSBOXPALETE        NUMOS NUMBER(10,0) Destinado a gravar o número da OS            OPERACIONAL                        NaN
PCWMSBOXPALETE CODBOXPALETE NUMBER(10,0)          C[odigo do palete no box            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*