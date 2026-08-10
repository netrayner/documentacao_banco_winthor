# 📊 Tabela: PCAVULSA

### Estrutura de Colunas e Restrições

  Tabela         Coluna  Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAVULSA        CODPROD   NUMBER(6,0)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAVULSA             QT  NUMBER(20,8)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA        CODOPER   VARCHAR2(2)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA          NUMOP   NUMBER(8,0)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA       CODCONTA  NUMBER(10,0)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA        NUMLOTE  VARCHAR2(15)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA NUMTRANSAVULSA  NUMBER(10,0)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAVULSA          PUNIT  NUMBER(18,6)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA    CODFUNCLANC   NUMBER(8,0)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA   CODFUNCBAIXA   NUMBER(8,0)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA         DTLANC          DATE                                                         NaN            OPERACIONAL                        NaN
PCAVULSA        DTBAIXA          DATE                                                         NaN            OPERACIONAL                        NaN
PCAVULSA      CODFILIAL   VARCHAR2(2)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA         NUMSEQ   NUMBER(6,0)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAVULSA       DTCANCEL          DATE                                                         NaN            OPERACIONAL                        NaN
PCAVULSA            OBS VARCHAR2(100)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA        NUMLANC   NUMBER(8,0)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA     QTANTERIOR  NUMBER(20,8)                                                         NaN            OPERACIONAL                        NaN
PCAVULSA    CODDEPOSITO  NUMBER(10,0) Código do depósito onde o estoque esta armazenado na filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*