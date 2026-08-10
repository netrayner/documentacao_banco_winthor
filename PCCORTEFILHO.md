# 📊 Tabela: PCCORTEFILHO

### Estrutura de Colunas e Restrições

      Tabela          Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCORTEFILHO         CODPROD  NUMBER(6,0)                  Cód. Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCCORTEFILHO          NUMSEQ NUMBER(20,0)                Num. Sequencia    CHAVE PRIMÁRIA (PK)                        NaN
PCCORTEFILHO      QTSEPARADA  NUMBER(8,2)                Qtde. separada            OPERACIONAL                        NaN
PCCORTEFILHO       QTCORTADA  NUMBER(8,2)                 Qtde. cortada            OPERACIONAL                        NaN
PCCORTEFILHO      DATA_CORTE         DATE                 Data do corte            OPERACIONAL                        NaN
PCCORTEFILHO          NUMCAR  NUMBER(8,0)             Num. Carregamento    CHAVE PRIMÁRIA (PK)                        NaN
PCCORTEFILHO         CODFUNC  NUMBER(8,0) Cod. Funcinario de lançamento            OPERACIONAL                        NaN
PCCORTEFILHO          NUMPED  NUMBER(8,0)              Numero do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCCORTEFILHO     CODFUNCCONF  NUMBER(8,0)            Cód. Do conferente            OPERACIONAL                        NaN
PCCORTEFILHO      CODFUNCSEP  NUMBER(8,0)             Cod. Do separador            OPERACIONAL                        NaN
PCCORTEFILHO       CODFILIAL  VARCHAR2(2)                   Cód. Filial            OPERACIONAL                        NaN
PCCORTEFILHO          QTORIG NUMBER(20,6)                Qtde. original            OPERACIONAL                        NaN
PCCORTEFILHO         QTFALTA  NUMBER(8,2)                 Qtd. Faltante            OPERACIONAL                        NaN
PCCORTEFILHO          MOTIVO VARCHAR2(80)               Motivo do corte            OPERACIONAL                        NaN
PCCORTEFILHO          CODCLI  NUMBER(6,0)                   Cód cliente            OPERACIONAL                        NaN
PCCORTEFILHO         CODUSUR  NUMBER(4,0)                      Cód. Rca            OPERACIONAL                        NaN
PCCORTEFILHO DTFINALCHECKOUT         DATE Data. De finalizacao da conf.            OPERACIONAL                        NaN
PCCORTEFILHO       CODROTINA  NUMBER(6,0)  Rotina geradora do registros            OPERACIONAL                        NaN
PCCORTEFILHO            HORA  NUMBER(2,0)                 Hora do corte            OPERACIONAL                        NaN
PCCORTEFILHO          MINUTO  NUMBER(2,0)               Minuto do corte            OPERACIONAL                        NaN
PCCORTEFILHO       CONDVENDA  NUMBER(5,0)                 Tipo de venda            OPERACIONAL                        NaN
PCCORTEFILHO  CODEMITENTEPED  NUMBER(8,0)            Emitente do pedido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*