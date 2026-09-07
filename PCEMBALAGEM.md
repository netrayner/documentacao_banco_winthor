# 📊 Tabela: PCEMBALAGEM

### Estrutura de Colunas e Restrições

     Tabela                        Coluna  Tipo/Tamanho                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMBALAGEM                   CODAUXILIAR  NUMBER(20,0)                                                                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBALAGEM                       CODPROD   NUMBER(6,0)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                     EMBALAGEM  VARCHAR2(12)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                       UNIDADE   VARCHAR2(2)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                        QTUNIT  NUMBER(18,6)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                       PTABELA  NUMBER(12,3)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                        PVENDA  NUMBER(12,3)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM               DTULTALTPTABELA          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                DTULTALTPVENDA          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM             CODFUNCALTPTABELA   NUMBER(8,0)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM              CODFUNCALTPVENDA   NUMBER(8,0)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                    QTMAXVENDA  NUMBER(18,6)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                    MARGEM_ESP   NUMBER(6,2)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                        MARGEM   NUMBER(6,2)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                   DTULTALTCOM          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                  EXPORTACAMPO   VARCHAR2(1)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                      PRAZOVAL   NUMBER(4,0)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                     CODFILIAL   VARCHAR2(2)                                                                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBALAGEM                       POFERTA  NUMBER(12,2)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                   DTOFERTAINI          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                   DTOFERTAFIM          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                 PRECOANTERIOR  NUMBER(12,3)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                      EXCLUIDO   VARCHAR2(1)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM          PERMITEMULTIPLICACAO   VARCHAR2(1)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM              USABALANCATOLEDO   VARCHAR2(1)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                 TIPOEMBALAGEM   VARCHAR2(1)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                 DTEMISSAOETIQ          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                  QTMINGONDOLA   NUMBER(6,0)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                  QTMAXGONDOLA   NUMBER(6,0)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                     NUMSEQATU        NUMBER                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                    FATORPRECO  NUMBER(20,8)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                 QTMINATACADOF   NUMBER(6,0)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                   PTABELAATAC  NUMBER(12,3)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                    PVENDAATAC  NUMBER(12,3)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM             PRECOANTERIORATAC  NUMBER(12,3)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM               QTMINIMAATACADO  NUMBER(18,6)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM              QTMINIMAATACADOF  NUMBER(18,6)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                       ENVIAFV   VARCHAR2(1)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                MARGEMATAC_ESP   NUMBER(6,2)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM           DTULTALTPTABELAATAC          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM            DTULTALTPVENDAATAC          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                    MARGEMATAC   NUMBER(6,2)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                           OBS   VARCHAR2(2)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM               MARGEMIDEALATAC   NUMBER(6,2)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM               DTOFERTAATACINI          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM               DTOFERTAATACFIM          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                   POFERTAATAC  NUMBER(18,6)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                     PESOBRUTO  NUMBER(20,8)                                                         Indica o Peso Bruto da embalagem.             OPERACIONAL                        NaN
