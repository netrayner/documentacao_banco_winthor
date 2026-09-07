# 📊 Tabela: PCCAIXA

### Estrutura de Colunas e Restrições

 Tabela                      Coluna  Tipo/Tamanho                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCAIXA                    NUMCAIXA   NUMBER(4,0)                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCAIXA                   DESCRICAO  VARCHAR2(40)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                     POSICAO   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                   CODFUNCCX   NUMBER(8,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                    DTINICIO          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                       DTFIM          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA              TIPOIMPRESSORA   VARCHAR2(2)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA             PORTAIMPRESSORA   NUMBER(2,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA               NUMSERIEEQUIP  VARCHAR2(30)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                 PORTALEITOR   NUMBER(2,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA            VERSAOIMPRESSORA  VARCHAR2(40)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA          PERMITEABRIRGAVETA   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA              GAVETAACOPLADA   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                     TIPOTEF   VARCHAR2(4)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA               PORTALEITORCH   NUMBER(2,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                    VALIDACH   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                   NUMREGIAO   NUMBER(4,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                   CODFILIAL   VARCHAR2(2)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                     NUMOPCX   NUMBER(2,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA        TIPOIMPRESSORACHEQUE   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA      VERSAOIMPRESSORACHEQUE   VARCHAR2(5)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA       PORTAIMPRESSORACHEQUE   NUMBER(2,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA              NUMCUPOMABERTO  NUMBER(10,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA             NUMCUPOMFECHADO  NUMBER(10,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA              DIRATUALIZACAO VARCHAR2(200)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                  DEGUSTACAO   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                 TIPOTECLADO   VARCHAR2(5)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                 TIPOBALANCA   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA              SALTARLINHATEF   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA              MSGCUPOMFISCAL  VARCHAR2(40)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                    ADMISSAO          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA              NUMCAIXAFISCAL   NUMBER(4,0)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                      MODELO  VARCHAR2(10)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA         ATUALIZACESTABASICA   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA               ATUALIZAPLANO   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA             ATUALIZAFORMAPG   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA           ATUALIZAEMPREGADO   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA              ATUALIZALAYOUT   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA               ATUALIZASETOR   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA          ATUALIZATRIBUTACAO   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA             ATUALIZACLIENTE   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA        ATUALIZACLIENTEDTINI          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA        ATUALIZACLIENTEDTFIM          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA                 ATUALIZACFO   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA             ATUALIZAPRODUTO   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA        ATUALIZAPRODUTODTINI          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA        ATUALIZAPRODUTODTFIM          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA      ATUALIZAPRECOEMBALAGEM   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA ATUALIZAPRECOEMBALAGEMDTINI          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA ATUALIZAPRECOEMBALAGEMDTFIM          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA         ATUALIZAPRECOREGIAO   VARCHAR2(1)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA    ATUALIZAPRECOREGIAODTINI          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA    ATUALIZAPRECOREGIAODTFIM          DATE                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA             IPSERVIDORSITEF  VARCHAR2(20)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA             CODEMPRESASITEF  VARCHAR2(20)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA               TERMINALSITEF  VARCHAR2(20)                                                                               NaN            OPERACIONAL                        NaN
PCCAIXA     ATUALIZAPCCOMISSAOPLPAG   VARCHAR2(1)                                         Atualizar comissão progressimo por plano.            OPERACIONAL                        NaN
PCCAIXA      ATUALIZAPCCOMISSAOUSUR   VARCHAR2(1)                                           Atualizar comissão progressimo por RCA.            OPERACIONAL                        NaN
PCCAIXA             ITENSCARGAGERAL VARCHAR2(200)                               Itens da carga geral para carga dos dados do caixa.            OPERACIONAL                        NaN
PCCAIXA            DTPROXCARGAGERAL          DATE                          Indica a data da proxima carga geral dos dados no caixa.            OPERACIONAL                        NaN
PCCAIXA             DTULTCARGAGERAL          DATE                           Indica a data da ultima carga geral dos dados no caixa.            OPERACIONAL                        NaN
PCCAIXA           ITENSCARGAPARCIAL VARCHAR2(200)                   Indica os itens da carga parcial para carga dos dados do caixa.            OPERACIONAL                        NaN
PCCAIXA          DTPROXCARGAPARCIAL          DATE                        Indica a data da proxima carga parcial dos dados no caixa.            OPERACIONAL                        NaN
PCCAIXA                 DATAINIPARC          DATE                                            Indica a data inicio da carga parcial.            OPERACIONAL                        NaN
PCCAIXA           DTULTCARGAPARCIAL          DATE                         Indica a data da ultima carga parcial dos dados no caixa.            OPERACIONAL                        NaN
PCCAIXA                 DATAFIMPARC          DATE                                             Indica a data final da carga parcial.            OPERACIONAL                        NaN
PCCAIXA                 CODPRODPARC   NUMBER(6,0)                                                  Indica o código produto parcial.            OPERACIONAL                        NaN
PCCAIXA                  CODCLIPARC   NUMBER(6,0)                                                  Indica o código cliente parcial.            OPERACIONAL                        NaN
PCCAIXA                USAINDICEECF   VARCHAR2(1)                                                  Indica se utiliza indice no ECF.            OPERACIONAL                        NaN
PCCAIXA        BITSPORSEGUNDOLEITOR  VARCHAR2(10)                                                     Indica a velocidade do envio.            OPERACIONAL                        NaN
PCCAIXA           BITSDEDADOSLEITOR  VARCHAR2(10)                                                    Indica a velocidade dos dados.            OPERACIONAL                        NaN
PCCAIXA              PARIDADELEITOR  VARCHAR2(10)                                                      Indica a paridade do leitor.            OPERACIONAL                        NaN
PCCAIXA            RESPSITEFTECLADO   VARCHAR2(1)                                                Indica o retorno da transação TEF.            OPERACIONAL                        NaN
PCCAIXA                    CODBANCO   NUMBER(4,0)                                          Indica o código do banco/caixa checkout.            OPERACIONAL                        NaN
PCCAIXA             USASUFIXOLEITOR   VARCHAR2(1)                                              Indica se gravação do uso de sufixo.            OPERACIONAL                        NaN
PCCAIXA       ATUALIZAPRECOFIMVENDA   VARCHAR2(1)                                Indica se utiliza a carga parcial no fim da venda.            OPERACIONAL                        NaN
PCCAIXA             CONFIRMAR_CARGA   VARCHAR2(1)                                                 Confirmar geração de carga geral.            OPERACIONAL                        NaN
PCCAIXA               NUMUSUARIOECF   NUMBER(4,0)                                                Indica o número do usuário da ECF.            OPERACIONAL                        NaN
PCCAIXA                 VERFIRMWARE  VARCHAR2(15)                                                      Indica a versão do firmware.            OPERACIONAL                        NaN
PCCAIXA              CODNACIONALECF   VARCHAR2(6)                                                  Indica o código nacional do ECF.            OPERACIONAL                        NaN
PCCAIXA                  DTSWBASICO          DATE                                                 Indica a data do software básico.            OPERACIONAL                        NaN
PCCAIXA                DTREINICIOOP          DATE                                            Indica a data de reinício da operação.            OPERACIONAL                        NaN
PCCAIXA                 DTSWUSUARIO          DATE                                             Indica a data de cadastro do usuário.            OPERACIONAL                        NaN
PCCAIXA                   MODELOECF  VARCHAR2(40)                                                    Modelo de Impressora para NFP.            OPERACIONAL                        NaN
PCCAIXA            DTPROXATULIZACAO   NUMBER(4,0)                                             Indica a data da proxima atualização.            OPERACIONAL                        NaN
PCCAIXA            SOLICITARCAVENDA   VARCHAR2(1)                                                               Solicitar RCA Venda            OPERACIONAL                        NaN
PCCAIXA            POSSUIGUILHOTINA   VARCHAR2(1)                                          Utilização de guilhotina pela impressora            OPERACIONAL                        NaN
PCCAIXA                   TIPOCAIXA   VARCHAR2(1)                                                                     Tipo de caixa            OPERACIONAL                        NaN
PCCAIXA                 TIPODECAIXA  VARCHAR2(15)                                                                     Tipo de caixa            OPERACIONAL                        NaN
PCCAIXA                 PROXNUMNFCE  NUMBER(10,0)                                              Numerador do próximo número de NFCe.            OPERACIONAL                        NaN
PCCAIXA      PROXNUMFECHAMENTOMOVCX  NUMBER(10,0)                                                   NUMERO DE MOVIMENTO DO OPERADOR            OPERACIONAL                        NaN
PCCAIXA      PROXNUMNFCEHOMOLOGACAO  NUMBER(10,0)                                                   Próximo número NFCe homologação            OPERACIONAL                        NaN
PCCAIXA               PROXNUMPEDAUX  NUMBER(10,0)                                                  Próx. Número de pedido auxiliar.            OPERACIONAL                        NaN
PCCAIXA               TIPODOCFISCAL  VARCHAR2(20)                                                          Tipo de documento Fiscal            OPERACIONAL                        NaN
PCCAIXA                      NUMSAT   NUMBER(4,0)                                                         Número do cadastro de SAT            OPERACIONAL                        NaN
PCCAIXA                TIPOOPERACAO   VARCHAR2(1)                                                                   Tipo de uso SAT            OPERACIONAL                        NaN
PCCAIXA               PROXNUMDOCSAT  NUMBER(10,0)                                                             Próximo num. Doc. SAT            OPERACIONAL                        NaN
PCCAIXA                 ENDERECOFTP VARCHAR2(200)                                                                      Endereço FTP            OPERACIONAL                        NaN
PCCAIXA                       PORTA  VARCHAR2(10)                                                        Porta para equipamento SAT            OPERACIONAL                        NaN
PCCAIXA              ENDERECOUPLOAD VARCHAR2(200)                                                                Endereço de Upload            OPERACIONAL                        NaN
PCCAIXA            ENDERECODOWNLOAD VARCHAR2(200)                                                              Endereço de Download            OPERACIONAL                        NaN
PCCAIXA                  USUARIOFTP VARCHAR2(200)                                                                       Usuário FTP            OPERACIONAL                        NaN
PCCAIXA                    SENHAFTP  VARCHAR2(50)                                                                         Senha FTP            OPERACIONAL                        NaN
PCCAIXA                 MFADICIONAL   VARCHAR2(1)                                                               MF Adicional do ECF            OPERACIONAL                        NaN
PCCAIXA               NUMEROUSUARIO   VARCHAR2(4)                                                             Número usuário do ECF            OPERACIONAL                        NaN
PCCAIXA                  ROTINALANC  VARCHAR2(48)                                                Última rotina que alterou a tabela            OPERACIONAL                        NaN
PCCAIXA                     TIPOECF  VARCHAR2(10)                                                                       Tipo do ECF            OPERACIONAL                        NaN
PCCAIXA            NUMSERIEPLACAMAE  VARCHAR2(50)                                  Numero de serie da placa mão da maquina do caixa            OPERACIONAL                        NaN
PCCAIXA                 NOMEMAQUINA  VARCHAR2(50)                                                   Nome Maquina utilizada no caixa            OPERACIONAL                        NaN
PCCAIXA         PROXNUMMOVIMENTOPDV  NUMBER(10,0)                                                        NUMERO DE MOVIMENTO DO DPV            OPERACIONAL                        NaN
PCCAIXA               PROXNUMDOCMFE  NUMBER(10,0)                                                    Numero sequencia documento Mfe            OPERACIONAL                        NaN
PCCAIXA                      MD5PAF VARCHAR2(200)                                                 Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN
PCCAIXA            PROXIMONUMPEDECF  NUMBER(10,0)                                           Sequencial de numero do pedido do caixa            OPERACIONAL                        NaN
PCCAIXA          IMPCHEQUEHANDSHAKE  VARCHAR2(15)                                                  Controle fluxo impressora cheque            OPERACIONAL                        NaN
PCCAIXA         IMPCHEQUEVELOCIDADE  NUMBER(10,0)                                       Velocidade de comunicação impressora cheque            OPERACIONAL                        NaN
PCCAIXA   NUMCAIXAFISCALCONTIGENCIA   NUMBER(4,0) Valor utilizado para definir o número de série das NFC-e emitidas em contingência            OPERACIONAL                        NaN
PCCAIXA                 ENDERECOMAC VARCHAR2(100)                                        Endereco MAC da Maquina utilizada no caixa            OPERACIONAL                        NaN
PCCAIXA               MODELO_LEITOR  VARCHAR2(30)                                                                  Modelo do leitor            OPERACIONAL                        NaN
PCCAIXA              CODEMPRESAREDE  VARCHAR2(10)                              Codigo de Cadastro da Filial com a adiquirente Rede.            OPERACIONAL                        NaN
PCCAIXA          IPSERVIDORGATECASH  VARCHAR2(20)                                                           IP do servidor Gatecash            OPERACIONAL                        NaN
PCCAIXA                     NOMEPDV  VARCHAR2(50)                                                                       Nome do PDV            OPERACIONAL                        NaN
PCCAIXA              HASHLICENCAPDV VARCHAR2(250)                                                 Assinatura hash da licença do pdv            OPERACIONAL                        NaN
PCCAIXA                 STATUSSEFAZ   VARCHAR2(3)                                                                   Status da Sefaz            OPERACIONAL                        NaN
PCCAIXA             ASSINATURACAIXA VARCHAR2(255)                                                                               NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*