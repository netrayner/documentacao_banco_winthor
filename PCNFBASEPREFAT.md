# 📊 Tabela: PCNFBASEPREFAT

### Estrutura de Colunas e Restrições

        Tabela                 Coluna  Tipo/Tamanho                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFBASEPREFAT                ALIQFCP   NUMBER(5,2)                                                Aliquota de FCP (fundo de combate a pobreza)            OPERACIONAL                        NaN
PCNFBASEPREFAT        ALIQINTERNADEST   NUMBER(5,2)                                                   Aliquota de ICMS interna na UF de destino            OPERACIONAL                        NaN
PCNFBASEPREFAT      ALIQINTERORIGPART  NUMBER(18,6)                                                               Valor de ICMS da UF de origem            OPERACIONAL                        NaN
PCNFBASEPREFAT               ALIQUOTA   NUMBER(5,2)                                                                           Valor da aliquota            OPERACIONAL                        NaN
PCNFBASEPREFAT                CODCONT  NUMBER(10,0)                                                                    Código da conta contábil            OPERACIONAL                        NaN
PCNFBASEPREFAT              CODFISCAL   NUMBER(8,0)                                                                               Código fiscal            OPERACIONAL                        NaN
PCNFBASEPREFAT    DTEXPORTACAOSERVINT          DATE                                                              Data de exportação do servidor            OPERACIONAL                        NaN
PCNFBASEPREFAT  DTIMPORTACAOSERVPRINC          DATE                                                              Data de importação do servidor            OPERACIONAL                        NaN
PCNFBASEPREFAT       EXPORTADOSERVINT   VARCHAR2(1)                                                         Indica se foi exportado do servidor            OPERACIONAL                        NaN
PCNFBASEPREFAT    GERAICMSLIVROFISCAL   VARCHAR2(1)                                                                                  Gera ICMS.            OPERACIONAL                        NaN
PCNFBASEPREFAT     IMPORTADOSERVPRINC   VARCHAR2(1)                                                         Indica se foi importado do servidor            OPERACIONAL                        NaN
PCNFBASEPREFAT            NUMTRANSENT  NUMBER(10,0)                                                              Número de transação de entrada            OPERACIONAL                        NaN
PCNFBASEPREFAT      NUMTRANSPISCOFINS  NUMBER(10,0)                                                          Número de transação de PIS/COFINS.            OPERACIONAL                        NaN
PCNFBASEPREFAT          NUMTRANSVENDA  NUMBER(10,0)                                                                Número de transação de venda            OPERACIONAL                        NaN
PCNFBASEPREFAT        PERCBASEREDPART   NUMBER(5,2)                                                        Redução aplicada na base de Partilha            OPERACIONAL                        NaN
PCNFBASEPREFAT                PERCISS   NUMBER(5,2)                                                  Percentual de ISS de serviço de transporte            OPERACIONAL                        NaN
PCNFBASEPREFAT           PERCPROVPART   NUMBER(5,2)                                                   Percentual provisório de partilha de ICMS            OPERACIONAL                        NaN
PCNFBASEPREFAT            PERCREDCIMS   NUMBER(5,2)                                                                 Porcentagem redução de icms            OPERACIONAL                        NaN
PCNFBASEPREFAT       PERCREDICMSCUSTO   NUMBER(5,2)                                      % de dedução do ICMS do frete FOB no cálculo do custo.            OPERACIONAL                        NaN
PCNFBASEPREFAT              SITTRIBUT   VARCHAR2(3)                                              Código de Situação Tributária de Saída/Entrada            OPERACIONAL                        NaN
PCNFBASEPREFAT           SITTRIBUTIPI   VARCHAR2(3)                                              Código de Situação Tributária de Saída/Entrada            OPERACIONAL                        NaN
PCNFBASEPREFAT                   TIPO   VARCHAR2(1)                                                                                        Tipo            OPERACIONAL                        NaN
PCNFBASEPREFAT                 VLBASE  NUMBER(12,2)                                                                               Valor da base            OPERACIONAL                        NaN
PCNFBASEPREFAT               VLBASENF  NUMBER(12,2)                                                                       Valor da base da nota            OPERACIONAL                        NaN
PCNFBASEPREFAT         VLBASEPARTDEST  NUMBER(18,6)                                                   Valor da base de calculo na Uf de destino            OPERACIONAL                        NaN
PCNFBASEPREFAT             VLCONTABIL  NUMBER(12,2)                                               Valor Contábil para efeito de Cálculo do ICMS            OPERACIONAL                        NaN
PCNFBASEPREFAT              VLFCPPART  NUMBER(18,6)                                                                             Valor do FUNCEP            OPERACIONAL                        NaN
PCNFBASEPREFAT                 VLICMS  NUMBER(12,2)                                                                               Valor do ICMS            OPERACIONAL                        NaN
PCNFBASEPREFAT      VLICMSDIFALIQPART  NUMBER(18,6)                                Valor de ICMS do diferencial de aliquota da partilha de ICMS            OPERACIONAL                        NaN
PCNFBASEPREFAT         VLICMSDIFERIDO  NUMBER(18,6)                                                                     Valor do ICMS Diferido.            OPERACIONAL                        NaN
PCNFBASEPREFAT             VLICMSPART  NUMBER(18,6) Valor de ICMS de partilha (valor que deverá ser utilizado para acrescer o valor do produto)            OPERACIONAL                        NaN
PCNFBASEPREFAT         VLICMSPARTDEST  NUMBER(18,6)                                               Valor do ICMS Interestadual para a UF Destino            OPERACIONAL                        NaN
PCNFBASEPREFAT          VLICMSPARTREM  NUMBER(18,6)                                                 Valor do ICMS de partilha para UF remetente            OPERACIONAL                        NaN
PCNFBASEPREFAT              VLISENTAS  NUMBER(12,2)                                                                               Valor insento            OPERACIONAL                        NaN
PCNFBASEPREFAT               VLMEXIVA  NUMBER(12,2)         Valor de IVA informado para NFs de consumo/imobilizado (quando a NF não tem itens).            OPERACIONAL                        NaN
PCNFBASEPREFAT DATACONSOLIDACAOPREFAT          DATE                                                           Data Consolidação Pré Faturamento            OPERACIONAL                        NaN
PCNFBASEPREFAT     CODBENEFICIOFISCAL  VARCHAR2(10)                                                                  Código do Benefício Fiscal            OPERACIONAL                        NaN
PCNFBASEPREFAT          CODPRODAJUSTE  VARCHAR2(12)                                                   Código de produto para NF-e de ajuste FEM            OPERACIONAL                        NaN
PCNFBASEPREFAT    DESCRICAOPRODAJUSTE VARCHAR2(120)                                                Descrição de produto para NF-e de ajuste FEM            OPERACIONAL                        NaN
PCNFBASEPREFAT          NCMPRODAJUSTE  VARCHAR2(15)                                                      NCM de produto para NF-e de ajuste FEM            OPERACIONAL                        NaN
PCNFBASEPREFAT      UNIDADEPRODAJUSTE   VARCHAR2(6)                                                  Unidade de produto para NF-e de ajuste FEM            OPERACIONAL                        NaN
PCNFBASEPREFAT        VLTOTPRODAJUSTE  NUMBER(18,6)                                                     Valor total bruto para NF de ajuste FEM            OPERACIONAL                        NaN
PCNFBASEPREFAT                 PIBSUF   NUMBER(7,4)                                                                    Alíquota do IBS Estadual            OPERACIONAL                        NaN
PCNFBASEPREFAT              CSTIBSCBS   VARCHAR2(3)                                                    Código da Situação Tributária do IBS/CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT             CCLASSTRIB   VARCHAR2(6)                                               Código da Classificação Tributária do IBS/CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT                    VBC  NUMBER(15,2)                                                    Valor da Base de cálculo comum a IBS/CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT                 VIBSUF  NUMBER(15,2)                                                           Valor do IBS de competência da UF            OPERACIONAL                        NaN
PCNFBASEPREFAT                PIBSMUN   NUMBER(7,4)                                                                   Alíquota do IBS Municipal            OPERACIONAL                        NaN
PCNFBASEPREFAT                VIBSMUN  NUMBER(15,2)                                                    Valor do IBS de competência do município            OPERACIONAL                        NaN
PCNFBASEPREFAT                   PCBS   NUMBER(7,4)                                                                             Alíquota da CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT                   VCBS  NUMBER(15,2)                                                                                Valor da CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT         PREDALIQ_IBSUF   NUMBER(7,4)                          Percentual da redução de Alíquota do cClassTrib referente ao IBSUF            OPERACIONAL                        NaN
PCNFBASEPREFAT        PALIQEFET_IBSUF   NUMBER(7,4)                        Alíquota efetiva do IBS de competência das UF que referente ao IBSUF            OPERACIONAL                        NaN
PCNFBASEPREFAT        PREDALIQ_IBSMUN   NUMBER(7,4)                         Percentual da redução de Alíquota do cClassTrib referente ao IBSMUN            OPERACIONAL                        NaN
PCNFBASEPREFAT       PALIQEFET_IBSMUN   NUMBER(7,4)                       Alíquota efetiva do IBS de competência das UF que referente ao IBSMUN            OPERACIONAL                        NaN
PCNFBASEPREFAT           PREDALIQ_CBS   NUMBER(7,4)                            Percentual da redução de Alíquota do cClassTrib referente ao CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT          PALIQEFET_CBS   NUMBER(7,4)                          Alíquota efetiva do IBS de competência das UF que referente ao CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT             CSTTRIBREG   VARCHAR2(3)                                                  Código de Situação Tributária do IBS e CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT          CCLASSTRIBREG   VARCHAR2(6)                                             Código de Classificação Tributária do IBS e CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT      PALIQEFETREGIBSUF   NUMBER(7,4)                                                              Valor da alíquota do IBS da UF            OPERACIONAL                        NaN
PCNFBASEPREFAT          VTRIBREGIBSUF  NUMBER(15,2)                                                               Valor do Tributo do IBS da UF            OPERACIONAL                        NaN
PCNFBASEPREFAT     PALIQEFETREGIBSMUN   NUMBER(7,4)                                                       Valor da alíquota do IBS do Município            OPERACIONAL                        NaN
PCNFBASEPREFAT         VTRIBREGIBSMUN  NUMBER(15,2)                                                        Valor do Tributo do IBS do Município            OPERACIONAL                        NaN
PCNFBASEPREFAT        PALIQEFETREGCBS   NUMBER(7,4)                                                                    Valor da alíquota da CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT            VTRIBREGCBS  NUMBER(15,2)                                                                     Valor do Tributo da CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT            SOMATOTALNF   VARCHAR2(1)                                    Informar se novos impostos serão somados ao total da nf.            OPERACIONAL                        NaN
PCNFBASEPREFAT             PALIQIBSUF   NUMBER(7,4)                                                                Alíquota IBS da UF utilizada            OPERACIONAL                        NaN
PCNFBASEPREFAT             VTRIBIBSUF  NUMBER(15,2)                                   Valor do Tributo do IBS da UF Valor que seria devido a UF            OPERACIONAL                        NaN
PCNFBASEPREFAT            PALIQIBSMUN   NUMBER(7,4)                                                         Alíquota IBS do Município utilizada            OPERACIONAL                        NaN
PCNFBASEPREFAT            VTRIBIBSMUN  NUMBER(15,2)                    Valor do Tributo do Município da UF  Valor que seria devido ao Município            OPERACIONAL                        NaN
PCNFBASEPREFAT               PALIQCBS   NUMBER(7,4)                                                               Alíquota IBS do CBS utilizada            OPERACIONAL                        NaN
PCNFBASEPREFAT               VTRIBCBS  NUMBER(15,2)                                       Valor do Tributo da CBS  Valor que seria devido a CBS            OPERACIONAL                        NaN
PCNFBASEPREFAT             VLTOTALIBS  NUMBER(15,2)                                                                             Valor Total IBS            OPERACIONAL                        NaN
PCNFBASEPREFAT     DFEREF_CHAVEACESSO  VARCHAR2(44)                                                             Chave do documento referenciado            OPERACIONAL                        NaN
PCNFBASEPREFAT           DFEREF_NITEM   NUMBER(3,0)                                                             NITEMXML documento referenciado            OPERACIONAL                        NaN
PCNFBASEPREFAT            NITEMDOCREF  NUMBER(38,0)                               Armazena o NITEMXML correspondente ao item da NF referenciada            OPERACIONAL                        NaN
PCNFBASEPREFAT            CHAVEDOCREF  VARCHAR2(60)                                       Armazena a Chave da NF-e ou CT-e da nota referenciada            OPERACIONAL                        NaN
PCNFBASEPREFAT            VIBSESTCRED  NUMBER(15,2)                                                                Valor IBS Estorno de Crédito            OPERACIONAL                        NaN
PCNFBASEPREFAT            VCBSESTCRED  NUMBER(15,2)                                                                Valor CBS Estorno de Crédito            OPERACIONAL                        NaN
PCNFBASEPREFAT        CTSUBSTITDEICMS   VARCHAR2(1)                                            Conhecimento Transporte com Substituição de ICMS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*