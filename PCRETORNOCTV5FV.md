# 📊 Tabela: PCRETORNOCTV5FV

### Estrutura de Colunas e Restrições

         Tabela                Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRETORNOCTV5FV             NUMPEDRCA NUMBER(10,0)                Número do pedido do palm            OPERACIONAL                        NaN
PCRETORNOCTV5FV     DTABERTURAPEDPALM         DATE         Data completa do pedido no palm            OPERACIONAL                        NaN
PCRETORNOCTV5FV               CODUSUR  NUMBER(4,0)                           Codigo do rca            OPERACIONAL                        NaN
PCRETORNOCTV5FV                CGCCLI VARCHAR2(18)                  Cnpj ou cpf do cliente            OPERACIONAL                        NaN
PCRETORNOCTV5FV          NUMPEDORIGEM NUMBER(10,0) Numero do pedido TV1 que gerou o brinde            OPERACIONAL                        NaN
PCRETORNOCTV5FV             NUMPEDTV5 NUMBER(10,0)             Numero do pedido TV5 gerado            OPERACIONAL                        NaN
PCRETORNOCTV5FV                CODCLI  NUMBER(6,0)                       Codigo do cliente            OPERACIONAL                        NaN
PCRETORNOCTV5FV               RETORNO  NUMBER(4,0)                                 Retorno            OPERACIONAL                        NaN
PCRETORNOCTV5FV         POSICAO_ATUAL  VARCHAR2(1)       Posição atual do pedido de brinde            OPERACIONAL                        NaN
PCRETORNOCTV5FV             CODFILIAL  VARCHAR2(2)              Codigo da Filial do Pedido            OPERACIONAL                        NaN
PCRETORNOCTV5FV           CODFILIALNF  VARCHAR2(2)           Codigo da Filial NF do Pedido            OPERACIONAL                        NaN
PCRETORNOCTV5FV       CODFILIALRETIRA  VARCHAR2(2)       Codigo da Filial Retira do Pedido            OPERACIONAL                        NaN
PCRETORNOCTV5FV             DTENTREGA         DATE               Data de entrega do pedido            OPERACIONAL                        NaN
PCRETORNOCTV5FV            DTINCLUSAO         DATE  Data de inclusao do registro na tabela            OPERACIONAL                        NaN
PCRETORNOCTV5FV           DTALTERACAO         DATE Data de alteração do registro na tabela            OPERACIONAL                        NaN
PCRETORNOCTV5FV GERARBRINDEPEDBONIFIC  VARCHAR2(1)                   GERARBRINDEPEDBONIFIC            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*