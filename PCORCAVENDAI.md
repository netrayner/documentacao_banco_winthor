# 📊 Tabela: PCORCAVENDAI

### Estrutura de Colunas e Restrições

      Tabela                   Coluna  Tipo/Tamanho                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORCAVENDAI                  NUMORCA  NUMBER(10,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAI                     DATA          DATE                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                   CODCLI   NUMBER(6,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  CODPROD   NUMBER(6,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAI                  CODUSUR   NUMBER(4,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                       QT  NUMBER(20,6)                                                                 Quantidade do item no orçamento..            OPERACIONAL                        NaN
PCORCAVENDAI                   PVENDA  NUMBER(19,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  PTABELA  NUMBER(19,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                   NUMCAR   NUMBER(8,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  POSICAO   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                       ST  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               VLCUSTOFIN  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              VLCUSTOREAL  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                   PERCOM   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  PERDESC  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  QTFALTA  NUMBER(20,6)                                                         Quantidade da falta do item no orçamento.            OPERACIONAL                        NaN
PCORCAVENDAI                   NUMSEQ  NUMBER(20,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAI                 TIPOPESO   VARCHAR2(1)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                PERCOMTAB   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               PERDESCTAB   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI       NUMEROETIQIMPRESSA   NUMBER(1,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                   REFCOR  VARCHAR2(20)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                   MARGEM  NUMBER(10,2)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               PERDESCAUX   NUMBER(5,2)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               PVENDABASE  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                    CODST   NUMBER(4,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                      IVA   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                ALIQICMS1   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                ALIQICMS2   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                    PAUTA   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              PERCBASERED   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                VLDESCCOM  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               PERDESCCOM  NUMBER(12,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               PERDESCFIN  NUMBER(12,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                VLBONIFIC  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               PERBONIFIC  NUMBER(12,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                VLDESCFIN  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              CUSTOFINEST  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              PERFRETECMV   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI             VLDESCRODAPE  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI            PERCBASEREDST   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI       PERCBASEREDSTFONTE   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              COMPLEMENTO  VARCHAR2(40)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  PERCISS   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                    VLISS  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  PERCIPI  NUMBER(12,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                    VLIPI  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              CODAUXILIAR  NUMBER(20,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              LOCALIZACAO  VARCHAR2(40)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              CODPROMOCAO  VARCHAR2(10)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               PRAZOMEDIO   NUMBER(4,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI         VLDESCICMISENCAO  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                VLREPASSE  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI          CODFILIALRETIRA   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                PERCVENDA   NUMBER(5,2)                                                           Indica o percentual negociado na venda.            OPERACIONAL                        NaN
PCORCAVENDAI         VLDESCPISSUFRAMA  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                PORIGINAL  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              VLCUSTOCONT  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               VLCUSTOREP  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              PERDESCFLEX  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               VLDESCFLEX  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI             PERREDCOMISS  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              VLREDCOMISS  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI         TIPODESCAPLICADO   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                 PBASERCA  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                PESOBRUTO   NUMBER(7,3)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               VLVERBACMV  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI           NUMVERBAREBCMV   NUMBER(6,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                PERCOMSUP   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI          PERREDCOMISSSUP  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI           VLREDCOMISSSUP  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                     QTCX  NUMBER(14,6)                                                                             Quantidade de caixas.            OPERACIONAL                        NaN
PCORCAVENDAI                  QTPECAS  NUMBER(14,6)                                                                              Quantidade de peças.            OPERACIONAL                        NaN
PCORCAVENDAI             PERDESCCUSTO   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  TXVENDA   NUMBER(8,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                CODICMTAB   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI        PERDESCISENTOICMS   NUMBER(4,2)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               PERCOMPROF   NUMBER(6,2)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                ESCANIADO   NUMBER(4,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI            NUMSEQFORMULA  NUMBER(20,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               CODMAQUINA   NUMBER(4,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI           CHAVEPRINCIPAL  VARCHAR2(40)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               CODFORMULA  VARCHAR2(20)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI             CODPRODTINTA  VARCHAR2(40)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  CODBASE  VARCHAR2(40)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI           VOLUMEDESEJADO  NUMBER(12,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI           SIGLAQUALIDADE  VARCHAR2(10)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI              ALTERNATIVO  VARCHAR2(10)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  PVENDA1  NUMBER(18,6)              Valor do preço a vista, para realização de cálculo de comissão sobre preço a vista.             OPERACIONAL                        NaN
PCORCAVENDAI          PERCAGREGADORST   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               QTENTREGUE  NUMBER(16,3)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI            QTENTREGUEAUX  NUMBER(16,3)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI               QTIMEDIATA  NUMBER(16,3)                                                                   Quantidade de Entrega Imediata.            OPERACIONAL                        NaN
PCORCAVENDAI              QTPOSTERIOR  NUMBER(16,3)                                                                  Quantidade de Entrega Posterior.            OPERACIONAL                        NaN
PCORCAVENDAI               QTENTREGAR  NUMBER(16,3)                                                                        Quantidade a ser Entregue.            OPERACIONAL                        NaN
PCORCAVENDAI                QTRETIRA1  NUMBER(16,3)                                                     Quantidade a ser retirada na filial número 1.            OPERACIONAL                        NaN
PCORCAVENDAI                QTRETIRA2  NUMBER(16,3)                                                     Quantidade a ser retirada na filial número 2.            OPERACIONAL                        NaN
PCORCAVENDAI                QTRETIRA3  NUMBER(16,3)                                                     Quantidade a ser retirada na filial número 3.            OPERACIONAL                        NaN
PCORCAVENDAI    PRODDESCRICAOCONTRATO VARCHAR2(300)                                                              Indica a especificação do Contrato.             OPERACIONAL                        NaN
PCORCAVENDAI     GERAGNRE_CNPJCLIENTE   VARCHAR2(1)                                             Campo para definir se a GNRE será paga pelo cliente.             OPERACIONAL                        NaN
PCORCAVENDAI           VLDIFALIQUOTAS  NUMBER(18,6)                                                                  Valor da diferença de aliquotas.            OPERACIONAL                        NaN
PCORCAVENDAI         BASEDIFALIQUOTAS  NUMBER(18,6)                                                                Base da diferença entre alíquotas.            OPERACIONAL                        NaN
PCORCAVENDAI         PERCDIFALIQUOTAS   NUMBER(8,4)                                                            Percentual de diferença de tributação.            OPERACIONAL                        NaN
PCORCAVENDAI              TIPOENTREGA   VARCHAR2(2)                     Indica o tipo de entrega do Produto. (RP-Retira posterior/EN-Entrega Normal.             OPERACIONAL                        NaN
PCORCAVENDAI           PVENDAANTERIOR  NUMBER(18,6)                                                                Indica o preço de venda anterior.             OPERACIONAL                        NaN
PCORCAVENDAI          PERDESCPOLITICA   NUMBER(8,2)                                                        Indica o percentual de desconto política.             OPERACIONAL                        NaN
PCORCAVENDAI           VLDESCCUSTOCMV  NUMBER(12,4)                                                                        Valor desconto custo CMV.             OPERACIONAL                        NaN
PCORCAVENDAI            VLDESCSUFRAMA  NUMBER(18,6)                                                                          Valor desconto suframa.             OPERACIONAL                        NaN
PCORCAVENDAI            STCLIENTEGNRE  NUMBER(18,6)                                                                           Valor ST cliente GNRE.             OPERACIONAL                        NaN
PCORCAVENDAI                   BRINDE   VARCHAR2(1)                                                                                  Item de brinde.             OPERACIONAL                        NaN
PCORCAVENDAI                 BASEICST  NUMBER(18,6)                                                                              Base de cálculo ST.             OPERACIONAL                        NaN
PCORCAVENDAI              LETRACOMISS   VARCHAR2(2)                                                             Letra de comissão por lucratividade.             OPERACIONAL                        NaN
PCORCAVENDAI               EANCODPROD  NUMBER(14,0)                                                                     Código EAN item do contrato.             OPERACIONAL                        NaN
PCORCAVENDAI            VLVERBACMVCLI  NUMBER(18,6)                                                                      Valor verba CMV do cliente.             OPERACIONAL                        NaN
PCORCAVENDAI                EXPORTADO   VARCHAR2(1)                                            STATUS DO REGISTRO, INDICA SE O REGISTRO FOI EXPORTADO            OPERACIONAL                        NaN
PCORCAVENDAI             DTEXPORTACAO          DATE                                                                   Data de exportação do orçamento            OPERACIONAL                        NaN
PCORCAVENDAI      POLITICAPRIORITARIA   VARCHAR2(1)                                                  Indica que a política de desconto é prioritária.            OPERACIONAL                        NaN
PCORCAVENDAI                QTUNITEMB  NUMBER(18,6)                                                         Indica a quantidade uitaria da embalagem.            OPERACIONAL                        NaN
PCORCAVENDAI              TRUNCARITEM   VARCHAR2(1)                                                          Indica se trunca o varlor total do item.            OPERACIONAL                        NaN
PCORCAVENDAI                  PERCOM2   NUMBER(8,4)                                                       Indica a comissão do primeiro profissional.            OPERACIONAL                        NaN
PCORCAVENDAI                  PERCOM3   NUMBER(8,4)                                                        Indica a comissão do segundo profissional.            OPERACIONAL                        NaN
PCORCAVENDAI                  PERCOM4   NUMBER(8,4)                                                       Indica a comissão do terceiro profissional.            OPERACIONAL                        NaN
PCORCAVENDAI                 TIPOMERC   VARCHAR2(2)                                                                               Tipo de Mercadoria.            OPERACIONAL                        NaN
PCORCAVENDAI              NUMSEQCESTA  NUMBER(20,0)                                                              Número de sequência da cesta básica.            OPERACIONAL                        NaN
PCORCAVENDAI              CODDESCONTO   NUMBER(8,0)                                                                   Código da política de desconto.            OPERACIONAL                        NaN
PCORCAVENDAI               FATORPRECO  NUMBER(20,8)                                                           Índice que se aplica ao preço de venda.            OPERACIONAL                        NaN
PCORCAVENDAI               PVENDAATAC  NUMBER(12,3)                                                                           Preço de Venda Atacado.            OPERACIONAL                        NaN
PCORCAVENDAI          QTMINIMAATACADO  NUMBER(18,6)                                                                     Quantidade Mínima de Atacado.            OPERACIONAL                        NaN
PCORCAVENDAI            PERCDESCQUANT   NUMBER(6,2)                                                            Percentual de Desconto por Quantidade.            OPERACIONAL                        NaN
PCORCAVENDAI        PERCDESC_POLITICA  NUMBER(10,4)                                                              Percentual por Política de Desconto.            OPERACIONAL                        NaN
PCORCAVENDAI                PRECOFIXO  NUMBER(18,6)                                                                                       Preço Fixo.            OPERACIONAL                        NaN
PCORCAVENDAI                 CODCOMBO   NUMBER(6,0)                                                                      Código da política de combo.            OPERACIONAL                        NaN
PCORCAVENDAI     VLREDPVENDASIMPLESNA  NUMBER(18,6)                                 Valor de redução no preço de venda para cliente Simples Nacional.            OPERACIONAL                        NaN
PCORCAVENDAI       VLREDCMVSIMPLESNAC  NUMBER(18,6)                                            Valor de redução no CMV para cliente Simples Nacional.            OPERACIONAL                        NaN
PCORCAVENDAI            CODOFERTAORIG   NUMBER(6,0)                                                                                  Codigo da oferta            OPERACIONAL                        NaN
PCORCAVENDAI               STPBASERCA  NUMBER(18,6)                                                            Valor de ST relativo ao preço base RCA            OPERACIONAL                        NaN
PCORCAVENDAI                STPTABELA  NUMBER(18,6)                                                           Valor de ST relativo ao preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAI         GRUPOFATURAMENTO   VARCHAR2(1)                                                                                 Grupo Faturamento            OPERACIONAL                        NaN
PCORCAVENDAI                DTENTREGA          DATE                                                                           Data de entrega do item            OPERACIONAL                        NaN
PCORCAVENDAI              RP_IMEDIATA   VARCHAR2(1)                                                                                  Retira posterior            OPERACIONAL                        NaN
PCORCAVENDAI       NUMSEQITEMCONTRATO   NUMBER(6,0)                                                           Número da Sequência do Item no Contrato            OPERACIONAL                        NaN
PCORCAVENDAI                 NUMLISTA   NUMBER(6,0)                                                                       Número da Lista de Presente            OPERACIONAL                        NaN
PCORCAVENDAI         PERDESCNEGOCIADO  NUMBER(18,6)                                                                Percentudal de desconto negociado.            OPERACIONAL                        NaN
PCORCAVENDAI          FORMANEGOCIACAO   VARCHAR2(1)                                                                              Forma de negociação.            OPERACIONAL                        NaN
PCORCAVENDAI            PERDESCAVISTA  NUMBER(18,6)                                                                   Percentual de desconta à vista.            OPERACIONAL                        NaN
PCORCAVENDAI      NEGOCIACAOPOSTERIOR   VARCHAR2(1)                                                                             Negociação Posterior.            OPERACIONAL                        NaN
PCORCAVENDAI    CODEMITENTEITEMPEDIDO   NUMBER(8,0)                                                                         Código emite item pedido.            OPERACIONAL                        NaN
PCORCAVENDAI             CODPRECOFIXO  NUMBER(18,6)                                                                                Código preço fixo.            OPERACIONAL                        NaN
PCORCAVENDAI           VLACRESFRETEKG  NUMBER(12,6)                                                                    Valor de acréscimo Frete (kG).            OPERACIONAL                        NaN
PCORCAVENDAI             STATUSSUCATA   NUMBER(1,0)                                                                                    Status Sucata.            OPERACIONAL                        NaN
PCORCAVENDAI              NUMORCAORIG  NUMBER(10,0)                                                                       Número orçamento de origem.            OPERACIONAL                        NaN
PCORCAVENDAI             NUMFICHAORIG  NUMBER(10,0)                                                                        Número da ficha de origem.            OPERACIONAL                        NaN
PCORCAVENDAI                MATRICULA   NUMBER(8,0)                                                                                        Matrícula.            OPERACIONAL                        NaN
PCORCAVENDAI               DTULTALTER          DATE                                                                            Data última alteração.            OPERACIONAL                        NaN
PCORCAVENDAI                  NUMLOTE  VARCHAR2(15)                                                                                   Número do lote.            OPERACIONAL                        NaN
PCORCAVENDAI               OBSERVACAO VARCHAR2(300)                                                                      Observação de Item da Ficha.            OPERACIONAL                        NaN
PCORCAVENDAI                  BAIXADO   VARCHAR2(1)                                                          Estado do orçamento como baixado ou não.            OPERACIONAL                        NaN
PCORCAVENDAI             PERDESCPAUTA  NUMBER(18,6)                                         Percentual de desconto utilizado para produtos com pauta.            OPERACIONAL                        NaN
PCORCAVENDAI                 ORIGEMST   VARCHAR2(1)                                                                           Origem do cálculo de ST            OPERACIONAL                        NaN
PCORCAVENDAI                  UNIDADE   VARCHAR2(2)                                                                       Unidade da fórmula de tinta            OPERACIONAL                        NaN
PCORCAVENDAI                 AMBIENTE  VARCHAR2(50)                                                                                  Nome do Ambiente            OPERACIONAL                        NaN
PCORCAVENDAI        TAXACASOMOEDAREAL  NUMBER(12,6)                                                          Taxa caso a moeda escolhida seja o real.            OPERACIONAL                        NaN
PCORCAVENDAI       CODMOEDAESTRAGEIRA   NUMBER(6,0)                                             Guarda código da moeda estrageira no momento da venda            OPERACIONAL                        NaN
PCORCAVENDAI       VLRMOEDAESTRAGEIRA  NUMBER(18,6)                                          Guarda valor da conversão do real para moeda extrangeira            OPERACIONAL                        NaN
PCORCAVENDAI        QTDIASENTREGAITEM   NUMBER(4,0)                                                  Qtde de dias para entregar o produto sem estoque            OPERACIONAL                        NaN
PCORCAVENDAI       IMPRIMERESTAURANTE   VARCHAR2(1)                                                           Embalagem permite impressão restaurante            OPERACIONAL                        NaN
PCORCAVENDAI      IMPRESSORESTAURANTE   VARCHAR2(1)                                                                       Status de impressão do item            OPERACIONAL                        NaN
PCORCAVENDAI                   CODIMP  NUMBER(10,0)                                                                              Código da Impressora            OPERACIONAL                        NaN
PCORCAVENDAI          NUMSEQIMPRESSAO   NUMBER(6,0)                                                                            Sequência de impressão            OPERACIONAL                        NaN
PCORCAVENDAI              NUMITEMORCA   NUMBER(6,0)                                                                    Número item orçamento cliente.            OPERACIONAL                        NaN
PCORCAVENDAI      VLACRESCCOMPLEMENTO  NUMBER(18,6)                                                                Valor de acréscimo do complemento.            OPERACIONAL                        NaN
PCORCAVENDAI           PERCREDALIQIPI  NUMBER(18,6)                                                                   % de Redução da Alíquota de IPI            OPERACIONAL                        NaN
PCORCAVENDAI             CODPRODCESTA   NUMBER(6,0)                                                                Código do produto cesta Kit Aberto            OPERACIONAL                        NaN
PCORCAVENDAI   CODINDICEMULTIPLICADOR   NUMBER(6,0)                                                            código indice multiplicador de serviço            OPERACIONAL                        NaN
PCORCAVENDAI                PVENDALIQ  NUMBER(18,6)                                                                                     preço líquido            OPERACIONAL                        NaN
PCORCAVENDAI           VLBASEPARTDEST  NUMBER(18,6)                                                         Valor da base de cálculo na UF de destino            OPERACIONAL                        NaN
PCORCAVENDAI                  ALIQFCP  NUMBER(18,6)                                                       Aliquota de FCP(Fundo de combate à pobreza)            OPERACIONAL                        NaN
PCORCAVENDAI          ALIQINTERNADEST  NUMBER(18,6)                                                        Aliquota de ]ICMS interna na UF de destino            OPERACIONAL                        NaN
PCORCAVENDAI                VLFCPPART  NUMBER(18,6)                                                                                   Valor do FUNCEP            OPERACIONAL                        NaN
PCORCAVENDAI           VLICMSPARTDEST  NUMBER(18,6)                                                     Valor do ICMS interestadual para a UF destino            OPERACIONAL                        NaN
PCORCAVENDAI               VLICMSPART  NUMBER(18,6)         Valor de ICMS de partilha(valor que deverá ser utilizado para acrescer o valor do produto            OPERACIONAL                        NaN
PCORCAVENDAI             PERCPROVPART   NUMBER(5,2)                                                         Percentual provisório de partilha de ICMS            OPERACIONAL                        NaN
PCORCAVENDAI        VLICMSDIFALIQPART  NUMBER(22,6)                                      Valor de ICMS do diferencial de aliquota da partilha de ICMS            OPERACIONAL                        NaN
PCORCAVENDAI          PERCBASEREDPART   NUMBER(5,2)                                                 Redução aplicada na base de Partilha no orçamento            OPERACIONAL                        NaN
PCORCAVENDAI            VLICMSPARTREM  NUMBER(18,6)                                                       Valor do ICMS de partilha para UF remetente            OPERACIONAL                        NaN
PCORCAVENDAI        ALIQINTERORIGPART  NUMBER(18,6)                                                                 Aliquota de  ICMS da UF de origem            OPERACIONAL                        NaN
PCORCAVENDAI             VLIPIPTABELA  NUMBER(18,6)                                                          Valor de IPI relativo ao preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAI            VLIPIPBASERCA  NUMBER(18,6)                                                           Valor de IPI relativo ao preço base RCA            OPERACIONAL                        NaN
PCORCAVENDAI        VLICMSPARTPTABELA  NUMBER(18,6)                                                   Valor ICMS Partilha relativo ao preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAI       VLICMSPARTPBASERCA  NUMBER(18,6)                                                    Valor ICMS Partilha relativo ao preço base RCA            OPERACIONAL                        NaN
PCORCAVENDAI               NUMITEMPED  NUMBER(10,0)                                                                       Número do Item no XML da NF            OPERACIONAL                        NaN
PCORCAVENDAI                  BONIFIC   VARCHAR2(1)                                                                  Identificação do item bonificado            OPERACIONAL                        NaN
PCORCAVENDAI                     OBS1 VARCHAR2(400)                                                                                      Observação 1            OPERACIONAL                        NaN
PCORCAVENDAI                     OBS2 VARCHAR2(400)                                                                                      Observação 2            OPERACIONAL                        NaN
PCORCAVENDAI                 PBONIFIC  NUMBER(18,6)                                                                          Valor do item bonificado            OPERACIONAL                        NaN
PCORCAVENDAI               ROTINALANC  VARCHAR2(48)                                                                Última rotina que alterou a tabela            OPERACIONAL                        NaN
PCORCAVENDAI    CODMOTIVONAOATENDPROD   NUMBER(3,0)                                          CÓDIGO DO MOTIVO DO NÃO ATENDIMENTO DO ITEM DO ORÇAMENTO            OPERACIONAL                        NaN
PCORCAVENDAI              PERCDESCPIS  NUMBER(12,4)                                                                                 Indica o % de pis            OPERACIONAL                        NaN
PCORCAVENDAI         VLDESCREDUCAOPIS  NUMBER(24,6)                                               indica o valor de desconto de PIS aplicado na venda            OPERACIONAL                        NaN
PCORCAVENDAI           PERCDESCCOFINS  NUMBER(12,4)                                                                              Indica o % de COFINS            OPERACIONAL                        NaN
PCORCAVENDAI      VLDESCREDUCAOCOFINS  NUMBER(24,6)                                            Indica o valor de desconto de COFINS aplicado na venda            OPERACIONAL                        NaN
PCORCAVENDAI    CODFIGVENDATRIANGULAR   NUMBER(4,0)                                        Define o código da figura tributaria para venda triangular            OPERACIONAL                        NaN
PCORCAVENDAI                CODFISCAL   NUMBER(8,0)                                                                Define o CFOP do item no orçamento            OPERACIONAL                        NaN
PCORCAVENDAI                SITTRIBUT   VARCHAR2(3)                                                                 Define o CST do item no orçamento            OPERACIONAL                        NaN
PCORCAVENDAI    VERSAOSERVICOPARTILHA  VARCHAR2(10)                                                                Versão do servido de ICMS Partilha            OPERACIONAL                        NaN
PCORCAVENDAI             VLTOTSERVICO  NUMBER(22,6)                                                    VALOR TOTAL DO SERVIÇO DO PRODUTO NO ORÇAMENTO            OPERACIONAL                        NaN
PCORCAVENDAI           PRODUZIR_TINTA   VARCHAR2(1)                                                                         Produzir Tinta Manipulada            OPERACIONAL                        NaN
PCORCAVENDAI                 PROMOCAO   VARCHAR2(1)                                                                                          Promoção            OPERACIONAL                        NaN
PCORCAVENDAI DESCONSIDERARDESCATACADO   VARCHAR2(1)                                                         Desconsiderar item no calculo de atacado.            OPERACIONAL                        NaN
PCORCAVENDAI     CODDESCONTOSIMULADOR   NUMBER(8,0)                                                  Indica o código do desconto de simulador no item            OPERACIONAL                        NaN
PCORCAVENDAI            DTENTREGAMESA          DATE                                                                           Data de entrega da mesa            OPERACIONAL                        NaN
PCORCAVENDAI       CODFUNCENTREGAMESA   NUMBER(8,0)                                                                    funcionário de entrega da mesa            OPERACIONAL                        NaN
PCORCAVENDAI        PRODIMPORTADOPEPS   VARCHAR2(1)                                                                            Produto Importado PEPS            OPERACIONAL                        NaN
PCORCAVENDAI          NUMTRANSENTPEPS  NUMBER(10,0)                                                                         Transação de Entrada PEPS            OPERACIONAL                        NaN
PCORCAVENDAI        PTABELAFABRICAZFM  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI                  SERVIMP  NUMBER(10,0)                                                                   Código do Servidor de impressão            OPERACIONAL                        NaN
PCORCAVENDAI             ORIGMERCTRIB   VARCHAR2(1)                                Código de origem da mercadoria para geração da situação tributária            OPERACIONAL                        NaN
PCORCAVENDAI            CODIMPSERVIMP  NUMBER(10,0)                                                                   Código do Servidor de impressão            OPERACIONAL                        NaN
PCORCAVENDAI         DTENVIOSERVCARGA          DATE                                                            Data de envio para o servidor de carga            OPERACIONAL                        NaN
PCORCAVENDAI             DESCRICAOPAF VARCHAR2(200)                                                                      Descrição de impressão Cupom            OPERACIONAL                        NaN
PCORCAVENDAI                   MD5PAF VARCHAR2(200)                                                                 Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN
PCORCAVENDAI            VLBASEFCPICMS  NUMBER(18,6)                                            Valor da base de calculo do Fundo de Combate a Pobreza            OPERACIONAL                        NaN
PCORCAVENDAI              VLBASEFCPST  NUMBER(18,6)                                         Valor de base de calculo do Fundo de Combate a Pobreza ST            OPERACIONAL                        NaN
PCORCAVENDAI             VLBCFCPSTRET  NUMBER(18,6)                                       Valor da base de calculo do FCP retido anteriormente por ST            OPERACIONAL                        NaN
PCORCAVENDAI              PERFCPSTRET  NUMBER(12,4)                                Percentual do FCP retido anteriormente por Substituição Tributaria            OPERACIONAL                        NaN
PCORCAVENDAI               VLFCPSTRET  NUMBER(18,6)                                                   Valor do FCP retido por Substituição Tributária            OPERACIONAL                        NaN
PCORCAVENDAI                 PERFCPSN  NUMBER(12,4)                                        Aliquota aplicável de cálculo do crédito(SIMPLES NACIONAL)            OPERACIONAL                        NaN
PCORCAVENDAI          VLCREDFCPICMSSN  NUMBER(18,6) Valor crédito do ICMS que pode ser aproveitado nos termos do art. 23 da LC 123 (SIMPLES NACIONAL)            OPERACIONAL                        NaN
PCORCAVENDAI                   VLFECP  NUMBER(18,6)                                                                                       Valor Fecp.            OPERACIONAL                        NaN
PCORCAVENDAI        VLACRESCIMOFUNCEP  NUMBER(18,6)                                                                            Valor Acrescimo FUNCEP            OPERACIONAL                        NaN
PCORCAVENDAI       PERACRESCIMOFUNCEP  NUMBER(12,4)                                                                       Percentual Acrescimo FUNCEP            OPERACIONAL                        NaN
PCORCAVENDAI             ALIQICMSFECP  NUMBER(12,4)                                                                            Alíquota de ICMS Fecp.            OPERACIONAL                        NaN
PCORCAVENDAI     UTILIZOUMOTORCALCULO   VARCHAR2(1)                                Indica se utilizou motor de calculo para calcular o preço de venda            OPERACIONAL                        NaN
PCORCAVENDAI                   CODECF   VARCHAR2(6)                                                                                  Aliquotas da ECF            OPERACIONAL                        NaN
PCORCAVENDAI        BAIXAQTFRENTELOJA   VARCHAR2(1)                                                Identifica baixa de estoque na loja ou no deposito            OPERACIONAL                        NaN
PCORCAVENDAI         NUMVERBACAMPANHA   NUMBER(8,0)                                                                Nr. da verba atribuída a campanha.            OPERACIONAL                        NaN
PCORCAVENDAI           PERCCUSTFORNEC  NUMBER(12,4)                                                              Percentual custeado pelo fornecedor.            OPERACIONAL                        NaN
PCORCAVENDAI             VLCUSTFORNEC  NUMBER(18,6)                                                          Valor unitário custeado pelo fornecedor.            OPERACIONAL                        NaN
PCORCAVENDAI             VLOUTRASDESP  NUMBER(18,6)                                                                                Acréscimos no item            OPERACIONAL                        NaN
PCORCAVENDAI           VLACRESCRODAPE  NUMBER(18,6)                                                                              Acréscimos no rodapé            OPERACIONAL                        NaN
PCORCAVENDAI      CODIGOINTEGRACAOWMS  VARCHAR2(15)                                                             Lote da Promoção para indução do lote            OPERACIONAL                        NaN
PCORCAVENDAI       NUMLOTEPROMOCAOMED  VARCHAR2(20)                                                                       Código da integração do WMS            OPERACIONAL                        NaN
PCORCAVENDAI              CODDEPOSITO  NUMBER(10,0)                                    Código do depósito informado para o orçamento durante a venda.            OPERACIONAL                        NaN
PCORCAVENDAI           CODPROMOCAOMED   NUMBER(9,0)                                                                Código da Promoção de Medicamentos            OPERACIONAL                        NaN
PCORCAVENDAI                NUMPEDCLI  VARCHAR2(15)                                                                       Número do pedido do cliente            OPERACIONAL                        NaN
PCORCAVENDAI              CODCONTRATO   NUMBER(6,0)                                                                      Código do contrato utilizado            OPERACIONAL                        NaN
PCORCAVENDAI     VLDESCCMVPROMOCAOMED  NUMBER(18,6)                                                                        Vl. Verba Fornec. Promocao            OPERACIONAL                        NaN
PCORCAVENDAI          BCSTRETANTERIOR  NUMBER(18,6)                                                     Base de calculo do ST recolhido anteriormente            OPERACIONAL                        NaN
PCORCAVENDAI VLICMSSUBSTITUTOANTERIOR  NUMBER(18,6)                                                  Valor do ICMS substituto recolhido anteriormente            OPERACIONAL                        NaN
PCORCAVENDAI      VLICMSSTRETANTERIOR  NUMBER(18,6)                                                               Valor do ST recolhido anteriormente            OPERACIONAL                        NaN
PCORCAVENDAI          PMPFMEDICAMENTO  NUMBER(18,6)                                                                                  PMPF Medicamento            OPERACIONAL                        NaN
PCORCAVENDAI               QBCMONORET  NUMBER(18,6)                                                                                     Base mono ret            OPERACIONAL                        NaN
PCORCAVENDAI             ADREMICMSRET  NUMBER(18,6)                                                                                      Rem ICMS RET            OPERACIONAL                        NaN
PCORCAVENDAI             VICMSMONORET  NUMBER(18,6)                                                                               Valor ICMS Mono ret            OPERACIONAL                        NaN
PCORCAVENDAI            VLIPISUSPENSO  NUMBER(18,6)                                                                             Valor de IPI Suspenso            OPERACIONAL                        NaN
PCORCAVENDAI             VLIISUSPENSO  NUMBER(18,6)                                                                              Valor de II Suspenso            OPERACIONAL                        NaN
PCORCAVENDAI           QTCOMBOVIRTUAL  NUMBER(12,4)                                             Quantidade de Combo Utilizado da Campanha de Desconto            OPERACIONAL                        NaN
PCORCAVENDAI       PERDESCMAXCAMPANHA  NUMBER(18,6)                                                           Percentual máximo da política utilizada            OPERACIONAL                        NaN
PCORCAVENDAI          PERDESCCAMPANHA  NUMBER(18,6)                                                                 Percentual informado pelo usuário            OPERACIONAL                        NaN
PCORCAVENDAI            PBASECAMPANHA  NUMBER(18,6)                                        Preço de venda aplicado caso não houvesse nenhuma política            OPERACIONAL                        NaN
PCORCAVENDAI        PRECOFIXOCAMPANHA  NUMBER(18,6)                        Preço de venda partindo da política da 357, sem outra política de desconto            OPERACIONAL                        NaN
PCORCAVENDAI                  ALIQCBS NUMBER(23,10)                                                              Aliquota para calculo do valor CBS\t            OPERACIONAL                        NaN
PCORCAVENDAI                  ALIQIBS NUMBER(23,10)                                                                Aliquota para calculo do valor IBS            OPERACIONAL                        NaN
PCORCAVENDAI                   ALIQIS NUMBER(23,10)                                                                 Aliquota para calculo do valor IS            OPERACIONAL                        NaN
PCORCAVENDAI                  BASECBS NUMBER(23,10)                                                              Valor base para calculo do valor CBS            OPERACIONAL                        NaN
PCORCAVENDAI                  BASEIBS NUMBER(23,10)                                                              Valor base para calculo do valor IBS            OPERACIONAL                        NaN
PCORCAVENDAI                   BASEIS NUMBER(23,10)                                                               Valor base para calculo do valor IS            OPERACIONAL                        NaN
PCORCAVENDAI                    VLCBS NUMBER(23,10)                                                                              Valor do imposto CBS            OPERACIONAL                        NaN
PCORCAVENDAI                    VLIBS NUMBER(23,10)                                                                              Valor do imposto IBS            OPERACIONAL                        NaN
PCORCAVENDAI                     VLIS NUMBER(23,10)                                                                               Valor do imposto IS            OPERACIONAL                        NaN
PCORCAVENDAI                   CODCBS  NUMBER(10,0)                                        Código da tributação do imposto CBS na tabela PCTRIBUTACAO            OPERACIONAL                        NaN
PCORCAVENDAI                   CODIBS  NUMBER(10,0)                                        Código da tributação do imposto IBS na tabela PCTRIBUTACAO            OPERACIONAL                        NaN
PCORCAVENDAI                    CODIS  NUMBER(10,0)                                         Código da tributação do imposto IS na tabela PCTRIBUTACAO            OPERACIONAL                        NaN
PCORCAVENDAI             VLCBSPTABELA NUMBER(23,10)                                                  Valor do imposto CBS aplicado no preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAI             VLIBSPTABELA NUMBER(23,10)                                                  Valor do imposto IBS aplicado no preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAI              VLISPTABELA NUMBER(23,10)                                                   Valor do imposto IS aplicado no preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAI            VLCBSPBASERCA NUMBER(23,10)                                                Valor do imposto CBS aplicado no preço base do RCA            OPERACIONAL                        NaN
PCORCAVENDAI            VLIBSPBASERCA NUMBER(23,10)                                                Valor do imposto IBS aplicado no preço base do RCA            OPERACIONAL                        NaN
PCORCAVENDAI             VLISPBASERCA NUMBER(23,10)                                                 Valor do imposto IS aplicado no preço base do RCA            OPERACIONAL                        NaN
PCORCAVENDAI                   NUMCCF   NUMBER(8,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAI   CPFRESPTECNICOAGRIGOLA  VARCHAR2(11)                                                                  CPF Responsável Técnico Agrícola            OPERACIONAL                        NaN
PCORCAVENDAI   NUMRECEITUARIOAGRICOLA  VARCHAR2(30)                                                                       Número Receituário Agrícola            OPERACIONAL                        NaN
PCORCAVENDAI   CPFRESPTECNICOAGRICOLA  VARCHAR2(11)                                                                  CPF Responsável Técnico Agrícola            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*