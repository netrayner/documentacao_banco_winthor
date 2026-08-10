# 📊 Tabela: PCCONTRATOFORNEC

### Estrutura de Colunas e Restrições

          Tabela              Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTRATOFORNEC           CODFILIAL  VARCHAR2(2)                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOFORNEC           CODFORNEC  NUMBER(6,0)                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOFORNEC             CODPROD  NUMBER(6,0)                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOFORNEC         NUMCONTRATO VARCHAR2(60)                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOFORNEC           DTINICIAL         DATE                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC             DTFINAL         DATE                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC              INDICE NUMBER(18,6)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC          TIPOINDICE  VARCHAR2(1)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC              DTLANC         DATE                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC           TIPOVERBA  VARCHAR2(1)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC            CODCONTA NUMBER(10,0)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC          PRAZOPAGTO NUMBER(10,0)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC           HISTORICO VARCHAR2(60)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC          SUPERVISOR VARCHAR2(40)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC                NOME VARCHAR2(40)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC                 CPF VARCHAR2(30)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC                  RG VARCHAR2(30)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC CALCVALORSEMIMPOSTO  VARCHAR2(1)                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC          DTEXCLUSAO         DATE                                       NaN            OPERACIONAL                        NaN
PCCONTRATOFORNEC        CODTIPOVERBA NUMBER(10,0)         Indica o código do tipo da verba.            OPERACIONAL                        NaN
PCCONTRATOFORNEC         DESCONTOFIN  VARCHAR2(1) Indica se utiliza no desconto financeiro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*