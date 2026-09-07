# 📊 Tabela: PCORDEMSERVICO

### Estrutura de Colunas e Restrições

        Tabela               Coluna  Tipo/Tamanho                                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORDEMSERVICO                NUMOS   NUMBER(6,0)                                                                             Indica o número ordem de serviço.    CHAVE PRIMÁRIA (PK)                        NaN
PCORDEMSERVICO               CODCOB   VARCHAR2(4)                                                                                  Indica o código de cobrança.            OPERACIONAL                        NaN
PCORDEMSERVICO             CODPLPAG   NUMBER(4,0)                                                                           Indica o código plano de pagamento.            OPERACIONAL                        NaN
PCORDEMSERVICO               CODCLI   NUMBER(6,0)                                                                                   Indica o código do cliente.            OPERACIONAL                        NaN
PCORDEMSERVICO               CODRCA   NUMBER(6,0)                                                                                          Indica o código RCA.            OPERACIONAL                        NaN
PCORDEMSERVICO          CODEMITENTE   NUMBER(8,0)                                                                                     Indica o código emitente.            OPERACIONAL                        NaN
PCORDEMSERVICO           DTCADASTRO          DATE                                                                                    Indica a data de cadastro.            OPERACIONAL                        NaN
PCORDEMSERVICO             SITUACAO   NUMBER(1,0)                                                                                         Indica a situação OS.            OPERACIONAL                        NaN
PCORDEMSERVICO           DTPREVTERM          DATE                                                                             Indica a data previsão término. .            OPERACIONAL                        NaN
PCORDEMSERVICO               TIPOOS   NUMBER(6,0)                                                                                             Indica o tipo OS.            OPERACIONAL                        NaN
PCORDEMSERVICO            CODFILIAL   VARCHAR2(2)                                                                                      Indica o código filial .            OPERACIONAL                        NaN
PCORDEMSERVICO    NUMTRANSVENDASERV  NUMBER(10,0)                                                               Indica o número da transação de venda serviços.            OPERACIONAL                        NaN
PCORDEMSERVICO    NUMTRANSVENDAPROD  NUMBER(10,0)                                                               Indica o número da transação de venda produtos.            OPERACIONAL                        NaN
PCORDEMSERVICO               NUMPED  NUMBER(10,0)                                                                           Indica o número do pedido de venda.            OPERACIONAL                        NaN
PCORDEMSERVICO              DTFECHA          DATE                                                                                  Indica a data de fechamento.            OPERACIONAL                        NaN
PCORDEMSERVICO             DTCANCEL          DATE                                                                                Indica a data de cancelamento.            OPERACIONAL                        NaN
PCORDEMSERVICO         MOTIVOCANCEL VARCHAR2(200)                                                                                 Indica o motivo cancelamento.            OPERACIONAL                        NaN
PCORDEMSERVICO                  OBS VARCHAR2(200)                                                                     Indica a observação da orderm de serviço.            OPERACIONAL                        NaN
PCORDEMSERVICO         CODPRODPRINC   NUMBER(6,0)                                                                         Indica o código do produto principal.            OPERACIONAL                        NaN
PCORDEMSERVICO             NUMSERIE  VARCHAR2(30)                                                                         Indica o código do produto principal.            OPERACIONAL                        NaN
PCORDEMSERVICO        NUMOSPRIMARIA   NUMBER(6,0)                                                                      Indica o número da ordem de serviço pai.            OPERACIONAL                        NaN
PCORDEMSERVICO NUMTRANVENDACOMODATO  NUMBER(10,0) Campo para armazenar o número de transação da remessa de comodato que é gerada ao faturar a ordem de serviço.            OPERACIONAL                        NaN
PCORDEMSERVICO  NUMTRANSDEVCOMODATO  NUMBER(10,0)                               Campo para armazenar o número de transação da remessa de devolução de comodato.            OPERACIONAL                        NaN
PCORDEMSERVICO      REMESSACOMODATO  NUMBER(10,0)               Campo para armazenar o número da remessa de comodato que o funcionário irá instalar no cliente.            OPERACIONAL                        NaN
PCORDEMSERVICO      GERADAAUTOMATIC   VARCHAR2(1)                                        Campo para armazenar se a ordem de serviço foi gerada automaticamente.            OPERACIONAL                        NaN
PCORDEMSERVICO  NUMCONTRATOCOMODATO   NUMBER(8,0)                               Campo para armazenar o número de transação da remessa de devolução de comodato.            OPERACIONAL                        NaN
PCORDEMSERVICO       DATAEXPORTACAO          DATE                                                            Armazena a data de exportação da ordem de serviço.            OPERACIONAL                        NaN
PCORDEMSERVICO                   KM  NUMBER(10,0)                                                                                                            km            OPERACIONAL                        NaN
PCORDEMSERVICO         CODOSVEICULO   NUMBER(6,0)                                                                                                código veiculo            OPERACIONAL                        NaN
PCORDEMSERVICO          NUMNOTAPREF  NUMBER(18,0)                                                                                    Número da NF da Prefeitura            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*