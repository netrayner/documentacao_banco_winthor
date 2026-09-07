# 📊 Tabela: PCFERIADOFISCAL

### Estrutura de Colunas e Restrições

         Tabela          Coluna Tipo/Tamanho     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFERIADOFISCAL      CODFERIADO  NUMBER(6,0)       Codigo do feriado    CHAVE PRIMÁRIA (PK)                        NaN
PCFERIADOFISCAL     DESCFERIADO VARCHAR2(40)    Descricao do feriado            OPERACIONAL                        NaN
PCFERIADOFISCAL             DIA  NUMBER(2,0)                     dia            OPERACIONAL                        NaN
PCFERIADOFISCAL             MES  NUMBER(2,0)                     mês            OPERACIONAL                        NaN
PCFERIADOFISCAL             ANO  NUMBER(4,0)                     ano            OPERACIONAL                        NaN
PCFERIADOFISCAL CONSIDTODOSANOS  VARCHAR2(1) considera todos os anos            OPERACIONAL                        NaN
PCFERIADOFISCAL     TIPOFERIADO  VARCHAR2(1)            tipo feriado            OPERACIONAL                        NaN
PCFERIADOFISCAL       UFFERIADO  VARCHAR2(2)              uf feriado            OPERACIONAL                        NaN
PCFERIADOFISCAL       CODCIDADE  NUMBER(6,0)          cidade feriado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*