# 📊 Tabela: PCINUTILIZARCTE

### Estrutura de Colunas e Restrições

         Tabela           Coluna   Tipo/Tamanho                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINUTILIZARCTE            SERIE    VARCHAR2(3)                                                           Sério do CTE sem retorno SEFAZ.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZARCTE           NUMCTE    NUMBER(9,0)                                                          Número do CTE sem retorno SEFAZ.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZARCTE          TIPOMOV    VARCHAR2(2)                                                                      Tipo da movimentação            OPERACIONAL                        NaN
PCINUTILIZARCTE     NUMTRANSACAO   NUMBER(10,0)                                                                       Número da transação            OPERACIONAL                        NaN
PCINUTILIZARCTE           DTLANC           DATE                                                                        Data de lançamento            OPERACIONAL                        NaN
PCINUTILIZARCTE   DTINUTILIZACAO           DATE                                                             Data de inutilização na SEFAZ            OPERACIONAL                        NaN
PCINUTILIZARCTE         CHAVECTE   VARCHAR2(45)                                                                    Chave de acesso do CTE            OPERACIONAL                        NaN
PCINUTILIZARCTE        RECIBOCTE   VARCHAR2(20)                                                                    Número do recibo SEFAZ            OPERACIONAL                        NaN
PCINUTILIZARCTE       NUMLOTECTE   VARCHAR2(15)                                                                            Número do lote            OPERACIONAL                        NaN
PCINUTILIZARCTE NUMTRANSACAONOVA   NUMBER(10,0)                                                                Transação da nota inserida            OPERACIONAL                        NaN
PCINUTILIZARCTE         MENSAGEM VARCHAR2(1000)                                                                    Mensagem de orientação            OPERACIONAL                        NaN
PCINUTILIZARCTE    NUMTENTATIVAS   NUMBER(10,0) Número de tentativas de processamento pelo DocFiscal, para evitar loop e consumo indevido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*