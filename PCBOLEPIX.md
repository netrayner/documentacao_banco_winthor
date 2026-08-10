# 📊 Tabela: PCBOLEPIX

### Estrutura de Colunas e Restrições

   Tabela               Coluna  Tipo/Tamanho                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBOLEPIX            CODFILIAL   VARCHAR2(2)                               Código da filial do titulo a receber            OPERACIONAL                        NaN
PCBOLEPIX               CODCLI   NUMBER(9,0)                              Código do cliente do titulo a receber            OPERACIONAL                        NaN
PCBOLEPIX        NUMTRANSVENDA  NUMBER(10,0) Número de transação da nota de saída vinculada ao titulo a receber            OPERACIONAL                        NaN
PCBOLEPIX                PREST   VARCHAR2(2)                            Número da prestação do titulo a receber            OPERACIONAL                        NaN
PCBOLEPIX            QRCODEPIX          CLOB                                         QrCode gerado pelo bolepix            OPERACIONAL                        NaN
PCBOLEPIX           COPIAECOLA          CLOB                         Copia e Cola gerado pelo bolepix em base64            OPERACIONAL                        NaN
PCBOLEPIX      NUMTRANSBOLEPIX  VARCHAR2(50)                   Número de transação única do bolepix junto a API            OPERACIONAL                        NaN
PCBOLEPIX       NUMTRANSSHIPAY  VARCHAR2(50)             Número de transação único vinculado a SHIPAY com a API            OPERACIONAL                        NaN
PCBOLEPIX            DTBOLEPIX  TIMESTAMP(6)                           Data de geração e atualização do bolepix            OPERACIONAL                        NaN
PCBOLEPIX        STATUSBOLEPIX  VARCHAR2(30)                       Status do bolepix: ENVIADO, GERADO, IMPRESSO            OPERACIONAL                        NaN
PCBOLEPIX           ARQUIVOB64          CLOB                                    PDF gerado do bolepix em base64            OPERACIONAL                        NaN
PCBOLEPIX      NOSSONUMBOLEPIX  NUMBER(14,0)                                     Nosso número gerado no bolepix    CHAVE PRIMÁRIA (PK)                        NaN
PCBOLEPIX             LINHADIG VARCHAR2(100)                                  Linha digitável gerado no bolepix            OPERACIONAL                        NaN
PCBOLEPIX             CODBARRA  VARCHAR2(44)                                  Código de barra gerado no bolepix            OPERACIONAL                        NaN
PCBOLEPIX           LOGGERACAO          CLOB             Log com a informação do processo de geração do bolepix            OPERACIONAL                        NaN
PCBOLEPIX        STATUSRETORNO  VARCHAR2(30)                                          Status do bolepix gerado             OPERACIONAL                        NaN
PCBOLEPIX             LOGBAIXA          CLOB                     Mensagem de log ao executar a baixa do bolepix            OPERACIONAL                        NaN
PCBOLEPIX     FORMARECEBIMENTO  VARCHAR2(30)                                    Forma de recebimento do bolepix            OPERACIONAL                        NaN
PCBOLEPIX MENSAGEMPROCESSADORA          CLOB                       Mensagem recebida da processadora do bolepix            OPERACIONAL                        NaN
PCBOLEPIX      MENSAGEMTECHFIN          CLOB                                      Mensagem recebida da techfin             OPERACIONAL                        NaN
PCBOLEPIX                VPAGO  NUMBER(14,2)                                              Valor pago do bolepix            OPERACIONAL                        NaN
PCBOLEPIX                DTPAG          DATE                                       Data do pagamento do bolepix            OPERACIONAL                        NaN
PCBOLEPIX        DATAEXPIRACAO  TIMESTAMP(6)                                       Data de expiração do bolepix            OPERACIONAL                        NaN
PCBOLEPIX           NSUBOLEPIX VARCHAR2(100)                                       Numero sequencial do bolepix            OPERACIONAL                        NaN
PCBOLEPIX       NOSSONUMEROBCO  VARCHAR2(30)                                       Descrição coluna NOSSONUMBCO            OPERACIONAL                        NaN
PCBOLEPIX      REFERENCENUMBER VARCHAR2(100)                                   Descricao coluna REFERENCENUMBER            OPERACIONAL                        NaN
PCBOLEPIX             DTCANCEL          DATE                                    Data de cancelamento do Bolepix            OPERACIONAL                        NaN
PCBOLEPIX      LOGCANCELAMENTO          CLOB                   Grava a o resultado do processo de cancelamento.            OPERACIONAL                        NaN
PCBOLEPIX            CODCOBPIX   VARCHAR2(4)                           Código de cobrança da geração do bolepix            OPERACIONAL                        NaN
PCBOLEPIX          CODBANCOPIX   NUMBER(4,0)                                  Código do banco gerado no bolepix            OPERACIONAL                        NaN
PCBOLEPIX              TXJUROS   NUMBER(6,2)  Taxa de juros obtida da cobrança no momento da geração do bolepix            OPERACIONAL                        NaN
PCBOLEPIX            PERCMULTA   NUMBER(7,4)  Taxa de multa obtida da cobrança no momento da geração do bolepix            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*