# 📊 Tabela: PCENDERECODELIVERY

### Estrutura de Colunas e Restrições

            Tabela             Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCENDERECODELIVERY          CODFUNCCX   NUMBER(8,0)                                     CODFUNCCX    CHAVE PRIMÁRIA (PK)                        NaN
PCENDERECODELIVERY           NUMCAIXA   NUMBER(4,0)                                      NUMCAIXA    CHAVE PRIMÁRIA (PK)                        NaN
PCENDERECODELIVERY           SITUACAO   VARCHAR2(2)                                      SITUACAO            OPERACIONAL                        NaN
PCENDERECODELIVERY             NUMCAR   NUMBER(8,0)                                        NUMCAR            OPERACIONAL                        NaN
PCENDERECODELIVERY            CPFCNPJ  VARCHAR2(18)                                       CPFCNPJ            OPERACIONAL                        NaN
PCENDERECODELIVERY        NOMECLIENTE  VARCHAR2(60)                                   NOMECLIENTE            OPERACIONAL                        NaN
PCENDERECODELIVERY         LOGRADOURO  VARCHAR2(40)                                    LOGRADOURO            OPERACIONAL                        NaN
PCENDERECODELIVERY             NUMERO   VARCHAR2(6)                                        NUMERO            OPERACIONAL                        NaN
PCENDERECODELIVERY        COMPLEMENTO  VARCHAR2(40)                                   COMPLEMENTO            OPERACIONAL                        NaN
PCENDERECODELIVERY             BAIRRO  VARCHAR2(40)                                        BAIRRO            OPERACIONAL                        NaN
PCENDERECODELIVERY             CIDADE  VARCHAR2(40)                                        CIDADE            OPERACIONAL                        NaN
PCENDERECODELIVERY             ESTADO  VARCHAR2(40)                                        ESTADO            OPERACIONAL                        NaN
PCENDERECODELIVERY                CEP   VARCHAR2(9)                                           CEP            OPERACIONAL                        NaN
PCENDERECODELIVERY           TELEFONE  VARCHAR2(20)                                      TELEFONE            OPERACIONAL                        NaN
PCENDERECODELIVERY         REFERENCIA VARCHAR2(100)                                    REFERENCIA            OPERACIONAL                        NaN
PCENDERECODELIVERY          EMBALADOR  VARCHAR2(30)                                     EMBALADOR            OPERACIONAL                        NaN
PCENDERECODELIVERY           QTCAIXAS   NUMBER(3,0)                                      QTCAIXAS            OPERACIONAL                        NaN
PCENDERECODELIVERY          NUMCAIXAS VARCHAR2(200)                                     NUMCAIXAS            OPERACIONAL                        NaN
PCENDERECODELIVERY          QTVOLRESF   NUMBER(3,0)                                     QTVOLRESF            OPERACIONAL                        NaN
PCENDERECODELIVERY          QTVOLCONG   NUMBER(3,0)                                     QTVOLCONG            OPERACIONAL                        NaN
PCENDERECODELIVERY         CODVEICULO   NUMBER(4,0)                                    CODVEICULO            OPERACIONAL                        NaN
PCENDERECODELIVERY                OBS VARCHAR2(400)                                           OBS            OPERACIONAL                        NaN
PCENDERECODELIVERY MATRICULAMOTORISTA   NUMBER(8,0)                            MATRICULAMOTORISTA            OPERACIONAL                        NaN
PCENDERECODELIVERY          NUMPEDECF  NUMBER(10,0)     Número do pedido da venda feita no caixa.    CHAVE PRIMÁRIA (PK)                        NaN
PCENDERECODELIVERY      HORATENTATIVA   VARCHAR2(5) Hora em que foi feita a tentativa da entrega.            OPERACIONAL                        NaN
PCENDERECODELIVERY     CODBAIRRODELIV   NUMBER(6,0)                 Código do Bairro para entrega            OPERACIONAL                        NaN
PCENDERECODELIVERY          EXPORTADO   VARCHAR2(1)          Indicador se registro foi exportado.            OPERACIONAL                        NaN
PCENDERECODELIVERY        DATAENTREGA          DATE                               Data de entrega            OPERACIONAL                        NaN
PCENDERECODELIVERY  PERIODODIAENTREGA   VARCHAR2(1)                   Período do dia para entrega            OPERACIONAL                        NaN
PCENDERECODELIVERY          CODCIDADE   NUMBER(6,0)                              Codigo da cidade            OPERACIONAL                        NaN
PCENDERECODELIVERY              EMAIL  VARCHAR2(60)                     Email responsavel entrega            OPERACIONAL                        NaN
PCENDERECODELIVERY                 IE  VARCHAR2(15)                            Inscricao Estadual            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*