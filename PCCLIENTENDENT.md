# 📊 Tabela: PCCLIENTENDENT

### Estrutura de Colunas e Restrições

        Tabela           Coluna   Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIENTENDENT           CODCLI    NUMBER(6,0)                                Código Cliente.    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTENDENT     CODENDENTCLI    NUMBER(6,0)                    Código Endereço de Entrega.    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTENDENT     CODBAIRROENT    NUMBER(6,0)                      Código Bairro de Entrega.            OPERACIONAL                        NaN
PCCLIENTENDENT        BAIRROENT   VARCHAR2(40)                             Bairro de entrega.            OPERACIONAL                        NaN
PCCLIENTENDENT         MUNICENT   VARCHAR2(15)                          Município de entrega.            OPERACIONAL                        NaN
PCCLIENTENDENT           ESTENT    VARCHAR2(2)                             Estado de entrega.            OPERACIONAL                        NaN
PCCLIENTENDENT           CEPENT    VARCHAR2(9)                                Cep de Entrega.            OPERACIONAL                        NaN
PCCLIENTENDENT         ENDERENT   VARCHAR2(40)                           Endereço de entrega.            OPERACIONAL                        NaN
PCCLIENTENDENT   COMPLEMENTOENT   VARCHAR2(60)                        Complemento de entrega.            OPERACIONAL                        NaN
PCCLIENTENDENT      CODPRACAENT    NUMBER(6,0)                      Código praça de entrega .            OPERACIONAL                        NaN
PCCLIENTENDENT        NUMEROENT    VARCHAR2(6)                  Número do endereço de entrega            OPERACIONAL                        NaN
PCCLIENTENDENT     CODMUNICIPIO   NUMBER(10,0)                            Código do municipio            OPERACIONAL                        NaN
PCCLIENTENDENT        CODCIDADE    NUMBER(6,0)                               Código da cidade            OPERACIONAL                        NaN
PCCLIENTENDENT       PONTOREFER   VARCHAR2(80)                            Ponto de referência            OPERACIONAL                        NaN
PCCLIENTENDENT        LONGITUDE   VARCHAR2(20)                                      Longitude            OPERACIONAL                        NaN
PCCLIENTENDENT         LATITUDE   VARCHAR2(20)                                       Latitude            OPERACIONAL                        NaN
PCCLIENTENDENT       DTEXCLUSAO           DATE           Data de exclusão endereço de entrega            OPERACIONAL                        NaN
PCCLIENTENDENT       CODFUNCCAD    NUMBER(8,0)            Código do funcionário que cadastrou            OPERACIONAL                        NaN
PCCLIENTENDENT  CODFUNCULTALTER    NUMBER(8,0)       Código do último funcionário que alterou            OPERACIONAL                        NaN
PCCLIENTENDENT            DTCAD           DATE                               Data do cadastro            OPERACIONAL                        NaN
PCCLIENTENDENT       DTULTALTER           DATE                       Data da última alteração            OPERACIONAL                        NaN
PCCLIENTENDENT       OBSERVACAO VARCHAR2(4000)                                     OBSERVAÇÃO            OPERACIONAL                        NaN
PCCLIENTENDENT        NUMREGIAO    NUMBER(4,0)                                            NaN            OPERACIONAL                        NaN
PCCLIENTENDENT         FANTASIA  VARCHAR2(100)      Identificação da empresa onde é a entrega            OPERACIONAL                        NaN
PCCLIENTENDENT        CODSEQEND    NUMBER(8,0) Código sequencial de identificação de endereço            OPERACIONAL                        NaN
PCCLIENTENDENT   DTSYNCPATHFIND           DATE Indica a Data de Sincronização com o Path Find            OPERACIONAL                        NaN
PCCLIENTENDENT    FONERECEBEDOR   NUMBER(14,0)                             Telefone Recebedor            OPERACIONAL                        NaN
PCCLIENTENDENT CODPAISRECEBEDOR    NUMBER(6,0)                                    Codigo Pais            OPERACIONAL                        NaN
PCCLIENTENDENT   RAZAORECEBEDOR   VARCHAR2(60)                                   Razão Social            OPERACIONAL                        NaN
PCCLIENTENDENT   EMAILRECEBEDOR   VARCHAR2(60)                                         E-mail            OPERACIONAL                        NaN
PCCLIENTENDENT     CEPRECEBEDOR    VARCHAR2(9)                                  CEP Recebedor            OPERACIONAL                        NaN
PCCLIENTENDENT       DTMXSALTER           DATE                                            NaN            OPERACIONAL                        NaN
PCCLIENTENDENT   APELIDOUNIDADE VARCHAR2(4000)                                            NaN            OPERACIONAL                        NaN
PCCLIENTENDENT      IERECEBEDOR   NUMBER(15,0)                                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*