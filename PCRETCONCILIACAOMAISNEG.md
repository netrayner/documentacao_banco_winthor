# 📊 Tabela: PCRETCONCILIACAOMAISNEG

### Estrutura de Colunas e Restrições

                 Tabela                     Coluna  Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRETCONCILIACAOMAISNEG              CONCILIACAOID  NUMBER(10,0)                                    Identificação da Conciliação    CHAVE PRIMÁRIA (PK)                        NaN
PCRETCONCILIACAOMAISNEG            DTPROCESSAMENTO  TIMESTAMP(6)                     Data e hora de processamento da Conciliação            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG               LANCAMENTOID VARCHAR2(200)                                     Identificador do lançamento            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                       TIPO  VARCHAR2(10)                                              Tipo de Lançamento            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                 TIPOEVENTO  VARCHAR2(10)                                                  Tipo de evento            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG               DTLANCAMENTO  TIMESTAMP(6)                                               Data da transação            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG               VLLANCAMENTO  NUMBER(12,2)                                      Valor líquido da transação            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                   DTEVENTO  TIMESTAMP(6)                                                    Data da nota            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                CNPJCLIENTE  VARCHAR2(20)                                                 CNPJ do cliente            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG               CNPJPARCEIRO  VARCHAR2(20)                                                CNPJ do Parceiro            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                    NUMNOTA  NUMBER(10,0)                                                Número da nota\t            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG CODIGOTRANSACAOAPROVACAONF  VARCHAR2(20)        Código de transação gerado na aprovação NF pela Supplier            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG           VLTOTALTRANSACAO  NUMBER(12,2)                                             Valor Total da Nota            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG             NUMTOTPARCELAS   VARCHAR2(2)                                         Número total da parcela            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                   PRESTAPI   VARCHAR2(2)                                        Número da parcela do API            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG               VLTOTPARCELA  NUMBER(12,2)                                          Valor total da parcela            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                 DTVENCORIG  TIMESTAMP(6)                                  Vencimento original da parcela            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                     VLTAXA  NUMBER(10,2)                                        Valor da taxa / deduções            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                VLTRANSACAO  NUMBER(12,2)                                        Valor Bruto da Transação            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG              NUMTRANSVENDA  NUMBER(10,0)                                                   Numtransvenda            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                     STATUS   VARCHAR2(1)        Informa se o titulo da conciliação consta baixado ou não            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                     MOTIVO          CLOB                          Descrição do motivo da não conciliação            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG     TENTATIVAPROCESSAMENTO   NUMBER(6,0) Quantidade de tentativas para processar a conciliação do título            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                 DTULTALTER  TIMESTAMP(6)                                      Data e hora da atualização            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                 VLPROVISAO  NUMBER(12,2)                                            Valor bruto provisão            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG             VLTAXAPROVISAO  NUMBER(10,2)                                             Valor Taxa provisão            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG              VLPROVISAOLIQ  NUMBER(12,2)                                          Valor Liquido Provisão            OPERACIONAL                        NaN
PCRETCONCILIACAOMAISNEG                  CODFILIAL   VARCHAR2(2)                                                             NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*