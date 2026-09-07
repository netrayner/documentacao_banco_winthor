# 📊 Tabela: PCVENDACONSUMECF

### Estrutura de Colunas e Restrições

          Tabela                    Coluna  Tipo/Tamanho                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVENDACONSUMECF                      DATA          DATE                                                                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDACONSUMECF                 NUMPEDECF  NUMBER(10,0)                                                                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDACONSUMECF                 CODFUNCCX   NUMBER(8,0)                                                                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDACONSUMECF                  NUMCAIXA   NUMBER(4,0)                                                                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDACONSUMECF                 CODFILIAL   VARCHAR2(2)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF             NUMSERIEEQUIP  VARCHAR2(30)                                                                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDACONSUMECF                  NUMCUPOM  NUMBER(10,0)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                  SERIEECF   VARCHAR2(2)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                    NUMPED  NUMBER(10,0)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                   CLIENTE  VARCHAR2(60)                                                                      Descricao coluna CLIENTE            OPERACIONAL                        NaN
PCVENDACONSUMECF                    CGCENT  VARCHAR2(18)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                  ENDERENT  VARCHAR2(40)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                 BAIRROENT  VARCHAR2(40)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                    TELENT  VARCHAR2(13)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                  MUNICENT  VARCHAR2(16)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                    ESTENT   VARCHAR2(2)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                    CEPENT   VARCHAR2(9)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                     IEENT  VARCHAR2(15)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                       OBS VARCHAR2(100)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF               NOMECONTATO  VARCHAR2(40)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF           TELEFONECONTATO  VARCHAR2(13)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                OBSCONTATO  VARCHAR2(75)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                 IMPORTADO   VARCHAR2(1)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                 EXPORTADO   VARCHAR2(1)                                                                 Flag se a exportação ocorreu.            OPERACIONAL                        NaN
PCVENDACONSUMECF                 CODCIDADE   NUMBER(6,0)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF                     EMAIL VARCHAR2(100)                                                                                           NaN            OPERACIONAL                        NaN
PCVENDACONSUMECF              DTEXPORTACAO          DATE                                                 Data em que a exportação do BD local ocorreu.            OPERACIONAL                        NaN
PCVENDACONSUMECF                 NUMEROENT   VARCHAR2(6)                                                                            Número do endereço            OPERACIONAL                        NaN
PCVENDACONSUMECF                        RG  VARCHAR2(20)                  Caso haja bebida alcoolica na venda será necessário infomar o RG do cliente.            OPERACIONAL                        NaN
PCVENDACONSUMECF                    DTNASC          DATE Caso haja bebida alcoolica na venda será necessário informar a data de nascimento do cliente.            OPERACIONAL                        NaN
PCVENDACONSUMECF IDENTIFICACAO_ESTRANGEIRO  VARCHAR2(20)                                                       Identificação de estrangeiros na venda.            OPERACIONAL                        NaN
PCVENDACONSUMECF           CONSUMIDORFINAL   VARCHAR2(1)                                                          Indica se cliente é consumidor final            OPERACIONAL                        NaN
PCVENDACONSUMECF              CONTRIBUINTE   VARCHAR2(1)                                                              Indica se cliente é contribuinte            OPERACIONAL                        NaN
PCVENDACONSUMECF                ASSINATURA VARCHAR2(256)                                                                                           NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*