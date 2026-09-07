# 📊 Tabela: PCCREDENCIAL

### Estrutura de Colunas e Restrições

      Tabela             Coluna   Tipo/Tamanho                                                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCREDENCIAL      CODCREDENCIAL    NUMBER(4,0)                                                                                                                 Código da credencial    CHAVE PRIMÁRIA (PK)                        NaN
PCCREDENCIAL           CLIENTID  VARCHAR2(200)                                                                                                                   CLIENT ID NO BANCO            OPERACIONAL                        NaN
PCCREDENCIAL       CLIENTSECRET  VARCHAR2(200)                                                                                                               CLIENT SECRET NO BANCO            OPERACIONAL                        NaN
PCCREDENCIAL           URITOKEN VARCHAR2(4000)                                                                                                         URI TOKEN ENVIADO PELO BANCO            OPERACIONAL                        NaN
PCCREDENCIAL         URIENVIOCP VARCHAR2(1000)                                                                                                             URI ENVIO CONTAS A PAGAR            OPERACIONAL                        NaN
PCCREDENCIAL       URIRETORNOCP VARCHAR2(1000)                                                                                                           URI RETORNO CONTAS A PAGAR            OPERACIONAL                        NaN
PCCREDENCIAL       UTILIZAAPICP    VARCHAR2(1)                                              UTILIZA INTEGRAÇÃO POR API PARA O CONTAS A PAGAR (H- HOMOLOGAÇÃO, P- PRODUÇÃO, N - NÃO)            OPERACIONAL                        NaN
PCCREDENCIAL   DIRETORIOCRTFILE VARCHAR2(1000)                                                                     Diretorio do arquivo CRT solicitado no certificado da requisicao            OPERACIONAL                        NaN
PCCREDENCIAL   DIRETORIOKEYFILE VARCHAR2(1000)                                                                     Diretorio do arquivo KEY solicitado no certificado da requisicao            OPERACIONAL                        NaN
PCCREDENCIAL       UTILIZAAPIEB    VARCHAR2(1)                                                                                    Utiliza Integração por API para Extrato Bancário             OPERACIONAL                        NaN
PCCREDENCIAL URIEXTRATOBANCARIO VARCHAR2(1000)                                                                                                                 URI Extrato Bancário            OPERACIONAL                        NaN
PCCREDENCIAL      AMBIENTETESTE    VARCHAR2(1) Caso esteja igual a S a busca pela URL do token será realizada no ambiente Sandbox, caso contrário irá validar o campo UTILIZAAPICP.            OPERACIONAL                        NaN
PCCREDENCIAL        CLIENTIDPIX  VARCHAR2(200)                                                                                            CLIENT ID ESPECÍFICO PARA PIX NO BRADESCO            OPERACIONAL                        NaN
PCCREDENCIAL    CLIENTSECRETPIX  VARCHAR2(200)                                                                                        CLIENT SECRET ESPECÍFICO PARA PIX NO BRADESCO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*