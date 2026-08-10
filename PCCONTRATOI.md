# 📊 Tabela: PCCONTRATOI

### Estrutura de Colunas e Restrições

     Tabela             Coluna  Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTRATOI        CODCONTRATO   NUMBER(6,0)                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOI            CODPROD   NUMBER(6,0)                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOI                 QT  NUMBER(20,6)                                        NaN            OPERACIONAL                        NaN
PCCONTRATOI            PTABELA  NUMBER(18,6)                                        NaN            OPERACIONAL                        NaN
PCCONTRATOI         CODPRODCLI  NUMBER(10,0)                                        NaN            OPERACIONAL                        NaN
PCCONTRATOI       PRAZOENTREGA   NUMBER(6,0)                                        NaN            OPERACIONAL                        NaN
PCCONTRATOI              QTMIN  NUMBER(20,6)                                        NaN            OPERACIONAL                        NaN
PCCONTRATOI             NUMSEQ   NUMBER(4,0)                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOI      PRODDESCRICAO VARCHAR2(300) Indica a descrição do produto no contrato.            OPERACIONAL                        NaN
PCCONTRATOI         QTDEMINIMA   NUMBER(8,0)          Qtde mínima para venda do produto            OPERACIONAL                        NaN
PCCONTRATOI PRODDESCRICAODANFE VARCHAR2(500)                    Descrição produto Danfe            OPERACIONAL                        NaN
PCCONTRATOI          CODEDITAL   NUMBER(9,0)                           Código do edital            OPERACIONAL                        NaN
PCCONTRATOI               LOTE  VARCHAR2(10)                             Lote do edital            OPERACIONAL                        NaN
PCCONTRATOI        NUMERO_ITEM   NUMBER(9,0)                   Numero do item do Edital            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*