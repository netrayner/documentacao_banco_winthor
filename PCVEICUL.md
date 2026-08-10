# 📊 Tabela: PCVEICUL

### Estrutura de Colunas e Restrições

  Tabela              Coluna  Tipo/Tamanho                                                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVEICUL          CODVEICULO   NUMBER(4,0)                                                                                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVEICUL           DESCRICAO  VARCHAR2(40)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL               PLACA  VARCHAR2(10)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL               MARCA  VARCHAR2(20)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL            QTPALETE   NUMBER(4,0)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL              VOLUME  NUMBER(10,4)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL         PESOCARGAKG  NUMBER(10,2)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL        PESOCARGAKG2  NUMBER(10,2)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL            SITUACAO   VARCHAR2(1)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL         TIPOVEICULO   VARCHAR2(1)                                                                                                             Tipo veiculo            OPERACIONAL                        NaN
PCVEICUL             PROPRIO   VARCHAR2(1)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL           CODFILIAL   VARCHAR2(2)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL       VALORKMRODADO  NUMBER(10,4)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL              ALTURA  NUMBER(10,3)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL             LARGURA  NUMBER(10,3)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL         COMPRIMENTO  NUMBER(10,3)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL            VLDIARIA  NUMBER(10,2)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL                 OBS  VARCHAR2(50)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL       CODFUNCALTSIT   NUMBER(8,0)                                                                                                                      NaN            OPERACIONAL                        NaN
PCVEICUL           RASTREADO   VARCHAR2(1) Campo (S ou N), para indicar se a rota possui rastreamento, caso esteja marcada (S), na montagem de carga ou faturamento            OPERACIONAL                        NaN
PCVEICUL      CODLOCALIZACAO   NUMBER(8,0)      Indica a localização do veículo, que poderá ser alterado no cadastro, no registro de saída ou entrada de veículos.             OPERACIONAL                        NaN
PCVEICUL             MEDIAKM  NUMBER(12,2)                                                                        Valor médio de quilômetros rodados pelo veículo.             OPERACIONAL                        NaN
PCVEICUL           KMINICIAL  NUMBER(12,2)        Quilometragem do veículo no momento da sua compra. Usado para ter noção da quantidade de quilômetros já rodados.             OPERACIONAL                        NaN
PCVEICUL             KMATUAL  NUMBER(12,2)                                                                                         Quilometragem atual do veículo.             OPERACIONAL                        NaN
PCVEICUL             QTEIXOS   NUMBER(2,0)                                                                              Quantidade de eixos existentes no veículo.             OPERACIONAL                        NaN
PCVEICUL             QTRODAS   NUMBER(2,0)                                                                                         Quantidade de rodas do veículo.             OPERACIONAL                        NaN
PCVEICUL           QTTANQUES   NUMBER(2,0)                                                                        Quantidade de tanques de combustível no veículo.             OPERACIONAL                        NaN
PCVEICUL            QTLITROS   NUMBER(6,2)                                                               Capacidade de litros do tanque de combustível do veículo.             OPERACIONAL                        NaN
PCVEICUL           ULTVIAGEM   NUMBER(6,0)                                                             Número do Carregamento da última viagem feita pelo veículo.             OPERACIONAL                        NaN
PCVEICUL              CHASSI  VARCHAR2(25)                                                                                            Código do Chassi do veículo.             OPERACIONAL                        NaN
PCVEICUL                 COR  VARCHAR2(20)                                                                                            Descrição da Cor do veículo.             OPERACIONAL                        NaN
PCVEICUL                OBS2 VARCHAR2(120)                                                              Espaço para informar observações diversas sobre o veículo.             OPERACIONAL                        NaN
PCVEICUL        CODROTAPRINC   NUMBER(4,0)                                                                                       Indica o código da rota principal.            OPERACIONAL                        NaN
PCVEICUL          PRIORIDADE   NUMBER(2,0)                                                                                         Indica prioridade de utilização.            OPERACIONAL                        NaN
PCVEICUL    NOMEPROPRIETARIO VARCHAR2(150)                                                                                Indica nome/razão social do proprietário.            OPERACIONAL                        NaN
PCVEICUL                ANTT  VARCHAR2(20)                                                                               Agência nacional de transporte terrestres.            OPERACIONAL                        NaN
PCVEICUL           CODFORNEC   NUMBER(6,0)                                                                             Cód. da transportadora vinculada ao veículo.            OPERACIONAL                        NaN
PCVEICUL              VLFIXO  NUMBER(12,2)                                                                                                     Vl. fixo de entrega.            OPERACIONAL                        NaN
PCVEICUL               VLPED  NUMBER(12,2)                                                                                               Vl. de entrega por pedido.            OPERACIONAL                        NaN
PCVEICUL             VALORKG  NUMBER(18,6)                                                                                          Valor pago por kilo de produto.            OPERACIONAL                        NaN
PCVEICUL         CODIGORNTRC  VARCHAR2(30)                                                                                             Registro Nacional de Transp.            OPERACIONAL                        NaN
PCVEICUL      UFPLACAVEICULO   VARCHAR2(2)                                                                                                  UF da placa do veículo.            OPERACIONAL                        NaN
PCVEICUL  CIDADEPLACAVEICULO  VARCHAR2(30)                                                                                              Cidade da placa do veículo.            OPERACIONAL                        NaN
PCVEICUL  CGCCPFPROPRIETARIO  VARCHAR2(15)                                                                             Indica o número do CNPJ/CPF do proprietário.            OPERACIONAL                        NaN
PCVEICUL        TIPOVEICULO2   VARCHAR2(2)                                                                                                             Tipo veiculo            OPERACIONAL                        NaN
PCVEICUL        TIPOVEICUEDI   NUMBER(3,0)                                                                                             Tipo de veiculo (EDI Fiscal)            OPERACIONAL                        NaN
PCVEICUL             RENAVAM  VARCHAR2(11)                                                                                                       Renavam do veiculo            OPERACIONAL                        NaN
PCVEICUL          TIPORODADO   VARCHAR2(2)                                                                                                           Tipo de rodado            OPERACIONAL                        NaN
PCVEICUL      TIPOCARROCERIA   VARCHAR2(2)                                                                                                       Tipo da carroceria            OPERACIONAL                        NaN
PCVEICUL      IEPROPRIETARIO  VARCHAR2(14)                                                                                       Inscrição Estadual do proprietario            OPERACIONAL                        NaN
PCVEICUL      UFPROPRIETARIO   VARCHAR2(2)                                                                                                       UF do proprietario            OPERACIONAL                        NaN
PCVEICUL    TIPOPROPRIETARIO   NUMBER(1,0)                                                                                                     Tipo do proprietario            OPERACIONAL                        NaN
PCVEICUL IDINTEGRACAOMYFROTA           RAW                                                                                    Identifica a integração com My Frota.            OPERACIONAL                        NaN
PCVEICUL      CODTIPOVEICULO   NUMBER(3,0)                                                                       Código do tipo de veiculo para Custo de Transporte            OPERACIONAL                        NaN
PCVEICUL         COMBUSTIVEL  VARCHAR2(10)                                                                Qual o combustivel do veículo: Gasolina, Diesel ou Álcool            OPERACIONAL                        NaN
PCVEICUL    COMBUSTIVELATIVO   VARCHAR2(1)                                                                  Informa se o combústivel é Ativo ("S") ou Inativo ("N")            OPERACIONAL                        NaN
PCVEICUL       CONSUMOPADRAO   NUMBER(6,3)                                                                                          Consumo estimado para o veículo            OPERACIONAL                        NaN
PCVEICUL   CONTROLEACUMULADO  NUMBER(10,1)                                                                                        Informa o controle de combustivel            OPERACIONAL                        NaN
PCVEICUL   CONTROLEDECONSUMO   VARCHAR2(1)                                                                                    Se utiliza controle de consumo ou não            OPERACIONAL                        NaN
PCVEICUL  DATAINICIOCONTROLE          DATE                                                                                    Data de inicio do controle de consumo            OPERACIONAL                        NaN
PCVEICUL  CONTROLEUSOINICIAL  NUMBER(10,1)                                                                                               Valor de inicio do consumo            OPERACIONAL                        NaN
PCVEICUL    HODOMETROINICIAL  NUMBER(10,1)                                                                                                     Kilometragem inicial            OPERACIONAL                        NaN
PCVEICUL       TIPODECONSUMO  VARCHAR2(30)                                                                                               Tipo de consumo do veículo            OPERACIONAL                        NaN
PCVEICUL     RETERFRETEAUTON   VARCHAR2(1)                                          Flag para determinar se haverá retenção de imposto autônomo no serviço de frete            OPERACIONAL                        NaN
PCVEICUL         IDSOFITVIEW  VARCHAR2(20)                                                                                  Indica o código do veículo na SofitView            OPERACIONAL                        NaN
PCVEICUL DTULTALTERSOFITVIEW          DATE                                                                Indica a data que o veículo foi integrado com a SofitView            OPERACIONAL                        NaN
PCVEICUL DTEXCLUSAOSOFITVIEW          DATE                                                                   Indica a data que o veículo foi inativado na SofitView            OPERACIONAL                        NaN
PCVEICUL          DTMXSALTER          DATE                                                                                                                      NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*