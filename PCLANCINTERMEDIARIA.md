# 📊 Tabela: PCLANCINTERMEDIARIA

### Estrutura de Colunas e Restrições

             Tabela               Coluna   Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLANCINTERMEDIARIA            CODFILIAL    VARCHAR2(2)                                                          Código Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCLANCINTERMEDIARIA       NUMTRANSLANCTO   NUMBER(38,0)                                                       Número transação.    CHAVE PRIMÁRIA (PK)                        NaN
PCLANCINTERMEDIARIA               NUMSEQ   NUMBER(10,0)                                                     Indica a sequência.    CHAVE PRIMÁRIA (PK)                        NaN
PCLANCINTERMEDIARIA           DATALANCTO           DATE                                            Indica a data do lançamento.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA            DOCUMENTO   VARCHAR2(60)                                                     Indica o documento.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA         CODHISTORICO    NUMBER(4,0)                                           Indica o código do histórico.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA      HISTORICO_COMPL  VARCHAR2(200)                                        Indica o histórico complementar.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA        CODPLANOCONTA    NUMBER(5,0)                                        Indica o código plano de contas.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA       CODREDUZIDO_PC   VARCHAR2(12)                                            Indica o código reduzido PC.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA             NATUREZA    VARCHAR2(1)                     Indica a natureza de ser C (crédito) ou D (débito).            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA                VALOR   NUMBER(22,2)                                                         Indica o valor.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA          NUMLOTECONT   NUMBER(38,0)                                                Indica o número do lote.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA             CODREGRA   NUMBER(10,0)                                               Indica o código da regra.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA             OPERACAO    VARCHAR2(2)                                                      Indica a operação.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA     NUMTRANSOPERACAO   NUMBER(12,0)                                            Indica o número da operação.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA               STATUS    VARCHAR2(1)                                                        Indica o status.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA        DATAALTERACAO           DATE                                             Indica a data da alteração.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA     USUARIOALTERACAO   VARCHAR2(60)                                          Indica o usuário da alteração.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA       INCONSISTENCIA    VARCHAR2(2)                                                Indica a inconsistência.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA    NUMLANCTOCONTABIL   NUMBER(38,0)                                    Indica o número lançamento contábil.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA       DATAINTEGRACAO           DATE                                            Indica a data de integração.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA                 CFOP    NUMBER(8,0)                                            Indica o CFOP do lançamento.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA             CODBANCO    NUMBER(4,0)                                 Indica o código do banco do lançamento.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA             CODMOEDA    VARCHAR2(4)                                 Indica o código da moeda do lançamento.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA         CONTABILIZAR    VARCHAR2(1)                           Indica se o lançamento deve ser contabilizado            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA  NUMTRANSCENTROCUSTO   NUMBER(12,0)                                                Núm. Trans. Centro custo            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA   DATAINTEGRACAOAUTO           DATE     Campo mostra a data que o lançamento foi integrado automaticamente.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA          CODPARCEIRO    NUMBER(8,0)                Código do parceiro que foi feito o lançamento financeiro            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA         TIPOPARCEIRO    VARCHAR2(2)                  Tipo do parceiro que foi feito o lançamento financeiro            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA          CODGRUPOBEM    NUMBER(6,0) Campo usando para rastrear o código do grupo do bem, ativo imobilizado.            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA          CHAVEGESTAO   NUMBER(18,0)                                                  Chave principal gestão            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA       CHAVEGESTAOAUX   VARCHAR2(20)                                                 Chave secundaria gestão            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA              FORMULA VARCHAR2(1000)                                     Formula utilizada na contabilização            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA                CONTA   VARCHAR2(50)                                    Conta prametrizada na contabilização            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA NUMTRANSPCLANCAMENTO   NUMBER(38,0)                                                   Chave da PCLANCAMENTO            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA         TABELAGESTAO   VARCHAR2(50)                                                Nome da tabela da gestão            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA     TIPOMOVIMENTACAO  VARCHAR2(100)                                          Tipo da movimentação da gestão            OPERACIONAL                        NaN
PCLANCINTERMEDIARIA        REGRATOTALIZA    VARCHAR2(2)                                                   Totalizador de regras            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*