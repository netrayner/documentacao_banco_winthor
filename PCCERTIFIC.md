# 📊 Tabela: PCCERTIFIC

### Estrutura de Colunas e Restrições

    Tabela           Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCERTIFIC      CODCERTIFIC  NUMBER(8,0)                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCERTIFIC          CODPROD  NUMBER(6,0)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC            SERIE  VARCHAR2(1)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC          TIPODOC  VARCHAR2(1)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC            MARCA VARCHAR2(40)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC             TIPO  VARCHAR2(1)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC           CLASSE VARCHAR2(40)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC           ESTADO  VARCHAR2(2)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC      PERCUMIDADE  NUMBER(6,3)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC       PERCMATEST  NUMBER(6,3)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC     PERCQUEBRADO  NUMBER(6,3)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC          PRODUTO VARCHAR2(40)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC            GRUPO VARCHAR2(40)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC         SUBGRUPO VARCHAR2(40)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC         DTINICIO         DATE                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC           DTVENC         DATE                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC          PESOLIQ NUMBER(16,4)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC    PESOUTILIZADO NUMBER(16,4)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC      ESTEMITSELO VARCHAR2(80)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC ESTEMITCLASSIFIC VARCHAR2(80)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC       MENSAGEMNF VARCHAR2(80)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC   NUMCERTIFICADO VARCHAR2(20)                                     NaN            OPERACIONAL                        NaN
PCCERTIFIC        CODFILIAL  VARCHAR2(2)                        Código da filial            OPERACIONAL                        NaN
PCCERTIFIC          NUMLOTE VARCHAR2(15) Indica o número do lote do certificado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*