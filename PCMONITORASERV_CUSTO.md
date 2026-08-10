# 📊 Tabela: PCMONITORASERV_CUSTO

### Estrutura de Colunas e Restrições

              Tabela            Coluna   Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMONITORASERV_CUSTO         DTGERACAO           DATE          Data e hora da movimentação            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO         TRANSACAO   VARCHAR2(15)   Numero da transação de movimentada            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO  TIPOMOVIMENTACAO    VARCHAR2(1)                 Tipo da movimentação            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO         CODFILIAL    VARCHAR2(2)                     Código da filial            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO           CODPROD   NUMBER(10,0)                    Código do produto            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO            NUMSEQ    NUMBER(6,0)                Sequencial do produto            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO            ROTINA   VARCHAR2(60) Rotina que chamou o serviço de custo            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO CALCULA_GERENCIAL    VARCHAR2(1)              Calcula custo gerencial            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO  CALCULA_CONTABIL    VARCHAR2(1)               Calcula custo contabil            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO       INFORMACOES  VARCHAR2(400)           Passos do serviço de custo            OPERACIONAL                        NaN
PCMONITORASERV_CUSTO       MSG_RETORNO VARCHAR2(4000)         Mensagens de retorno de erro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*