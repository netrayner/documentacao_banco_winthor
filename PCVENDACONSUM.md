# 📊 Tabela: PCVENDACONSUM

### Estrutura de Colunas e Restrições

       Tabela                    Coluna  Tipo/Tamanho                                                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVENDACONSUM                    NUMPED  NUMBER(10,0)                                                                                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDACONSUM                   CLIENTE  VARCHAR2(60)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                    CGCENT  VARCHAR2(18)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                  ENDERENT  VARCHAR2(40)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                 BAIRROENT  VARCHAR2(40)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                    TELENT  VARCHAR2(15)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                  MUNICENT  VARCHAR2(15)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                    ESTENT   VARCHAR2(2)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                    CEPENT   VARCHAR2(9)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                     IEENT  VARCHAR2(15)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                       OBS VARCHAR2(100)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM               NOMECONTATO  VARCHAR2(40)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM           TELEFONECONTATO  VARCHAR2(15)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                OBSCONTATO  VARCHAR2(75)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                 CODCIDADE   NUMBER(6,0) Campo ncessário para relacionamento na tabela PCCIDADE, afim de obter a normalização de CIDADE, ESTADO e COD.IBGE.            OPERACIONAL                        NaN
PCVENDACONSUM       DTEXPORTACAOSERVINT          DATE                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM          EXPORTADOSERVINT   VARCHAR2(1)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM        IMPORTADOSERVPRINC   VARCHAR2(1)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM     DTIMPORTACAOSERVPRINC          DATE                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                     EMAIL VARCHAR2(100)                                                                                                                NaN            OPERACIONAL                        NaN
PCVENDACONSUM                 NUMEROENT   VARCHAR2(6)                                                                                                  Número de entrega            OPERACIONAL                        NaN
PCVENDACONSUM                        RG  VARCHAR2(20)                                       Caso haja bebida alcoolica na venda será necessário infomar o RG do cliente.            OPERACIONAL                        NaN
PCVENDACONSUM                    DTNASC          DATE                      Caso haja bebida alcoolica na venda será necessário informar a data de nascimento do cliente.            OPERACIONAL                        NaN
PCVENDACONSUM IDENTIFICACAO_ESTRANGEIRO  VARCHAR2(20)                                                                            Identificação de estrangeiros na venda.            OPERACIONAL                        NaN
PCVENDACONSUM           CONSUMIDORFINAL   VARCHAR2(1)                                                                               Indica se cliente é consumidor final            OPERACIONAL                        NaN
PCVENDACONSUM              CONTRIBUINTE   VARCHAR2(1)                                                                                   Indica se cliente é contribuinte            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*