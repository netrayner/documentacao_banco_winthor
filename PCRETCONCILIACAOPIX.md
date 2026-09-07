# 📊 Tabela: PCRETCONCILIACAOPIX

### Estrutura de Colunas e Restrições

             Tabela                  Coluna  Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRETCONCILIACAOPIX           CONCILIACAOID  NUMBER(14,0)                                      Identificador da Conciliacao    CHAVE PRIMÁRIA (PK)                        NaN
PCRETCONCILIACAOPIX               CODFILIAL   VARCHAR2(2)                  O Código da Filial a qual a conciliação pertence            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX           NSUPAGDIGITAL  VARCHAR2(50)                         Número identificador da transação PCPREST            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX               CLIENTEID  VARCHAR2(20)                              Identificador do Cliente Retorno TPI            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX             CNPJCLIENTE  VARCHAR2(20)                                                   CNPJ da Empresa            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX           TIPOPAGAMENTO  VARCHAR2(20)                    Tipo do método do Pagamento = PIX , ou EWallet            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX               DTCRIACAO  TIMESTAMP(6)                                                   Data da Criação            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX     DTHORAPROCESSAMENTO  TIMESTAMP(6)                            Data Hora do retorno da Requisição TPI            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX             VLTRANSACAO  NUMBER(10,2)                                          Valor Bruto da Transação            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX            VLDEPOSITADO  NUMBER(10,2)                              Valor Liquido com desconto das taxas            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX                  VLTAXA  NUMBER(10,2)                                          Valor da Taxa / Deduções            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX          TRANSACAOPAGID  VARCHAR2(50)                           Identificador da Transação do pagamento            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX          PROCESSADORAID  VARCHAR2(50)                                        Identificador da Operadora            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX           TRANSACAOEXID  VARCHAR2(50)                                Identificador da Transação Externa            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX                  MOTIVO VARCHAR2(100)                                Descrição do motivo da Conciliação            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX                  STATUS   VARCHAR2(1) Informa se o titulo da conciliação consta baixado ou não (S ou N)            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX          ARQUIVORETORNO          CLOB                                              Arquivo JSON retorno            OPERACIONAL                        NaN
PCRETCONCILIACAOPIX TENTATIVASPROCESSAMENTO   NUMBER(2,0)   Quantidade de tentativas para processar a conciliação do titulo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*