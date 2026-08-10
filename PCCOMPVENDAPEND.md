# 📊 Tabela: PCCOMPVENDAPEND

### Estrutura de Colunas e Restrições

         Tabela        Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMPVENDAPEND       CODPROD  NUMBER(6,0)                 Código do produto    CHAVE PRIMÁRIA (PK)          PCRASTREABILIDADE
PCCOMPVENDAPEND   NUMSEQVENDA NUMBER(20,0)     Número sequencia pedido venda CHAVE ESTRANGEIRA (FK)          PCRASTREABILIDADE
PCCOMPVENDAPEND        NUMSEQ  NUMBER(6,0)    Número sequencia pedido compra    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPVENDAPEND          QTDE NUMBER(20,6)                     Qtde Atendida            OPERACIONAL                        NaN
PCCOMPVENDAPEND        NUMPED NUMBER(10,0)        Número do pedido de compra    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPVENDAPEND   NUMPEDVENDA NUMBER(10,0)         Número do pedido de venda CHAVE ESTRANGEIRA (FK)          PCRASTREABILIDADE
PCCOMPVENDAPEND     NUMPEDPAI NUMBER(10,0) Número do pedido de compra Master            OPERACIONAL                        NaN
PCCOMPVENDAPEND   NUMTRANSENT NUMBER(10,0)       Número transação NF entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPVENDAPEND LIBERADOVENDA  VARCHAR2(1)       Entrada liberada para venda            OPERACIONAL                        NaN
PCCOMPVENDAPEND      DTCANCEL         DATE         Data cancelamento Entrada            OPERACIONAL                        NaN
PCCOMPVENDAPEND    ROTINALANC VARCHAR2(48)                 Rotina Lançamento            OPERACIONAL                        NaN
PCCOMPVENDAPEND        VERSAO VARCHAR2(20)                     Versão rotina            OPERACIONAL                        NaN
PCCOMPVENDAPEND     NUMSEQENT  NUMBER(6,0)          Número Sequencia Entrada    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*