PCEMBALAGEM                       PESOLIQ  NUMBER(20,8)                                                       Indica o Peso Líquido da embalagem.             OPERACIONAL                        NaN
PCEMBALAGEM                  ENVIABALANCA   VARCHAR2(1)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                    QTMULTIPLA   NUMBER(6,0)                                                   Indica a quantidade múltipla embalagem.             OPERACIONAL                        NaN
PCEMBALAGEM           PERMITEVENDAATACADO   VARCHAR2(1)                                   Indica restrição de venda por embalagem para o Atacado.             OPERACIONAL                        NaN
PCEMBALAGEM                  DESCRICAOECF  VARCHAR2(40)                                                                Indica a descrição do ECF.             OPERACIONAL                        NaN
PCEMBALAGEM          ACEITAPRECOREPLICADO   VARCHAR2(1)                                    Indica se a embalagem deve ou não replicação de preço.             OPERACIONAL                        NaN
PCEMBALAGEM                LAYOUTETIQUETA  VARCHAR2(40)                                                       Definição de layout para embalagem.             OPERACIONAL                        NaN
PCEMBALAGEM            PERVARIACAOPTABELA  NUMBER(20,8)                                                  Indica o percentual de variação de preço.            OPERACIONAL                        NaN
PCEMBALAGEM         DTEMISSAOETIQPOFERTAS          DATE                                            Indica a data de emissão da etiqueta de oferta.            OPERACIONAL                        NaN
PCEMBALAGEM              DTULTALTERSRVPRC          DATE                                            Indica a data da ultima alteração nesta tabela.            OPERACIONAL                        NaN
PCEMBALAGEM                FATORCONVERSAO  NUMBER(20,8)                                Indica o fator de conversão para o da unidade da embalagem.            OPERACIONAL                        NaN
PCEMBALAGEM                      UNMEDIDA   VARCHAR2(4)                                     Indica a unidade de medida utilizada para a embalagem.            OPERACIONAL                        NaN
PCEMBALAGEM         CODFUNCALTPTABELAATAC   NUMBER(8,0)                                  Código Funcionário que alterou o preço de tabela atacado.            OPERACIONAL                        NaN
PCEMBALAGEM          CODFUNCALTPVENDAATAC   NUMBER(8,0)                                   Código Funcionário que alterou o preço de venda atacado.            OPERACIONAL                        NaN
PCEMBALAGEM             CODFUNCALTPOFERTA   NUMBER(8,0)                                          Código Funcionário que alterou o preço de oferta.            OPERACIONAL                        NaN
PCEMBALAGEM         CODFUNCALTPOFERTAATAC   NUMBER(8,0)                                  Código Funcionário que alterou o preço de oferta atacado.            OPERACIONAL                        NaN
PCEMBALAGEM       PERDESCCARTAOFIDELIDADE   NUMBER(5,2)                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                    ASSINATURA VARCHAR2(255)                                                                               Código MD-5             OPERACIONAL                        NaN
PCEMBALAGEM             CONTROLEVASILHAME   VARCHAR2(1)                                                                         Controle Vasilhame            OPERACIONAL                        NaN
PCEMBALAGEM                CODFUNCINATIVO   NUMBER(8,0)                                                          Funcionário desativação embalagem            OPERACIONAL                        NaN
PCEMBALAGEM                     DTINATIVO          DATE                                                                 Data desativação embalagem            OPERACIONAL                        NaN
PCEMBALAGEM                  MOTIVOOFERTA  VARCHAR2(60)                                                                           Motivo da oferta            OPERACIONAL                        NaN
PCEMBALAGEM                      DTULTALT          DATE                                               Data  e hora de última alteração no registro            OPERACIONAL                        NaN
PCEMBALAGEM                USARESTAURANTE   VARCHAR2(1)                                                               Usa embalagem em restaurante            OPERACIONAL                        NaN
PCEMBALAGEM       IMPDATAEMBALAGEMBALANCA   VARCHAR2(1)                                                    Exporta data da embalagem para balanças            OPERACIONAL                        NaN
PCEMBALAGEM                 ENVIAINFNUTRI   VARCHAR2(1)                             Exportar as informações nutricionais da embalagem para balança            OPERACIONAL                        NaN
PCEMBALAGEM                    PTABELAWEB   NUMBER(8,2)                           Preço futuro que será aplicado ao produto disponibilizado na web            OPERACIONAL                        NaN
PCEMBALAGEM                     PVENDAWEB   NUMBER(8,2)                         Preço de venda que será aplicado ao produto disponibilizado na web            OPERACIONAL                        NaN
PCEMBALAGEM                    POFERTAWEB   NUMBER(8,2)                        Preço de oferta que será aplicado ao produto disponibilizado na web            OPERACIONAL                        NaN
PCEMBALAGEM                DTOFERTAWEBINI          DATE Data do inicio do período de vigência do preço de oferta do produto disponibilizado na web            OPERACIONAL                        NaN
PCEMBALAGEM                DTOFERTAWEBFIM          DATE             Data do fim do período de vigência da oferta do produto disponibilizado na web            OPERACIONAL                        NaN
PCEMBALAGEM                   SITUACAOWEB   VARCHAR2(1)                                                                        Situação do Produto            OPERACIONAL                        NaN
PCEMBALAGEM                  DESCRICAOWEB VARCHAR2(100)                                                                Descrição do Produto na WEB            OPERACIONAL                        NaN
PCEMBALAGEM                        QTDIAS   NUMBER(3,0)                                                            Qt. Dias para estoque segurança            OPERACIONAL                        NaN
PCEMBALAGEM       QTFIXAMULTIPLICCHECKOUT   NUMBER(9,3)                                             Quantidade fixa para multiplicação no checkout            OPERACIONAL                        NaN
PCEMBALAGEM            DTULTALTPTABELAWEB          DATE                                       Data da última alteração do preço de tabela para web            OPERACIONAL                        NaN
PCEMBALAGEM                        CODCOB   VARCHAR2(4)                                                                         Código da cobrança            OPERACIONAL                        NaN
PCEMBALAGEM                        CODCLI   NUMBER(6,0)                                                                          Código do cliente            OPERACIONAL                        NaN
PCEMBALAGEM                 QTEMISSAOETIQ   NUMBER(8,0)                                           Quantidade de etiquetas a emitir desta embalagem            OPERACIONAL                        NaN
PCEMBALAGEM                CODINFEXTRABAL   NUMBER(6,0)   Informação extra usada para vincular uma receita ao exportar a embalagem para a balança.            OPERACIONAL                        NaN
PCEMBALAGEM                         TARAF   NUMBER(7,3)                                                                            Tara da balança            OPERACIONAL                        NaN
PCEMBALAGEM        PERMITEVENDACOMINTERNO   VARCHAR2(1)                                                    Permite venda com código interno - PDV.            OPERACIONAL                        NaN
PCEMBALAGEM       INDICPESAGEMOBRIGATORIA   VARCHAR2(1)                                                    Indica se a pesagem e obrigatória - PDV            OPERACIONAL                        NaN
PCEMBALAGEM       INDICPERMITEPORPREVENDA   VARCHAR2(1)                           Indica se o produto só pode ser vendido dentro de uma pré venda.            OPERACIONAL                        NaN
PCEMBALAGEM    INDICPERMITEDIGITACAOPRECO   VARCHAR2(1)                                                                Permite digitação de preço.            OPERACIONAL                        NaN
PCEMBALAGEM INDICPERMITEDIGITACAODESCONTO   VARCHAR2(1)                                                             Permite digitação de desconto.            OPERACIONAL                        NaN
PCEMBALAGEM          INDICGERARCODPESOVAR   VARCHAR2(1)                                                        Permite gerar código peso variável.            OPERACIONAL                        NaN
PCEMBALAGEM         INDICALERTAQUANTIDADE   VARCHAR2(1)                  Indica se o sistema deve apresentar o alerta de quantidade para operador.            OPERACIONAL                        NaN
PCEMBALAGEM          INDICPRODUCAOPROPRIA   VARCHAR2(1)                                                                 Indica a produção própria.            OPERACIONAL                        NaN
PCEMBALAGEM                 CODDIGITAQTDE   VARCHAR2(1)                                                           Permite digitação da quantidade.            OPERACIONAL                        NaN
PCEMBALAGEM                    PTABELAANT  NUMBER(12,3)                                                                      Preço futuro anterior            OPERACIONAL                        NaN
PCEMBALAGEM                PTABELAATACANT  NUMBER(12,3)                                                              Preço futuro atacado anterior            OPERACIONAL                        NaN
PCEMBALAGEM                  PVENDAWEBANT  NUMBER(18,6)                                                     Preço venda web anterior da embalagem.            OPERACIONAL                        NaN
PCEMBALAGEM                 PTABELAWEBANT  NUMBER(18,6)                                                                 Preço futuro web anterior.            OPERACIONAL                        NaN
PCEMBALAGEM                      PCOMINT1   NUMBER(6,2)                                                    Taxa de comissão para vendedor interno.            OPERACIONAL                        NaN
PCEMBALAGEM                      PCOMEXT1   NUMBER(6,2)                                                    Taxa de comissão para vendedor externo.            OPERACIONAL                        NaN
PCEMBALAGEM                      PCOMREP1   NUMBER(6,2)                                                       Taxa de comissão para representante.            OPERACIONAL                        NaN
PCEMBALAGEM                  BEBALCOOLICA   VARCHAR2(1)                                            Definição de Item como bebida alcoolica ou não.            OPERACIONAL                        NaN
PCEMBALAGEM            DTAPLICPRECOVAREJO          DATE                                                Data de agendamento de preço futuro varejo.            OPERACIONAL                        NaN
PCEMBALAGEM              DTAPLICPRECOATAC          DATE                                               Data de agendamento de preço futuro atacado.            OPERACIONAL                        NaN
PCEMBALAGEM           INDCVENDECODINTERNO   VARCHAR2(1)                                                         Permite vender com código interno.            OPERACIONAL                        NaN
PCEMBALAGEM                 SOCIOTORCEDOR   VARCHAR2(1)                                                                   Embalagem sócio torcedor            OPERACIONAL                        NaN
PCEMBALAGEM           DESTINOOFERTAVAREJO   VARCHAR2(2)                                 Define para onde será aplicado o preço de oferta de varejo            OPERACIONAL                        NaN
PCEMBALAGEM             DESTINOOFERTAATAC   VARCHAR2(2)                                Define para onde será aplicado o preço de oferta de atacado            OPERACIONAL                        NaN
PCEMBALAGEM                       GIROMES  NUMBER(16,3)                                                                      Giro mês da embalagem            OPERACIONAL                        NaN
PCEMBALAGEM                  GIROMEDIODIA  NUMBER(16,3)                                                                Giro médio dia da embalagem            OPERACIONAL                        NaN
PCEMBALAGEM                  DTULTALTGIRO          DATE                                                           Data da última alteração de giro            OPERACIONAL                        NaN
PCEMBALAGEM            ENVIATELEMARKETING   VARCHAR2(1)                                                                        Envia telemarketing            OPERACIONAL                        NaN
PCEMBALAGEM              ENVIAFRENTECAIXA   VARCHAR2(1)                                                                      Envia frente de caixa            OPERACIONAL                        NaN
PCEMBALAGEM            IMPRIMERESTAURANTE   VARCHAR2(1)                                                                        Imprime restaurante            OPERACIONAL                        NaN
PCEMBALAGEM                        ALTURA  NUMBER(20,8)                                                                        Altura da embalagem            OPERACIONAL                        NaN
PCEMBALAGEM                       LARGURA  NUMBER(20,8)                                                                       Largura da embalagem            OPERACIONAL                        NaN
PCEMBALAGEM                   COMPRIMENTO  NUMBER(20,8)                                                                   Comprimento da embalagem            OPERACIONAL                        NaN
PCEMBALAGEM                        VOLUME  NUMBER(20,8)                                                                        Volume da embalagem            OPERACIONAL                        NaN
PCEMBALAGEM         OBRIGALEITURACODBARRA   VARCHAR2(1)                                            Obriga leitura de código de barras da embalagem            OPERACIONAL                        NaN
PCEMBALAGEM          IMPRESSAORESTAURANTE   VARCHAR2(1)                                                             Permite impressão restaurante.            OPERACIONAL                        NaN
PCEMBALAGEM                PRODUTOCOZINHA   VARCHAR2(1)                                                          Informa se é producao de cozinha.            OPERACIONAL                        NaN
PCEMBALAGEM                  TEMPOPREPARO   NUMBER(5,0)                                            Tempo de Preparo no caso de produto de cozinha.            OPERACIONAL                        NaN
PCEMBALAGEM                   TEMPOALERTA   NUMBER(5,0)                              Tempo de alerta para o preparo no caso de produto de cozinha.            OPERACIONAL                        NaN
PCEMBALAGEM      PERMITEIMPRESSAOETIQUETA   VARCHAR2(1)                               Flag para indicar se embalagem permite impressão de Etiqueta            OPERACIONAL                        NaN
PCEMBALAGEM          USAECOMMERCEUNILEVER   VARCHAR2(1)                    Valida se a embalagem será enviada ou não para o e-commerce da Unilever            OPERACIONAL                        NaN
PCEMBALAGEM                        MD5PAF VARCHAR2(200)                                                          Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN
PCEMBALAGEM          USAETIQUETAANTIFURTO   VARCHAR2(1)                                               INDICA SE PRODUTO POSSUI ETIQUETA ANTI-FURTO            OPERACIONAL                        NaN
PCEMBALAGEM         ACEITAMARGEMREPLICADA       CHAR(1)                                               Define se aceita ou não replicação de margem            OPERACIONAL                        NaN
PCEMBALAGEM                 ENVIAPENTREGA       CHAR(1)                                  Valor para definir se o produto é ou não a pronta entrega            OPERACIONAL                        NaN
PCEMBALAGEM                   INFOPRODWEB          CLOB                                                                 Informações do Produto WEB            OPERACIONAL                        NaN
PCEMBALAGEM                     IDCIASHOP  NUMBER(10,0)                                               Indentificador do embalagem vindo do ciashop            OPERACIONAL                        NaN
PCEMBALAGEM              PRODSEMCODBARRAS       CHAR(1)       Define se o produto tem ou não código de barras para listagem de embalagens no Caixa            OPERACIONAL                        NaN
PCEMBALAGEM    PERMITEVENDACRTALIMENTACAO   VARCHAR2(1)                    Define se permite ou não vender o produto utilizando cartão alimentação            OPERACIONAL                        NaN
PCEMBALAGEM       QTDVIASIMPRESSAOCOZINHA   NUMBER(8,0)     Quantidade de vias de impressão para embalagens que utilizam a opção "Produto Cozinha"            OPERACIONAL                        NaN
PCEMBALAGEM            JUSTIFICATIVAPRECO  VARCHAR2(50)                                                        JUSTIFICATIVA DE ALTERACAO DE PRECO            OPERACIONAL                        NaN
PCEMBALAGEM                CODFRACIONADOR   VARCHAR2(4)                                                                      Código do Fracionador            OPERACIONAL                        NaN
PCEMBALAGEM           CODAUXILIARANTERIOR  NUMBER(20,0)                                          Código auxiliar que possuía antes de ser editado.            OPERACIONAL                        NaN
PCEMBALAGEM                    DTMXSALTER          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCEMBALAGEM                ENVIAECOMMERCE   VARCHAR2(1)                                                                E enviado para o e commerce            OPERACIONAL                        NaN
PCEMBALAGEM                ATIVOECOMMERCE   VARCHAR2(1)                                                               Está ativo para o e-commerce            OPERACIONAL                        NaN
PCEMBALAGEM           CODFILIALINTEGRACAO   NUMBER(3,0)                                                             Código da filial de integração            OPERACIONAL                        NaN
PCEMBALAGEM                     DTALTERC5  TIMESTAMP(6)                                                                          Data de alteração            OPERACIONAL                        NaN
PCEMBALAGEM                    DTCADASTRO  TIMESTAMP(6)                                                                           Data de cadastro            OPERACIONAL                        NaN
PCEMBALAGEM              DTULALTERINTEGRA  TIMESTAMP(6)                                                                             Data alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*