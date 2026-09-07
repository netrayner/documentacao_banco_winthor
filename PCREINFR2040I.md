# 📊 Tabela: PCREINFR2040I

### Estrutura de Colunas e Restrições

       Tabela         Coluna  Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2040I             ID   NUMBER(8,0)                         Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2040I      R2040C_ID   NUMBER(8,0) Identificador registro 2040 cabeçalho            OPERACIONAL                        NaN
PCREINFR2040I         RECNUM  NUMBER(22,0)               RecNum da tabela PCLANC            OPERACIONAL                        NaN
PCREINFR2040I    TIPOREPASSE   NUMBER(8,0)                       Tipo do repasse            OPERACIONAL                        NaN
PCREINFR2040I VLBRUTOREPASSE  NUMBER(12,2)                Valor bruto do repasse            OPERACIONAL                        NaN
PCREINFR2040I     VLRETENCAO  NUMBER(12,2)                     Valor de retenção            OPERACIONAL                        NaN
PCREINFR2040I   DESCRRECURSO VARCHAR2(300)                  Descrição do recurso            OPERACIONAL                        NaN
PCREINFR2040I         STATUS VARCHAR2(100)                                Status            OPERACIONAL                        NaN
PCREINFR2040I     RETEMVALOR   VARCHAR2(1)                           Retem valor            OPERACIONAL                        NaN
PCREINFR2040I    RETIFICACAO   VARCHAR2(1)  Controle de processo em retificação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*