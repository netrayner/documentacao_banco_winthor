# 📊 Tabela: PCINUTILIZARNFE

### Estrutura de Colunas e Restrições

         Tabela                Coluna   Tipo/Tamanho                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINUTILIZARNFE                 SERIE    VARCHAR2(3)                                                                Série da NF-e inutilizada.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZARNFE               NUMNOTA    NUMBER(9,0)                                             Número da nota fiscal eletrônica inutilizada.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZARNFE               TIPOMOV    VARCHAR2(2)                                                                     Tipo da movimentação.            OPERACIONAL                        NaN
PCINUTILIZARNFE          NUMTRANSACAO   NUMBER(10,0)                                                                      Número da transação.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZARNFE                DTLANC           DATE                                                     Data de lançamento para inutilização.            OPERACIONAL                        NaN
PCINUTILIZARNFE        DTINUTILIZACAO           DATE                                                             Data da inutilização efetiva.            OPERACIONAL                        NaN
PCINUTILIZARNFE              CHAVENFE   VARCHAR2(45)                                                                    Chave de acesso da Nfe            OPERACIONAL                        NaN
PCINUTILIZARNFE             RECIBONFE   VARCHAR2(20)                                                                 Número do Recibo do Sefaz            OPERACIONAL                        NaN
PCINUTILIZARNFE            NUMLOTENFE   VARCHAR2(15)                                                                            Número do Lote            OPERACIONAL                        NaN
PCINUTILIZARNFE      NUMTRANSACAONOVA   NUMBER(10,0)                                                                Transação da nota inserida            OPERACIONAL                        NaN
PCINUTILIZARNFE              MENSAGEM VARCHAR2(1000)                                                                    Mensagem de orientação            OPERACIONAL                        NaN
PCINUTILIZARNFE         NUMTENTATIVAS   NUMBER(10,0) Número de tentativas de processamento pelo DocFiscal, para evitar loop e consumo indevido            OPERACIONAL                        NaN
PCINUTILIZARNFE NUMTRANSCONTRAPARTIDA   NUMBER(10,0)                                                         Transação da contrapartida gerada            OPERACIONAL                        NaN
PCINUTILIZARNFE                 CSTAT    VARCHAR2(5)                                                                   Código retorno da SEFAZ            OPERACIONAL                        NaN
PCINUTILIZARNFE      DTHORAREQUISICAO           DATE                                                          Data e hora da última requisição            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*