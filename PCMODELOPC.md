# 📊 Tabela: PCMODELOPC

### Estrutura de Colunas e Restrições

    Tabela                   Coluna   Tipo/Tamanho                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMODELOPC            CODPLANOCONTA    NUMBER(5,0)                                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMODELOPC           CODREDUZIDO_PC   VARCHAR2(12)                                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMODELOPC              CODCONTA_PC   VARCHAR2(40)                                                                                                          NaN            OPERACIONAL                        NaN
PCMODELOPC               NOME_CONTA   VARCHAR2(50)                                                                                                          NaN            OPERACIONAL                        NaN
PCMODELOPC                 NATUREZA        CHAR(1)                                                                                                          NaN            OPERACIONAL                        NaN
PCMODELOPC            NATUREZAGRUPO        CHAR(1)                                                                                                          NaN            OPERACIONAL                        NaN
PCMODELOPC          ULT_CODREDUZIDO    NUMBER(5,0)                                                                                                          NaN            OPERACIONAL                        NaN
PCMODELOPC            RECEBE_LANCTO        CHAR(1)                                                                                                          NaN            OPERACIONAL                        NaN
PCMODELOPC                CODFORNEC    NUMBER(6,0)                   Indica se a Conta Contábil é Analítica de Fornecedor, e qual o Fornecedor ela referencia.             OPERACIONAL                        NaN
PCMODELOPC              CODCONTAGER   NUMBER(10,0)                                       Relaciona o plano de contas contábil com o plano de contas gerencial.             OPERACIONAL                        NaN
PCMODELOPC            COMPORBALANCO    VARCHAR2(1)                                                                   Indica as contas que vão compor o balanco.            OPERACIONAL                        NaN
PCMODELOPC           CONTARESULTADO    VARCHAR2(1)                                                                                 Indica a conta de resultado.            OPERACIONAL                        NaN
PCMODELOPC                TIPOCONTA    VARCHAR2(1)                                                                                      Indica o tipo de conta.            OPERACIONAL                        NaN
PCMODELOPC            CODCONTA_SPED   VARCHAR2(20)                                                     Indica o código da conta do plano de contas referencial.            OPERACIONAL                        NaN
PCMODELOPC                   CODCLI    NUMBER(6,0)                                                                                  Indica o código do cliente.            OPERACIONAL                        NaN
PCMODELOPC              COMPORFCONT    VARCHAR2(1)                                                                                          Conta compõe FCONT.            OPERACIONAL                        NaN
PCMODELOPC               OBSERVACAO VARCHAR2(4000)                                                                      Observação sobre a utilização da conta.            OPERACIONAL                        NaN
PCMODELOPC                   CODRCA   NUMBER(10,0)                                                                        Código RCA vinculado à conta contábil            OPERACIONAL                        NaN
PCMODELOPC           USACENTROCUSTO    VARCHAR2(1)                                                                     Determina se a conta usa Centro de Custo            OPERACIONAL                        NaN
PCMODELOPC                COMPORDFC    VARCHAR2(1)                                                                                                  Compõe DFC.            OPERACIONAL                        NaN
PCMODELOPC         CODCONTA_SPEDECF   VARCHAR2(20)                                                             Indica a conta SPED ECF relacionada àquela conta            OPERACIONAL                        NaN
PCMODELOPC        TIPOPLANOCONTAREF    VARCHAR2(2)                                                                             Indica o tipo do plano de contas            OPERACIONAL                        NaN
PCMODELOPC              CODSPEDI053    NUMBER(5,0)                                                                               Codigo da natureza da subconta            OPERACIONAL                        NaN
PCMODELOPC   CODSUBCONTACORRELATADA   VARCHAR2(50)                                                                            Codigo da subconta da correlatada            OPERACIONAL                        NaN
PCMODELOPC          COMPORLALURLACS    VARCHAR2(1)                       Quando 'S' a rotina 2138 usará a conta como filtro na lista de lançamentos e de saldos            OPERACIONAL                        NaN
PCMODELOPC              COMPOE_DMPL    VARCHAR2(1)                                                                              Define se a conta compôS a DMPL            OPERACIONAL                        NaN
PCMODELOPC              COMPOE_DLPA    VARCHAR2(1)                                                                              Define se a conta compôS a DLPA            OPERACIONAL                        NaN
PCMODELOPC           LOTEIMPORTACAO   NUMBER(10,0) Campo usando para rastrear um lote de importação feito pela rotina 2127, este valor vem da DFSEQ_IMPCONTABIL            OPERACIONAL                        NaN
PCMODELOPC     RECEBE_LANCTO_MANUAL    VARCHAR2(1)      Indica se a Conta Contábil pode receber lançamento manual: (S/N) (obs: é dependente de RECEBE_LANCTO=S)            OPERACIONAL                        NaN
PCMODELOPC         USACENTRORECEITA    VARCHAR2(1)                                                  Valida se a conta contabil utiliza ou não centro de receita            OPERACIONAL                        NaN
PCMODELOPC CODREDUZIDO_PC_VINCULADO   VARCHAR2(12)                                                                            Conta vínculada ao plano de conta            OPERACIONAL                        NaN
PCMODELOPC  CODPLANOCONTA_VINCULADO    NUMBER(5,0)                                                                           Código do plano de conta vínculado            OPERACIONAL                        NaN
PCMODELOPC            ANO_VINCULADO    NUMBER(4,0)                                                           Rerente ao ano anterior a troca de plano de contas            OPERACIONAL                        NaN
PCMODELOPC       COMPOE_LIVRO_CAIXA    VARCHAR2(1)                                                                       Indica se a conta compõe o livro caixa            OPERACIONAL                        NaN
PCMODELOPC               DATAULTALT           DATE                                                Indica a data em que foi efetuada a última alteração na conta            OPERACIONAL                        NaN
PCMODELOPC             DATAINCLUSAO           DATE                                                           Indica a data em que a conta foi criada no sistema            OPERACIONAL                        NaN
PCMODELOPC  CODAGLUTINACAO_ANTERIOR  VARCHAR2(100)                   Código referente a identificação da conta no ECD enviado pelo cliente anterior ao Winthor.            OPERACIONAL                        NaN
PCMODELOPC            LIVROAUXTIPOA    VARCHAR2(2)                     Define se a conta compõe o Livro Auxiliar do Tipo A para a escrituração do tipo R no ECD            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*