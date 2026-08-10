# 📊 Tabela: PCNVE

### Estrutura de Colunas e Restrições

Tabela            Coluna  Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
 PCNVE           CODPROD   NUMBER(6,0)          Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
 PCNVE            CODNVE   VARCHAR2(8)           Código NVE (NCM)            OPERACIONAL                        NaN
 PCNVE          CODNIVEL  VARCHAR2(10)                      Nível            OPERACIONAL                        NaN
 PCNVE       CODATRIBUTO  VARCHAR2(10)         Código do atributo            OPERACIONAL                        NaN
 PCNVE      DESCATRIBUTO VARCHAR2(100)      Descrição do atributo            OPERACIONAL                        NaN
 PCNVE  CODESPECIFICACAO  VARCHAR2(10)    Código da especificação            OPERACIONAL                        NaN
 PCNVE DESCESPECIFICACAO VARCHAR2(100) Descrição da especificação            OPERACIONAL                        NaN
 PCNVE        UNIDADENVE  VARCHAR2(10)   Unidade de medida do NVE            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*