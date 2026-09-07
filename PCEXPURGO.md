# 📊 Tabela: PCEXPURGO

### Estrutura de Colunas e Restrições

   Tabela            Coluna  Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXPURGO       NUMTRANSWMS  NUMBER(10,0)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCEXPURGO           CODPROD   NUMBER(6,0)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCEXPURGO                QT  NUMBER(20,8)                 NaN            OPERACIONAL                        NaN
PCEXPURGO              TIPO   VARCHAR2(1)                 NaN            OPERACIONAL                        NaN
PCEXPURGO           OBSTIPO VARCHAR2(400)                 NaN            OPERACIONAL                        NaN
PCEXPURGO  INTENSIDADEPRAGA   VARCHAR2(1)                 NaN            OPERACIONAL                        NaN
PCEXPURGO              DATA          DATE                 NaN            OPERACIONAL                        NaN
PCEXPURGO      DTFECHAMENTO          DATE                 NaN            OPERACIONAL                        NaN
PCEXPURGO    EVIDENCIAPRAGA   VARCHAR2(1)                 NaN            OPERACIONAL                        NaN
PCEXPURGO OBSEVIDENCIAPRAGA VARCHAR2(400)                 NaN            OPERACIONAL                        NaN
PCEXPURGO    PRODUTOEXPURGO  VARCHAR2(60)                 NaN            OPERACIONAL                        NaN
PCEXPURGO     PARTICIPANTES VARCHAR2(400)                 NaN            OPERACIONAL                        NaN
PCEXPURGO CONDICOESAMBIENTE VARCHAR2(400)                 NaN            OPERACIONAL                        NaN
PCEXPURGO          EXECUTOR  VARCHAR2(40)                 NaN            OPERACIONAL                        NaN
PCEXPURGO       COORDENADOR  VARCHAR2(40)                 NaN            OPERACIONAL                        NaN
PCEXPURGO        SUPERVISOR  VARCHAR2(40)                 NaN            OPERACIONAL                        NaN
PCEXPURGO    ACOMPANHAMENTO  VARCHAR2(40)                 NaN            OPERACIONAL                        NaN
PCEXPURGO     DTVERIFICACAO          DATE                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*