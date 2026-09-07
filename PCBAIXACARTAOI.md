# 📊 Tabela: PCBAIXACARTAOI

### Estrutura de Colunas e Restrições

        Tabela                  Coluna   Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBAIXACARTAOI            CODBAIXAITEM   NUMBER(10,0)                                             Código do item da baixa    CHAVE PRIMÁRIA (PK)                        NaN
PCBAIXACARTAOI          CODBAIXACARTAO   NUMBER(10,0)                                        Código do cabeçalho da baixa CHAVE ESTRANGEIRA (FK)             PCBAIXACARTAOC
PCBAIXACARTAOI                 PARCELA    NUMBER(2,0)                                                 Parcela da cobrança            OPERACIONAL                        NaN
PCBAIXACARTAOI               NUMCARTAO   VARCHAR2(30)                                         Número do cartão do cliente            OPERACIONAL                        NaN
PCBAIXACARTAOI            VALORPARCELA   NUMBER(12,6)                                              Valor da Parcela Bruta            OPERACIONAL                        NaN
PCBAIXACARTAOI     VALORPARCELALIQUIDO   NUMBER(18,6)                                            Valor da Parcela Líquida            OPERACIONAL                        NaN
PCBAIXACARTAOI                     NSU   VARCHAR2(15)                                                    Nsu da Transação            OPERACIONAL                        NaN
PCBAIXACARTAOI                 NSUHOST   VARCHAR2(15)                                               Nsu Host da Transação            OPERACIONAL                        NaN
PCBAIXACARTAOI                    DATA           DATE                                                  Data da importação            OPERACIONAL                        NaN
PCBAIXACARTAOI            CODOPERADORA   VARCHAR2(10)                                                 Código da operadora            OPERACIONAL                        NaN
PCBAIXACARTAOI                 NUMLOTE   VARCHAR2(20)                               Número do lote quando tem antecipação            OPERACIONAL                        NaN
PCBAIXACARTAOI                 CODREDE   VARCHAR2(10)                                                      Código da rede            OPERACIONAL                        NaN
PCBAIXACARTAOI             CODBANDEIRA   VARCHAR2(10)                                        Código da bandeira do cartão            OPERACIONAL                        NaN
PCBAIXACARTAOI          CODAUTORIZACAO   VARCHAR2(15)                                     Código da autorização do cartão            OPERACIONAL                        NaN
PCBAIXACARTAOI         DATAANTECIPACAO           DATE                                      Data da antecipação do crédito            OPERACIONAL                        NaN
PCBAIXACARTAOI             DATACREDITO           DATE                                                     Data do crédito            OPERACIONAL                        NaN
PCBAIXACARTAOI             TIPOPRODUTO    VARCHAR2(1)                                                     Tipo do produto            OPERACIONAL                        NaN
PCBAIXACARTAOI                    TAXA   NUMBER(12,6)                                                       Valor da taxa            OPERACIONAL                        NaN
PCBAIXACARTAOI                  DUPLIC   VARCHAR2(10)                                               Duplicata da cobrança            OPERACIONAL                        NaN
PCBAIXACARTAOI                CODBANCO    NUMBER(4,0)                                                      Banco da baixa            OPERACIONAL                        NaN
PCBAIXACARTAOI                SITUACAO   VARCHAR2(60)                                                   Situação da baixa            OPERACIONAL                        NaN
PCBAIXACARTAOI                  MOTIVO   VARCHAR2(60)                                                     Motivo da baixa            OPERACIONAL                        NaN
PCBAIXACARTAOI                  STATUS   VARCHAR2(30)                                                     Status da baixa            OPERACIONAL                        NaN
PCBAIXACARTAOI              VALORATUAL   NUMBER(10,0)                                                Valor atual do campo            OPERACIONAL                        NaN
PCBAIXACARTAOI           VALORANTERIOR   NUMBER(10,0)                                             Valor anterior do campo            OPERACIONAL                        NaN
PCBAIXACARTAOI                 DTBAIXA           DATE                                           Data da baixa dos títulos            OPERACIONAL                        NaN
PCBAIXACARTAOI           NUMTRANSVENDA   NUMBER(10,0)                                        Número da transação da venda            OPERACIONAL                        NaN
PCBAIXACARTAOI                  CODCLI    NUMBER(6,0)                                                   Código do cliente            OPERACIONAL                        NaN
PCBAIXACARTAOI                NUMTRANS   NUMBER(10,0)                         Número da transação do lançamento do título            OPERACIONAL                        NaN
PCBAIXACARTAOI               DTEMISSAO           DATE                                        Data da emissão da prestação            OPERACIONAL                        NaN
PCBAIXACARTAOI                  DTVENC           DATE                                     Data do vencimento da prestação            OPERACIONAL                        NaN
PCBAIXACARTAOI           CODBANCOPREST    VARCHAR2(4)                                     Banco que foi realizado a baixa            OPERACIONAL                        NaN
PCBAIXACARTAOI                  MARGEM    NUMBER(4,2) Campo indica o valor aceito na diferença durante a baixa automatica            OPERACIONAL                        NaN
PCBAIXACARTAOI                NUMCUPOM   NUMBER(10,0)                                     Indica o número do cupom fiscal            OPERACIONAL                        NaN
PCBAIXACARTAOI             IDTRANSACAO   VARCHAR2(30)                                                        Id Transação            OPERACIONAL                        NaN
PCBAIXACARTAOI      CODESTABELECIMENTO   VARCHAR2(15)                                                 Cod.Estabelecimento            OPERACIONAL                        NaN
PCBAIXACARTAOI              CODAGENCIA    VARCHAR2(6)                                                         Cod.Agencia            OPERACIONAL                        NaN
PCBAIXACARTAOI                NUMCONTA   VARCHAR2(20)                                                          Num.Conta             OPERACIONAL                        NaN
PCBAIXACARTAOI             VLRCOMISSAO   NUMBER(16,2)                                  Valor da Comissão da Adminstradora            OPERACIONAL                        NaN
PCBAIXACARTAOI          VLRTAXASERVICO   NUMBER(16,2)                                            Valor da taxa de serviço            OPERACIONAL                        NaN
PCBAIXACARTAOI            CODLOJASITEF    VARCHAR2(8)                                                Codigo da loja Sitef            OPERACIONAL                        NaN
PCBAIXACARTAOI               NUMRESUMO   VARCHAR2(22)                                       Numero do resumo de pagamento            OPERACIONAL                        NaN
PCBAIXACARTAOI          NUMCOMPROVANTE   VARCHAR2(12)                                               Número do Comprovante            OPERACIONAL                        NaN
PCBAIXACARTAOI         QTTOTALPARCELAS    NUMBER(3,0)                                               Qtd.total de parcelas            OPERACIONAL                        NaN
PCBAIXACARTAOI                 CAPTURA    VARCHAR2(1)                                                     Meio de Captura            OPERACIONAL                        NaN
PCBAIXACARTAOI          HORAVENDASITEF    VARCHAR2(6)                                                 Hora venda no Sitef            OPERACIONAL                        NaN
PCBAIXACARTAOI   VLRPARCELALIQUIDOORIG   NUMBER(16,2)                                   Valor original da parcela Liquida            OPERACIONAL                        NaN
PCBAIXACARTAOI         DTVENDAORIGINAL           DATE                                              Data original da venda            OPERACIONAL                        NaN
PCBAIXACARTAOI               HORAVENDA   VARCHAR2(10)                                                       Hora da venda            OPERACIONAL                        NaN
PCBAIXACARTAOI          NUMRESUMOUNICO   VARCHAR2(22)                                              Numero do resumo único            OPERACIONAL                        NaN
PCBAIXACARTAOI           INDARQUIVOREQ    VARCHAR2(1)                                        Indice do arquivo de retorno            OPERACIONAL                        NaN
PCBAIXACARTAOI      SEQREGISTROARQUIVO    VARCHAR2(6)                                             Seq.registro no arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOI            TIPOREGISTRO    VARCHAR2(5)                                         Tipo de Registro do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOI     DATACREDITOORIGINAL           DATE                                            Data original do credito            OPERACIONAL                        NaN
PCBAIXACARTAOI       TIPOPROCESSAMENTO   VARCHAR2(40)                                                  Tipo processamento            OPERACIONAL                        NaN
PCBAIXACARTAOI                     PDV    VARCHAR2(9)                                                      Ponto de venda            OPERACIONAL                        NaN
PCBAIXACARTAOI    R_VLTAXAADMINTRADORA   NUMBER(16,2)                             Valor da taxa administradora do retorno            OPERACIONAL                        NaN
PCBAIXACARTAOI        R_VLRTAXASERVICO   NUMBER(16,2)                                   Valor da taxa seriviço do retorno            OPERACIONAL                        NaN
PCBAIXACARTAOI    R_VLTAXAADIANTAMENTO   NUMBER(16,2)                            Valor da taxa de adiantamento do retorno            OPERACIONAL                        NaN
PCBAIXACARTAOI    S_VLTAXAADMINTRADORA   NUMBER(16,2)                             Valor da taxa administradora do sistema            OPERACIONAL                        NaN
PCBAIXACARTAOI             S_VLPARCELA   NUMBER(16,2)                                        Valor da parcela considarada            OPERACIONAL                        NaN
PCBAIXACARTAOI                  FILLER    VARCHAR2(1)                                                              Filler            OPERACIONAL                        NaN
PCBAIXACARTAOI                   PLANO    VARCHAR2(2)                                                  Plano de pagamento            OPERACIONAL                        NaN
PCBAIXACARTAOI           TIPOTRANSACAO    NUMBER(2,0)                                                      Tipo Transação            OPERACIONAL                        NaN
PCBAIXACARTAOI            DTENVIOBANCO           DATE                                          Data de envio para o banco            OPERACIONAL                        NaN
PCBAIXACARTAOI            SINALVLBRUTO    VARCHAR2(1)                                                Sinal do Valor bruto            OPERACIONAL                        NaN
PCBAIXACARTAOI         SINALVLCOMISSAO    VARCHAR2(1)                                          Sinal do valor da comissão            OPERACIONAL                        NaN
PCBAIXACARTAOI        SINALVLREJEITADO    VARCHAR2(1)                                            sinal do valor rejeitado            OPERACIONAL                        NaN
PCBAIXACARTAOI             VLREJEITADO   NUMBER(16,2)                                                     valor rejeitado            OPERACIONAL                        NaN
PCBAIXACARTAOI          SINALVLLIQUIDO    VARCHAR2(1)                                              sinal do valor liquido            OPERACIONAL                        NaN
PCBAIXACARTAOI         STATUSPAGAMENTO    NUMBER(2,0)                                                 status do pagamento            OPERACIONAL                        NaN
PCBAIXACARTAOI          QTDECVSACEITOS    NUMBER(6,0)                            Quantidade de comprovantes vendas aceito            OPERACIONAL                        NaN
PCBAIXACARTAOI       QTDECVSREJEITADOS    NUMBER(6,0)                        Quantidade de comprovantes vendas rejeitados            OPERACIONAL                        NaN
PCBAIXACARTAOI               IDREVENDA    VARCHAR2(1)                                                       Id da revenda            OPERACIONAL                        NaN
PCBAIXACARTAOI       DTCAPTURATRASACAO           DATE                                        Data de captura da transação            OPERACIONAL                        NaN
PCBAIXACARTAOI            ORIGEMAJUSTE    VARCHAR2(3)                                                    Origem do Ajuste            OPERACIONAL                        NaN
PCBAIXACARTAOI          VLCOMPLEMENTAR   NUMBER(16,2)                                                  Valor complementar            OPERACIONAL                        NaN
PCBAIXACARTAOI     IDPRODUTOFINANCEIRO    VARCHAR2(1)                                            Id do produto financeiro            OPERACIONAL                        NaN
PCBAIXACARTAOI   NUMOPERACAOFINANCEIRA    NUMBER(9,0)                                     Número de operações financeiras            OPERACIONAL                        NaN
PCBAIXACARTAOI  SINALVLBRUTOANTECIPADO    VARCHAR2(1)                                     Sinal do valor bruto antecipado            OPERACIONAL                        NaN
PCBAIXACARTAOI       VLBRUTOANTECIPADO   NUMBER(16,2)                                              Valor bruto antecipado            OPERACIONAL                        NaN
PCBAIXACARTAOI                NUMUNICO   NUMBER(22,0)                                                        Número único            OPERACIONAL                        NaN
PCBAIXACARTAOI                  TARIFA    NUMBER(4,0)                                                              Tarifa            OPERACIONAL                        NaN
PCBAIXACARTAOI              TXGARANTIA    VARCHAR2(2)                                                    taxa de garantia            OPERACIONAL                        NaN
PCBAIXACARTAOI       NUMLOGICOTERMINAL    VARCHAR2(8)                                           Número logico do terminal            OPERACIONAL                        NaN
PCBAIXACARTAOI                USOCIELO   VARCHAR2(18)                                                        Uso da Cielo            OPERACIONAL                        NaN
PCBAIXACARTAOI                     TID   VARCHAR2(20)                                                                 TID            OPERACIONAL                        NaN
PCBAIXACARTAOI               DIGCARTAO    NUMBER(2,0)                                                    Digito do cartao            OPERACIONAL                        NaN
PCBAIXACARTAOI            VLTOTALVENDA   NUMBER(16,2)                                                Valor Total da venda            OPERACIONAL                        NaN
PCBAIXACARTAOI           VLPROXPARCELA   NUMBER(16,2)                                            Valor da próxima parcela            OPERACIONAL                        NaN
PCBAIXACARTAOI        IDCARTAOEXTERIOR    NUMBER(4,0)                                                  Id Cartão Exterior            OPERACIONAL                        NaN
PCBAIXACARTAOI IDTAXAEMBARQUEVLENTRADA    VARCHAR2(2)                                   Id taxa de embarque valor entrada            OPERACIONAL                        NaN
PCBAIXACARTAOI               CODPEDIDO   VARCHAR2(20)                                                    Código do pedido            OPERACIONAL                        NaN
PCBAIXACARTAOI       NUMUNICOTRANSACAO   VARCHAR2(29)                                           Número único da transação            OPERACIONAL                        NaN
PCBAIXACARTAOI         IDENTIFICADORPP    VARCHAR2(1)                                                    Identificador PP            OPERACIONAL                        NaN
PCBAIXACARTAOI                   PREST    VARCHAR2(4)                                                 Prestação do título            OPERACIONAL                        NaN
PCBAIXACARTAOI                   LINHA VARCHAR2(1000)                                      Linha do Arquivo de Importação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*