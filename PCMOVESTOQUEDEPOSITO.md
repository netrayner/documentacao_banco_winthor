# 📊 Tabela: PCMOVESTOQUEDEPOSITO

### Estrutura de Colunas e Restrições

              Tabela          Coluna   Tipo/Tamanho                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVESTOQUEDEPOSITO    NUMTRANSACAO   NUMBER(10,0) Código agrupador dos itens de uma transação entre depósitos(DEFSEQ_NUMTRANS_MOVDEP)            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO   CODREQUISICAO   NUMBER(10,0)  Código agrupador dos itens de uma requisição entre depósitos(DEFSEQ_CODREQUISICAO)            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO            DATA           DATE                                                           Data da efetiva transação            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO       DTGERACAO           DATE                                         Data e hora da inserção dos dados na tabela            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO         CODPROD    NUMBER(6,0)                                                                   Código do produto            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO       CODFILIAL    VARCHAR2(2)                                                                    Código da Filial            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO CODDEPOSITOORIG   NUMBER(10,0)                                           Código do depósito de origem da transação            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO CODAUXILIARORIG   NUMBER(20,0)                                Código de barras da embalagem de origem da transação            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO     NUMLOTEORIG   VARCHAR2(15)                                          Nr. Do lote de origem do item da transação            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO CODDEPOSITODEST   NUMBER(10,0)                                          Código do depósito de destino da transação            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO CODAUXILIARDEST   NUMBER(20,0)                               Código de barras da embalagem de destino da transação            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO     NUMLOTEDEST   VARCHAR2(15)                                         Nr. Do lote de destino do item da transação            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO         CODOPER    VARCHAR2(2)                                          Códigoda operação da transação requisitada            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO              QT   NUMBER(22,8)                                                  Quantidade da movimentação do item            OPERACIONAL                        NaN
PCMOVESTOQUEDEPOSITO             OBS VARCHAR2(1000)                                          Observações gerais sobre esta movimentação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*