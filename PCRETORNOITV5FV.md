# 📊 Tabela: PCRETORNOITV5FV

### Estrutura de Colunas e Restrições

         Tabela            Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRETORNOITV5FV         NUMPEDRCA NUMBER(10,0)                  Número do pedido do palm            OPERACIONAL                        NaN
PCRETORNOITV5FV DTABERTURAPEDPALM         DATE           Data completa do pedido no palm            OPERACIONAL                        NaN
PCRETORNOITV5FV           CODUSUR  NUMBER(4,0)                             Codigo do rca            OPERACIONAL                        NaN
PCRETORNOITV5FV            CGCCLI VARCHAR2(18)                    Cnpj ou cpf do cliente            OPERACIONAL                        NaN
PCRETORNOITV5FV      NUMPEDORIGEM NUMBER(10,0)   Numero do pedido TV1 que gerou o brinde            OPERACIONAL                        NaN
PCRETORNOITV5FV         NUMPEDTV5 NUMBER(10,0)               Numero do pedido TV5 gerado            OPERACIONAL                        NaN
PCRETORNOITV5FV            CODCLI  NUMBER(6,0)                         Codigo do cliente            OPERACIONAL                        NaN
PCRETORNOITV5FV           CODPROD  NUMBER(6,0)                         Codigo do produto            OPERACIONAL                        NaN
PCRETORNOITV5FV       CODAUXILIAR NUMBER(16,0)                          Codigo de barras            OPERACIONAL                        NaN
PCRETORNOITV5FV                QT NUMBER(20,6) Quantidade de brinde gravada pela package            OPERACIONAL                        NaN
PCRETORNOITV5FV       QT_FATURADA NUMBER(20,6)      Quantidade atual de brinde na pcpedi            OPERACIONAL                        NaN
PCRETORNOITV5FV   CODFILIALRETIRA  VARCHAR2(2)           Codigo da Filial Retira do item            OPERACIONAL                        NaN
PCRETORNOITV5FV           PTABELA NUMBER(12,6)                 Preco de tabela do brinde            OPERACIONAL                        NaN
PCRETORNOITV5FV            NUMSEQ NUMBER(20,0)                    Numse do itemde brinde            OPERACIONAL                        NaN
PCRETORNOITV5FV        DTINCLUSAO         DATE    Data de inclusao do registro na tabela            OPERACIONAL                        NaN
PCRETORNOITV5FV       DTALTERACAO         DATE   Data de alteração do registro na tabela            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*