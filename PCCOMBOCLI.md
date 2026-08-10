# 📊 Tabela: PCCOMBOCLI

### Estrutura de Colunas e Restrições

    Tabela        Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMBOCLI        CODIGO NUMBER(10,0)                       Codigo sequencial            OPERACIONAL                        NaN
PCCOMBOCLI       PERDESC NUMBER(18,6)       Porcentagem consedida de desconto            OPERACIONAL                        NaN
PCCOMBOCLI       CODPROD  NUMBER(6,0)                       Codigo do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMBOCLI        CODCLI  NUMBER(6,0)                       Codigo do cliente            OPERACIONAL                        NaN
PCCOMBOCLI      CODCOMBO NUMBER(10,0)                      Codigo da campanha            OPERACIONAL                        NaN
PCCOMBOCLI     CODFILIAL  VARCHAR2(2)                        Codigo da filial            OPERACIONAL                        NaN
PCCOMBOCLI          DATA         DATE                      data da utilização            OPERACIONAL                        NaN
PCCOMBOCLI CODGRUPOCOMBO NUMBER(10,0)             codigo do grupo de campanha            OPERACIONAL                        NaN
PCCOMBOCLI        NUMSEQ NUMBER(20,0)            numero sequencial do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMBOCLI        NUMPED NUMBER(20,0)                        Numero do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMBOCLI   CODAUXILIAR NUMBER(20,0) Indica o código da embalagem do produto            OPERACIONAL                        NaN
PCCOMBOCLI            QT  NUMBER(6,0)     Indica a quantidade do item incluso            OPERACIONAL                        NaN
PCCOMBOCLI    DTMXSALTER         DATE                                     NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*