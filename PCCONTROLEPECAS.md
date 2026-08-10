# 📊 Tabela: PCCONTROLEPECAS

### Estrutura de Colunas e Restrições

         Tabela        Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTROLEPECAS      NUMBONUS  NUMBER(6,0)    Número do bônus de recebimento            OPERACIONAL                        NaN
PCCONTROLEPECAS       CODPROD  NUMBER(6,0)        Codigo do produto recebido            OPERACIONAL                        NaN
PCCONTROLEPECAS          PESO NUMBER(22,8)             Peso da Peça recebida            OPERACIONAL                        NaN
PCCONTROLEPECAS       ID_PECA NUMBER(20,0)       Identificador único da peça    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLEPECAS        NUMPED NUMBER(10,0) Número do pedido vinculo ao bonus            OPERACIONAL                        NaN
PCCONTROLEPECAS      EXCLUIDO  VARCHAR2(1)   informará se o produto excluido            OPERACIONAL                        NaN
PCCONTROLEPECAS  DATA_ENTRADA         DATE           Data da entrada da peca            OPERACIONAL                        NaN
PCCONTROLEPECAS   CODAUXILIAR VARCHAR2(30)        codigo auxiliar do produto            OPERACIONAL                        NaN
PCCONTROLEPECAS     NUMINVENT  NUMBER(8,0)              Numero do inventario            OPERACIONAL                        NaN
PCCONTROLEPECAS NUMTRANSVENDA NUMBER(10,0)      Numero da transacao de venda            OPERACIONAL                        NaN
PCCONTROLEPECAS   NUMTRANSENT NUMBER(10,0)       Numero transacao de entrada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*