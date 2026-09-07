# 📊 Tabela: PCOPC

### Estrutura de Colunas e Restrições

Tabela           Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
 PCOPC            NUMOP   NUMBER(8,0)                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
 PCOPC        CODFILIAL   VARCHAR2(2)                                                NaN            OPERACIONAL                        NaN
 PCOPC    CODPRODMASTER   NUMBER(6,0)                                                NaN            OPERACIONAL                        NaN
 PCOPC           METODO   VARCHAR2(4)                                                NaN            OPERACIONAL                        NaN
 PCOPC       QTPRODUZIR  NUMBER(20,8)                                                NaN            OPERACIONAL                        NaN
 PCOPC      QTPRODUZIDA  NUMBER(20,8)                                                NaN            OPERACIONAL                        NaN
 PCOPC           DTLANC          DATE                                                NaN            OPERACIONAL                        NaN
 PCOPC      CODFUNCLANC   NUMBER(8,0)                                                NaN            OPERACIONAL                        NaN
 PCOPC         DTCANCEL          DATE                                                NaN            OPERACIONAL                        NaN
 PCOPC    CODFUNCCANCEL   NUMBER(8,0)                                                NaN            OPERACIONAL                        NaN
 PCOPC         DTINICIO          DATE                                                NaN            OPERACIONAL                        NaN
 PCOPC    CODFUNCINICIO   NUMBER(8,0)                                                NaN            OPERACIONAL                        NaN
 PCOPC          DTFECHA          DATE                                                NaN            OPERACIONAL                        NaN
 PCOPC     CODFUNCFECHA   NUMBER(8,0)                                                NaN            OPERACIONAL                        NaN
 PCOPC          POSICAO   VARCHAR2(1)                                                NaN            OPERACIONAL                        NaN
 PCOPC          QTHORAS   NUMBER(6,2)                                                NaN            OPERACIONAL                        NaN
 PCOPC     DTPREVINICIO          DATE                                                NaN            OPERACIONAL                        NaN
 PCOPC          NUMLOTE  VARCHAR2(15)                                                NaN            OPERACIONAL                        NaN
 PCOPC              OBS VARCHAR2(150)                                                NaN            OPERACIONAL                        NaN
 PCOPC       CODFUNCAMX   NUMBER(8,0)                                                NaN            OPERACIONAL                        NaN
 PCOPC         DTENTAMX          DATE                                                NaN            OPERACIONAL                        NaN
 PCOPC       PARECERAMX   VARCHAR2(2)                                                NaN            OPERACIONAL                        NaN
 PCOPC        NOMEDOCOP VARCHAR2(100)                                                NaN            OPERACIONAL                        NaN
 PCOPC           NUMPED  NUMBER(10,0)                                                NaN            OPERACIONAL                        NaN
 PCOPC       QTORIGINAL  NUMBER(20,8) Indica a Quantidade original da ordem de produção.            OPERACIONAL                        NaN
 PCOPC FINALIZAPRODUCAO   VARCHAR2(1)    Identificar o término de uma linha de produção.            OPERACIONAL                        NaN
 PCOPC       REPROCESSO   VARCHAR2(1)            Informa se a op é de reprocesso ou não.            OPERACIONAL                        NaN
 PCOPC     NUMOPCENTRAL   NUMBER(8,0)          Número da ordem de produção centralizada.            OPERACIONAL                        NaN
 PCOPC           QTDIAS   NUMBER(6,0)       Armazena o tempo médio de produção de uma OP            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*