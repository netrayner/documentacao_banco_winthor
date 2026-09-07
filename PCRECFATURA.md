# 📊 Tabela: PCRECFATURA

### Estrutura de Colunas e Restrições

     Tabela             Coluna Tipo/Tamanho                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECFATURA               DATA         DATE                                                                    Data de Fatura.            OPERACIONAL                        NaN
PCRECFATURA          CODFUNCCX  NUMBER(8,0)                                                              Funcionário Checkout.            OPERACIONAL                        NaN
PCRECFATURA           NUMCAIXA  NUMBER(4,0)                                                                   Número do Caixa.            OPERACIONAL                        NaN
PCRECFATURA      NUMSERIEEQUIP VARCHAR2(30)                                                              Série do Equipamento.            OPERACIONAL                        NaN
PCRECFATURA          NUMPEDECF NUMBER(10,0)                                                              Número do Pedido ECF.            OPERACIONAL                        NaN
PCRECFATURA          NUMCARTAO VARCHAR2(20)                                                                  Número do Cartão.            OPERACIONAL                        NaN
PCRECFATURA              VALOR NUMBER(12,2)                                                                   Valor da Fatura.            OPERACIONAL                        NaN
PCRECFATURA             CODCLI  NUMBER(6,0)                                                       Código do Cliente da fatura.            OPERACIONAL                        NaN
PCRECFATURA          CODFILIAL  VARCHAR2(2)                                                        Código da Filial da Fatura.            OPERACIONAL                        NaN
PCRECFATURA           NUMCUPOM  NUMBER(6,0)                                                            Número do Cupom Fiscal.            OPERACIONAL                        NaN
PCRECFATURA                NSU VARCHAR2(20)                                                                        NSU fatura.            OPERACIONAL                        NaN
PCRECFATURA          NUMFATURA VARCHAR2(10)                                                                  Número da Fatura.            OPERACIONAL                        NaN
PCRECFATURA      NUMTRANSVENDA NUMBER(10,0)                                                               Número da transação.            OPERACIONAL                        NaN
PCRECFATURA          EXPORTADO  VARCHAR2(1)                                                                  Dados exportados.            OPERACIONAL                        NaN
PCRECFATURA       DTEXPORTACAO         DATE                                                                Data da Exportação.            OPERACIONAL                        NaN
PCRECFATURA         VENCIMENTO         DATE                                                                Data de Vencimento.            OPERACIONAL                        NaN
PCRECFATURA        DTPAGAMENTO         DATE                                                                 Data de Pagamento.            OPERACIONAL                        NaN
PCRECFATURA        CONSOLIDADO  VARCHAR2(1)                                                                       Consolidado.            OPERACIONAL                        NaN
PCRECFATURA           DESCONTO NUMBER(10,2)                                                                     Valor desconto            OPERACIONAL                        NaN
PCRECFATURA NUMFECHAMENTOMOVCX NUMBER(10,0)                                                               Numero de fechamento            OPERACIONAL                        NaN
PCRECFATURA      DTMOVIMENTOCX         DATE                                                                 Data de fechamento            OPERACIONAL                        NaN
PCRECFATURA         TIPOFATURA  VARCHAR2(1)                                Tipo da fatura ('ARRECADACAO', 'TITULO', 'TRIBUTO')            OPERACIONAL                        NaN
PCRECFATURA              BANCO  VARCHAR2(1)                                                     Nome do banco do correspodente            OPERACIONAL                        NaN
PCRECFATURA      VALORORIGINAL NUMBER(10,2)                                                           Valor original da fatura            OPERACIONAL                        NaN
PCRECFATURA     VALORACRESCIMO NUMBER(10,2)                                          Valor de acréscimo informado no pagamento            OPERACIONAL                        NaN
PCRECFATURA        CODIGOBARRA VARCHAR2(55)                                              Código de barras usado para pagamento            OPERACIONAL                        NaN
PCRECFATURA           NSUSITEF VARCHAR2(20)                                                      NSU da transação de pagamento            OPERACIONAL                        NaN
PCRECFATURA    NSUCANCELAMENTO VARCHAR2(20)                                                   NSU da transação de cancelamento            OPERACIONAL                        NaN
PCRECFATURA  NSUCBCANCELAMENTO VARCHAR2(20)                                     NSU do correspondente bancário de cancelamento            OPERACIONAL                        NaN
PCRECFATURA       ORIGEMFATURA  VARCHAR2(1)                                      Origem da fatura ('WINTHOR','CORRESPONDENTE')            OPERACIONAL                        NaN
PCRECFATURA             STATUS  VARCHAR2(1)                                                              Efetuada ou cancelada            OPERACIONAL                        NaN
PCRECFATURA        CODIGOAUTCB VARCHAR2(40) Código impresso no rodapé do comprovante e utilizado pra reimpressão/cancelamento;            OPERACIONAL                        NaN
PCRECFATURA       VALORORGINAL NUMBER(10,2)                                                                                NaN            OPERACIONAL                        NaN
PCRECFATURA  CODOPERRECARGACEL  NUMBER(5,0)                                                                                NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*