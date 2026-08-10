# 📊 Tabela: PCRELFILTROESP

### Estrutura de Colunas e Restrições

        Tabela         Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRELFILTROESP   CODRELATORIO   NUMBER(4,0)                            CÓDIGO DO RELATORIO            OPERACIONAL                        NaN
PCRELFILTROESP      CODFILTRO   NUMBER(6,0)                               CÓDIGO DO FILTRO    CHAVE PRIMÁRIA (PK)                        NaN
PCRELFILTROESP      NOMECAMPO VARCHAR2(100)                        NOME DO CAMPO DA TABELA            OPERACIONAL                        NaN
PCRELFILTROESP       OPERADOR  VARCHAR2(20)                     OPERADOR DA CLAUSULA WHERE            OPERACIONAL                        NaN
PCRELFILTROESP          VALOR VARCHAR2(100) VALOR DO FILTRO REFERENTE AO CAMPO SELECIONADO            OPERACIONAL                        NaN
PCRELFILTROESP OPERADORLOGICO   VARCHAR2(3)                      OPERADOR LOGICO (AND, OR)            OPERACIONAL                        NaN
PCRELFILTROESP          ORDEM   NUMBER(4,0)                               ORDEM DO FILTRO             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*