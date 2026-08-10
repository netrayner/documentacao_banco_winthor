# 📊 Tabela: PCCORTEFV

### Estrutura de Colunas e Restrições

   Tabela            Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCORTEFV         NUMPEDRCA NUMBER(10,0)                Número do pedido do palm            OPERACIONAL                        NaN
PCCORTEFV            NUMPED NUMBER(10,0)             Número do pedido do Winthor            OPERACIONAL                        NaN
PCCORTEFV           CODUSUR  NUMBER(4,0)                           Código do rca            OPERACIONAL                        NaN
PCCORTEFV            CODCLI  NUMBER(6,0)                       Código do cliente            OPERACIONAL                        NaN
PCCORTEFV DTABERTURAPEDPALM         DATE                  Data do pedido no palm            OPERACIONAL                        NaN
PCCORTEFV           CODPROD  NUMBER(6,0)                       Código do produto            OPERACIONAL                        NaN
PCCORTEFV       CODAUXILIAR NUMBER(20,0)                        Código de barras            OPERACIONAL                        NaN
PCCORTEFV            NUMSEQ NUMBER(20,0)                               Sequencia            OPERACIONAL                        NaN
PCCORTEFV             QTANT NUMBER(20,6)            Quantidade anterior ao corte            OPERACIONAL                        NaN
PCCORTEFV           QTCORTE NUMBER(20,6)                      Quantidade cortada            OPERACIONAL                        NaN
PCCORTEFV           DTCORTE         DATE                           Data do corte            OPERACIONAL                        NaN
PCCORTEFV      CODFUNCCORTE VARCHAR2(80)       Código do Usuario que fez o corte            OPERACIONAL                        NaN
PCCORTEFV          PROGRAMA VARCHAR2(80) Código da rotina onde foi feito o corte            OPERACIONAL                        NaN
PCCORTEFV           MAQUINA VARCHAR2(80)          Máquina onde foi feito o corte            OPERACIONAL                        NaN
PCCORTEFV         CODFILIAL  VARCHAR2(2)              Código da Filial do pedido            OPERACIONAL                        NaN
PCCORTEFV   CODFILIALRETIRA  VARCHAR2(2)         Código da Filial retira do item            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*