# 📊 Tabela: PCLOGLANCAMENTO

### Estrutura de Colunas e Restrições

         Tabela             Coluna  Tipo/Tamanho                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGLANCAMENTO       CODALTERACAO  NUMBER(10,0)                                                                                Indica o código da alteração.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGLANCAMENTO          CODFILIAL   VARCHAR2(2)                                                                               Indica a filial do lançamento.            OPERACIONAL                        NaN
PCLOGLANCAMENTO     NUMTRANSLANCTO  NUMBER(38,0)                                                                                Indica o código da transação.            OPERACIONAL                        NaN
PCLOGLANCAMENTO           OPERACAO   VARCHAR2(1)                                                                                  Indica o tipo de alteração.            OPERACIONAL                        NaN
PCLOGLANCAMENTO            USUARIO  VARCHAR2(50)                                                                                 Indica o usuário do Winthor.            OPERACIONAL                        NaN
PCLOGLANCAMENTO          NUMLANCTO  NUMBER(38,0)                                                                               Indica o número do lançamento.            OPERACIONAL                        NaN
PCLOGLANCAMENTO       DTHREXCLUSAO          DATE                                                                            Indica a data e hora de exclusão.            OPERACIONAL                        NaN
PCLOGLANCAMENTO             NUMSEQ  NUMBER(10,0)                                                                            Indica a sequência do lançamento.            OPERACIONAL                        NaN
PCLOGLANCAMENTO      DTHRALTERACAO          DATE                                                                              Indica a data e hora alteração.            OPERACIONAL                        NaN
PCLOGLANCAMENTO                MES   NUMBER(2,0)                                                                                  Indica o mês do lançamento.            OPERACIONAL                        NaN
PCLOGLANCAMENTO     CODREDUZIDO_PC  VARCHAR2(12)                                                                           Indica o código reduzido anterior.            OPERACIONAL                        NaN
PCLOGLANCAMENTO              VALOR  NUMBER(22,2)                                                                                              Indica o valor.            OPERACIONAL                        NaN
PCLOGLANCAMENTO           NATUREZA   VARCHAR2(1)                                                                                           Indica a natureza.            OPERACIONAL                        NaN
PCLOGLANCAMENTO       CODHISTORICO   NUMBER(4,0)                                                                                Indica o código do histórico.            OPERACIONAL                        NaN
PCLOGLANCAMENTO    HISTORICO_COMPL VARCHAR2(200)                                                                             Indica o histórico complementar.            OPERACIONAL                        NaN
PCLOGLANCAMENTO          DOCUMENTO  VARCHAR2(60)                                                                                          Indica o documento.            OPERACIONAL                        NaN
PCLOGLANCAMENTO               LOTE  VARCHAR2(38)                                                                                    Indica o número do lote .            OPERACIONAL                        NaN
PCLOGLANCAMENTO             DTLANC          DATE                                                                        Indica a data do lançamento contábil.            OPERACIONAL                        NaN
PCLOGLANCAMENTO         TIPOLANCTO   VARCHAR2(1)                                                                                 Indica o tipo de lançamento.            OPERACIONAL                        NaN
PCLOGLANCAMENTO CODREGRAINTEGRACAO  NUMBER(10,0)                                                                      Indica o código da regra de integração.            OPERACIONAL                        NaN
PCLOGLANCAMENTO            MAQUINA  VARCHAR2(64)                                                                                          Máquina que excluiu            OPERACIONAL                        NaN
PCLOGLANCAMENTO           PROGRAMA  VARCHAR2(64)                                                                                         Programa que excluiu            OPERACIONAL                        NaN
PCLOGLANCAMENTO        USUARIOREDE  VARCHAR2(30)                                                                                                          NaN            OPERACIONAL                        NaN
PCLOGLANCAMENTO                ANO   NUMBER(4,0)                                                                                            Ano do lançamento            OPERACIONAL                        NaN
PCLOGLANCAMENTO    CODFILIALIMPORT   VARCHAR2(2)                                                       Filial de Importação pela 2123. Lançamentos Contábeis.            OPERACIONAL                        NaN
PCLOGLANCAMENTO   CODFUNCALTERACAO   NUMBER(8,0)                                                                                           Código funcionário            OPERACIONAL                        NaN
PCLOGLANCAMENTO  CODFUNCINTEGRACAO   NUMBER(8,0)                                                                                 Cód. Funcionário integração.            OPERACIONAL                        NaN
PCLOGLANCAMENTO        CODGRUPOBEM   NUMBER(6,0)                                      Campo usando para rastrear o código do grupo do bem, ativo imobilizado.            OPERACIONAL                        NaN
PCLOGLANCAMENTO   CODLOGINTEGRACAO  NUMBER(38,0)                                                                                        Código log integração            OPERACIONAL                        NaN
PCLOGLANCAMENTO        CODPARCEIRO   NUMBER(8,0)                                                     Código do parceiro que foi feito o lançamento financeiro            OPERACIONAL                        NaN
PCLOGLANCAMENTO      CODPLANOCONTA   NUMBER(5,0)                                                                                    Código do plano de contas            OPERACIONAL                        NaN
PCLOGLANCAMENTO        COMPORFCONT   VARCHAR2(2)                                                                                     Lançamento compõe FCONT.            OPERACIONAL                        NaN
PCLOGLANCAMENTO         CONCILIADO   VARCHAR2(1)                                                               Indica se o lançamento esta ou não conciliado.            OPERACIONAL                        NaN
PCLOGLANCAMENTO     DATAINTEGRACAO          DATE                                                                                             Data integração.            OPERACIONAL                        NaN
PCLOGLANCAMENTO          ENCERRADO       CHAR(1)                                                                                     Indica se esta encerrado            OPERACIONAL                        NaN
PCLOGLANCAMENTO           EXCLUIDO       CHAR(1)                                                                                      Indica se esta excluido            OPERACIONAL                        NaN
PCLOGLANCAMENTO     LOTEIMPORTACAO  NUMBER(10,0) Campo usando para rastrear um lote de importação feito pela rotina 2127, este valor vem da DFSEQ_IMPCONTABIL            OPERACIONAL                        NaN
PCLOGLANCAMENTO     LOTEINTEGRACAO  NUMBER(22,0) Campo usando para rastrear um lote de importação feito pela rotina 2127, este valor vem da DFSEQ_IMPCONTABIL            OPERACIONAL                        NaN
PCLOGLANCAMENTO        MULTIFILIAL   VARCHAR2(1)                                                                                 Lançamento em multi-filiais.            OPERACIONAL                        NaN
PCLOGLANCAMENTO       TIPOPARCEIRO   VARCHAR2(2)                                                       Tipo do parceiro que foi feito o lançamento financeiro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*