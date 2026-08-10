# 📊 Tabela: PCSUPPLIRETSOLICITACAO

### Estrutura de Colunas e Restrições

                Tabela                    Coluna  Tipo/Tamanho                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPPLIRETSOLICITACAO                    BAIRRO VARCHAR2(100)                                                                  Bairro do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                       CEP   VARCHAR2(8)                                                                     CEP do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO             CHAVEACESSONF  VARCHAR2(50)                                                     Chave de acesso da Nota Fiscal            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                    CIDADE  VARCHAR2(20)                                                                  Cidade do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                   CNPJCPF  VARCHAR2(14)                                                                CNPJ/CPF do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO         CODIGOAUTORIZACAO  VARCHAR2(14)                                                              Código de autorização            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO             CODIGOEMPRESA   VARCHAR2(2)                                                                  Código da empresa            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO               COMPLEMENTO  VARCHAR2(15)                                                            Complemento do endereço            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO     CONDICAOFINANCIAMENTO   VARCHAR2(9)                                                          Condição de financiamento            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO   DATAFATURAMENTOPARCEIRO          DATE                                                     Data de faturamento no cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO               DATARETORNO          DATE                                                         Data de retorno do arquivo            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                       DDD   VARCHAR2(3)                                                         DDD do telefone do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                DDDCELULAR   VARCHAR2(3)                                                          DDD do celular do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO           DIASPRORROGACAO  NUMBER(22,0)                                                                Dias de prorrogação            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                     EMAIL  VARCHAR2(50)                                                                   Email do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                        ID  NUMBER(22,0)                                                                    Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCSUPPLIRETSOLICITACAO             MOTIVORETORNO   VARCHAR2(3)                                                       Motivo do retorno do arquivo            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO              NOMEFANTASIA  VARCHAR2(25)                                                           Nome fantasia do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO NOSSONUMEROIMPRESSOBOLETO  VARCHAR2(14)                                                             Nosso número do boleto            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO        NOVADATAVENCIMENTO          DATE                                                            Nova data de vencimento            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                    NUMERO   VARCHAR2(5)                                                      Número do endereço do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO             NUMEROCELULAR   VARCHAR2(8)                                                       Número do celular do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO   NUMEROPARCELAPRORROGADA  NUMBER(22,0)                                                       Número da parcela prorrogada            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO           NUMEROTRANSACAO  VARCHAR2(14)                                                                Número da transação            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                OBSERVACAO VARCHAR2(100)                                                                         Observação            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO  ORIGEMALTERACAOCADASTRAL   NUMBER(1,0)                       Podendo ser 0-Parceiro 1-Central de Atendimento Suppliercard            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO        QUANTIDADEPARCELAS   NUMBER(2,0)                                                             Quantidade de parcelas            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO               RAZAOSOCIAL  VARCHAR2(40)                                                            Razão social do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                   RETORNO  VARCHAR2(30)                             Podendo ser 01-Atendida, 02-Encaminhada e 03-Rejeitada            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                       RUA  VARCHAR2(40)                                                                     Rua do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                  TELEFONE  VARCHAR2(15)                                                      Telefone comercial do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO               TIPOCLIENTE   VARCHAR2(5)                                    Chave estrangeira da tabela PCSUPPLITIPOCLIENTE            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO            TIPOREQUISICAO   VARCHAR2(2)                                                      Tipo de requisição do arquivo            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO               TIPORETORNO   VARCHAR2(2) Podendo ser 02-Retorno de concessão de cartão e 03-Retorno de alteração de limites            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO                        UF   VARCHAR2(2)                                                                      UF do cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO           VALORFINANCIADO  NUMBER(16,4)                                                                   Valor financiado            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO           VALORLANCAMENTO  NUMBER(16,4)                                                                Valor do lançamento            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO          VALORPAGOCLIENTE  NUMBER(16,4)                                                            Valor pago pelo cliente            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO              VALORPARCELA  NUMBER(16,4)                                                                   Valor da parcela            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO        VALORSALDOEMABERTO  NUMBER(16,4)                                                           Valor do saldo em aberto            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO               VALORTARIFA  NUMBER(16,4)                                                                    Valor da tarifa            OPERACIONAL                        NaN
PCSUPPLIRETSOLICITACAO VENCIMENTOPRIMEIRAPARCELA          DATE                                             Data de vencimento da primeira parcela            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*