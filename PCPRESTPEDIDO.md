# 📊 Tabela: PCPRESTPEDIDO

### Estrutura de Colunas e Restrições

       Tabela            Coluna Tipo/Tamanho                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRESTPEDIDO           NUMNOTA NUMBER(10,0)               NUM. DA NOTA FISCAL DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO             PREST  VARCHAR2(2)                 NUM. DA PRESTAÇÃO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            CODCLI  NUMBER(6,0)                      CÓD. CLIENTE DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO         CODFILIAL  VARCHAR2(2)                       CÓD. FILIAL DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO             NUMCX  NUMBER(8,0)                     NUM. DO CAIXA DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO           CODFUNC  NUMBER(8,0)                  CÓD. FUNCIONÁRIO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO         DTEMISSAO         DATE                   DATA DE EMISSÃO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            DTVENC         DATE                DATA DE VENCIMENTO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO             VALOR NUMBER(10,2)                             VALOR DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO        VLDESCONTO NUMBER(10,2)                 VALOR DO DESCONTO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            VLJURO NUMBER(10,2)                   VALOR DOS JUROS DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            DTPAGO         DATE                 DATA DE PAGAMENTO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO             VPAGO NUMBER(10,2)                        VALOR PAGO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            CODCOB  VARCHAR2(4)                          COBRANÇA DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO           DTFECHA         DATE                DATA DE FECHAMENTO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO               OBS VARCHAR2(40)                              OBS. DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO             VLAUX NUMBER(10,2)                    VALOR AUXILIAR DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO           CODVEND  NUMBER(4,0)                  CÓD. DO VENDEDOR DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO        VLTXBOLETO NUMBER(12,2)                    TAXA DO BOLETO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO          VLLIQCOM NUMBER(14,2)                     VALOR LÍQUIDO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            PERCOM  NUMBER(8,5)            PERCENTUAL DE COMISSÃO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            NUMBCO  NUMBER(4,0)                     NUM. DO BANCO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO             NUMAG  NUMBER(4,0)                   NUM. DA AGÊNCIA DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO             NUMCH  NUMBER(8,0)                    NUM. DO CHEQUE DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            CODSUP  NUMBER(8,0)                CÓD. DO SUPERVISOR DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO               TEF  VARCHAR2(1)                               TEF DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO               POS  VARCHAR2(1)                               POS DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            NSUTEF VARCHAR2(15)                            NSUTEF DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO CODAUTORIZACAOTEF VARCHAR2(13)              CÓD. AUTORIZAÇÃO TEF DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO   TIPOOPERACAOTEF  VARCHAR2(4)                 TIPO OPERAÇÃO TEF DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO        QTPARCELAS  NUMBER(3,0)                      QT. PARCELAS DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO   PARCELAMENTOTEF  VARCHAR2(1)                  PARCELAMENTO TEF DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO          PRESTTEF  NUMBER(2,0)                     PRESTAÇÃO DO TEF FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO      CODADMCARTAO  VARCHAR2(6)                   CÓD. ADM CARTÃO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO    CODBANDEIRATEF  VARCHAR2(5)              CÓD. DA BANDEIRA TEF DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO    FORMAPGTONOECF VARCHAR2(16)              FORMA DE PGTO NO ECF DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO     CONTACORRENTE NUMBER(10,0)                    CONTA CORRENTE DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO      VALORPAGOORI NUMBER(12,2)               VALOR PAGO ORIGINAL DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO            NUMPED NUMBER(10,0)                    NUM. DO PEDIDO DA FORMA DE PAGAMENTO DO PEDIDO.            OPERACIONAL                        NaN
PCPRESTPEDIDO           NUMORCA NUMBER(10,0)                                                NÚMERO DO ORÇAMENTO            OPERACIONAL                        NaN
PCPRESTPEDIDO           NSUHOST VARCHAR2(15) Numero do NSH Host para autorizacao de venda com cartao de credito            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*