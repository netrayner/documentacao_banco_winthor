# 📊 Tabela: PCCONSIGFORNEC

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONSIGFORNEC   CODFORNEC  NUMBER(6,0)                                                                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSIGFORNEC NUMTRANSENT NUMBER(10,0)                                                                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSIGFORNEC     CODPROD  NUMBER(6,0)                                                                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSIGFORNEC       DTENT         DATE                                                                                     NaN            OPERACIONAL                        NaN
PCCONSIGFORNEC          QT NUMBER(14,4)                                                                                     NaN            OPERACIONAL                        NaN
PCCONSIGFORNEC    QTDEVFAT NUMBER(14,4)                                                                                     NaN            OPERACIONAL                        NaN
PCCONSIGFORNEC    DTCANCEL         DATE                                                                                     NaN            OPERACIONAL                        NaN
PCCONSIGFORNEC   CODFILIAL  VARCHAR2(2)                                                                                     NaN            OPERACIONAL                        NaN
PCCONSIGFORNEC      NUMSEQ NUMBER(20,0) Seqüencial para identificar quando um item é inserido mais de uma vez na mesma entrada.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*