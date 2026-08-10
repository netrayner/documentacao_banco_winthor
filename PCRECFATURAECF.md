# 📊 Tabela: PCRECFATURAECF

### Estrutura de Colunas e Restrições

        Tabela             Coluna Tipo/Tamanho                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECFATURAECF           NUMCUPOM NUMBER(10,0)                                                                   Número do cupom.    CHAVE PRIMÁRIA (PK)                        NaN
PCRECFATURAECF      NUMSERIEEQUIP VARCHAR2(30)                                                                   Número de série.    CHAVE PRIMÁRIA (PK)                        NaN
PCRECFATURAECF          CODFILIAL  VARCHAR2(2)                                                                  Código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCRECFATURAECF               DATA         DATE                                                                              Data.    CHAVE PRIMÁRIA (PK)                        NaN
PCRECFATURAECF          CODFUNCCX NUMBER(10,0)                                                             Código do funcionário.    CHAVE PRIMÁRIA (PK)                        NaN
PCRECFATURAECF      NUMTRANSVENDA NUMBER(10,0)                                                      Número da transação de venda.            OPERACIONAL                        NaN
PCRECFATURAECF          NUMPEDECF NUMBER(10,0)                                                                  Número do Pedido.            OPERACIONAL                        NaN
PCRECFATURAECF           NUMCAIXA  NUMBER(4,0)                                                                   Número do Caixa.    CHAVE PRIMÁRIA (PK)                        NaN
PCRECFATURAECF                NSU VARCHAR2(20)                                                         Número de Sequência Único.            OPERACIONAL                        NaN
PCRECFATURAECF          NUMFATURA VARCHAR2(10)                                                                  Número da Fatura.            OPERACIONAL                        NaN
PCRECFATURAECF              VALOR NUMBER(12,2)                                                                   Valor da Fatura.            OPERACIONAL                        NaN
PCRECFATURAECF          EXPORTADO  VARCHAR2(1)                                                                         Exportado.            OPERACIONAL                        NaN
PCRECFATURAECF       DTEXPORTACAO         DATE                                                                Data de Exportação.            OPERACIONAL                        NaN
PCRECFATURAECF         VENCIMENTO         DATE                                                      Data de Vencimento da fatura.            OPERACIONAL                        NaN
PCRECFATURAECF        DTPAGAMENTO         DATE                                                       Data de pagamento da fatura.            OPERACIONAL                        NaN
PCRECFATURAECF           DESCONTO NUMBER(10,2)                                                                Desconto na fatura.            OPERACIONAL                        NaN
PCRECFATURAECF NUMFECHAMENTOMOVCX NUMBER(10,0)                                                               Numero de fechamento            OPERACIONAL                        NaN
PCRECFATURAECF      DTMOVIMENTOCX         DATE                                                                 Data de fechamento            OPERACIONAL                        NaN
PCRECFATURAECF         TIPOFATURA  VARCHAR2(1)                                Tipo da fatura ('ARRECADACAO', 'TITULO', 'TRIBUTO')            OPERACIONAL                        NaN
PCRECFATURAECF              BANCO  VARCHAR2(1)                                                     Nome do banco do correspodente            OPERACIONAL                        NaN
PCRECFATURAECF      VALORORIGINAL NUMBER(10,2)                                                           Valor original da fatura            OPERACIONAL                        NaN
PCRECFATURAECF     VALORACRESCIMO NUMBER(10,2)                                          Valor de acréscimo informado no pagamento            OPERACIONAL                        NaN
PCRECFATURAECF        CODIGOBARRA VARCHAR2(55)                                              Código de barras usado para pagamento            OPERACIONAL                        NaN
PCRECFATURAECF           NSUSITEF VARCHAR2(20)                                                      NSU da transação de pagamento            OPERACIONAL                        NaN
PCRECFATURAECF    NSUCANCELAMENTO VARCHAR2(20)                                                   NSU da transação de cancelamento            OPERACIONAL                        NaN
PCRECFATURAECF  NSUCBCANCELAMENTO VARCHAR2(20)                                     NSU do correspondente bancário de cancelamento            OPERACIONAL                        NaN
PCRECFATURAECF       ORIGEMFATURA  VARCHAR2(1)                                      Origem da fatura ('WINTHOR','CORRESPONDENTE')            OPERACIONAL                        NaN
PCRECFATURAECF             STATUS  VARCHAR2(1)                                                              Efetuada ou cancelada            OPERACIONAL                        NaN
PCRECFATURAECF        CODIGOAUTCB VARCHAR2(40) Código impresso no rodapé do comprovante e utilizado pra reimpressão/cancelamento;            OPERACIONAL                        NaN
PCRECFATURAECF       VALORORGINAL NUMBER(10,2)                                                                                NaN            OPERACIONAL                        NaN
PCRECFATURAECF  CODOPERRECARGACEL  NUMBER(5,0)                                                                                NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*