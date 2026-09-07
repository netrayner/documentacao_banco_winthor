# 📊 Tabela: PCMOVCIAPPREENT

### Estrutura de Colunas e Restrições

         Tabela                  Coluna   Tipo/Tamanho                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVCIAPPREENT             NUMTRANSENT   NUMBER(10,0)                                                                      Numero de transação.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 CODPROD    NUMBER(6,0)                                                                        Código do produto.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               CODFISCAL    NUMBER(6,0)                                                                             CFOP do item.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  VLITEM   NUMBER(18,2)                                                                            Valor do item.            OPERACIONAL                        NaN
PCMOVCIAPPREENT             ALIQICMSINT    NUMBER(5,2)                                                                         Aliquota Interna.            OPERACIONAL                        NaN
PCMOVCIAPPREENT             ALIQICMSEXT    NUMBER(5,2)                                                                         Aliquota externa.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               VLCREDITO   NUMBER(10,2)                                                                         Valor de Crédito.            OPERACIONAL                        NaN
PCMOVCIAPPREENT           VLDIFALIQUOTA   NUMBER(10,2)                                                                 Valor do Dif. De aliquota            OPERACIONAL                        NaN
PCMOVCIAPPREENT               ALIQICMS1   NUMBER(12,4)                                                                 Alíquota de ICMS Interna.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               ALIQICMS2   NUMBER(12,4)                                                                 Alíquota de ICMS Externa.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                BASEICMS   NUMBER(18,6)                                                                             Base do ICMS.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                BASEICST   NUMBER(18,6)                                                 Valor Base de Substituição de Tributação.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  CODCLI    NUMBER(8,0)                                                                        Código do Cliente.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               CODFILIAL    VARCHAR2(2)                                                                         Código da Filial.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               CODFORNEC    NUMBER(6,0)                                                                        Código fornecedor.            OPERACIONAL                        NaN
PCMOVCIAPPREENT             CODFUNCLANC    NUMBER(8,0)                                                                       Código Funcionário.            OPERACIONAL                        NaN
PCMOVCIAPPREENT CODMOTIVOICMSDESONERADO    VARCHAR2(2)                                                      Código do Motivo Desoneração do ICMS            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 CODOPER    VARCHAR2(2)                                                                        Códio da operação.            OPERACIONAL                        NaN
PCMOVCIAPPREENT           CODPRODIMOPRI    NUMBER(6,0)                                           Código de produto do bem imobilizado principal.            OPERACIONAL                        NaN
PCMOVCIAPPREENT           CODSITTRIBIPI    NUMBER(3,0)                                                                Situação Tributária do IPI            OPERACIONAL                        NaN
PCMOVCIAPPREENT     CODSITTRIBPISCOFINS    NUMBER(3,0)                                                               Cód. Sit. Trib. Pis/Cofins.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               CUSTOCONT   NUMBER(18,6)                                                                           Custo Contábil.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                CUSTOFIN   NUMBER(18,6)                                                                         Custo Financeiro.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               CUSTOREAL   NUMBER(18,6)                                                                               Custo Real.            OPERACIONAL                        NaN
PCMOVCIAPPREENT          CUSTOREALSEMST   NUMBER(18,6)                                                                        Custo Real sem ST.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                CUSTOREP   NUMBER(18,6)                                                                       Custo de Reposição.            OPERACIONAL                        NaN
PCMOVCIAPPREENT             CUSTOREPANT   NUMBER(18,6)                                                                 Custo Reposição Anterior.            OPERACIONAL                        NaN
PCMOVCIAPPREENT        DESCCOMPLEMENTAR VARCHAR2(1500)                                               Descrição complementar para entrada do bem.            OPERACIONAL                        NaN
PCMOVCIAPPREENT          DESCRFUNCAOBEM  VARCHAR2(255)                                Descrição da função do bem na atividade do estabelecimento            OPERACIONAL                        NaN
PCMOVCIAPPREENT       GERADOCONTASPAGAR    VARCHAR2(1)                                                            Gerado contas a pagar para NF.            OPERACIONAL                        NaN
PCMOVCIAPPREENT     GERAICMSLIVROFISCAL    VARCHAR2(1)                                                                Gera ICMS no Livro Fiscal.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                     IVA    NUMBER(8,4)                                                                           Percentual IVA.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               MODBCICMS    VARCHAR2(1)                                            Modalidade de Redução da Base de Cálculo do ST            OPERACIONAL                        NaN
PCMOVCIAPPREENT              MOTDESICMS    VARCHAR2(1)                                                             Motivo da Desoneração do ICMS            OPERACIONAL                        NaN
PCMOVCIAPPREENT             MOVBCICMSST    VARCHAR2(1)                                                  Modalidade de Base de Cálculo do ICMS ST            OPERACIONAL                        NaN
PCMOVCIAPPREENT                     NCM   VARCHAR2(15)                                                            Nomenclatura Comum do Mercosul            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 NUMNOTA   NUMBER(10,0)                                                                    Número da Nota Fiscal.            OPERACIONAL                        NaN
PCMOVCIAPPREENT           NUMPATRIMONIO   VARCHAR2(20)                                                            Indica o número do patrimônio.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  NUMPED   NUMBER(10,0)                                                                          Número do pedido            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  NUMSEQ   NUMBER(10,0)                                                                                 Sequência            OPERACIONAL                        NaN
PCMOVCIAPPREENT               NUMSEQPED   NUMBER(10,0)                                                                       Sequência do pedido            OPERACIONAL                        NaN
PCMOVCIAPPREENT           NUMTRANSVENDA   NUMBER(10,0)                                                      Indica o númerro transação de venda.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                   PAUTA    NUMBER(8,4)                                                                           Valor de Pauta.            OPERACIONAL                        NaN
PCMOVCIAPPREENT             PERCBASERED    NUMBER(8,4)                                                            Percentual de Base de Redução.            OPERACIONAL                        NaN
PCMOVCIAPPREENT           PERCBASEREDST    NUMBER(8,4)                                                               Percentual de Redução do ST            OPERACIONAL                        NaN
PCMOVCIAPPREENT    PERCCREDICMPRESUMIDO   NUMBER(12,4)                                                                   Alíquota ICMS presumido            OPERACIONAL                        NaN
PCMOVCIAPPREENT                PERCDESC   NUMBER(12,4)                                                                    Percentual de desconto            OPERACIONAL                        NaN
PCMOVCIAPPREENT        PERCDESPDENTRONF   NUMBER(12,4)                                                               Alíquota de outras despesas            OPERACIONAL                        NaN
PCMOVCIAPPREENT               PERCFRETE   NUMBER(12,4)                                                                      Percentual do Frete.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 PERCICM   NUMBER(12,4)                                                                          Alíquota de ICMS            OPERACIONAL                        NaN
PCMOVCIAPPREENT              PERCICMRED   NUMBER(12,4)                                                                  Alíquota de redução ICMS            OPERACIONAL                        NaN
PCMOVCIAPPREENT      PERCICMSSIMPLESNAC    NUMBER(8,4)                                                       Percentual de ICMS Simples Nacional            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 PERCIPI    NUMBER(8,4)                                                                         Percentual de IPI            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 PERCIVA   NUMBER(12,4)                                                                           Alíquota de IVA            OPERACIONAL                        NaN
PCMOVCIAPPREENT               PERCOFINS   NUMBER(12,4)                                                                        Percentual Cofins.            OPERACIONAL                        NaN
PCMOVCIAPPREENT          PERCOUTRASDESP   NUMBER(12,4)                                                               Percentual Outras Despesas.            OPERACIONAL                        NaN
PCMOVCIAPPREENT             PERCREDICMS   NUMBER(12,4)                                                                    Alíquota de Créd. ICMS            OPERACIONAL                        NaN
PCMOVCIAPPREENT              PERCSEGURO   NUMBER(12,4)                                                                        Alíquota de seguro            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  PERCST   NUMBER(12,4)                                                                          Percentual de ST            OPERACIONAL                        NaN
PCMOVCIAPPREENT             PERCSUFRAMA   NUMBER(12,4)                                                                       Percentual Suframa.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  PERPIS   NUMBER(12,4)                                                                           Percentual Pis.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                PLIQUIDO   NUMBER(18,6)                                                                             Preço liquido            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 PTABELA   NUMBER(18,6)                                                               Preço de tabela do produto.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               PUNITCONT   NUMBER(18,6)                                                                 Indica o valor unitário.             OPERACIONAL                        NaN
PCMOVCIAPPREENT              QTBAIXADOS   NUMBER(18,6)                                         Quantidade de itens dos Bens Patrimoniais Baixada            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  QTCONT   NUMBER(16,4)                                                                     Indica a quantidade.             OPERACIONAL                        NaN
PCMOVCIAPPREENT          QTDTRANSFERIDA   NUMBER(16,4)                                                            Quantidade transferida do bem.            OPERACIONAL                        NaN
PCMOVCIAPPREENT         QTMESESCREDCIAP    NUMBER(4,0)                                           Qtd. Meses para aproveitamento do crédito CIAP.            OPERACIONAL                        NaN
PCMOVCIAPPREENT          REDBASEALIQEXT   NUMBER(12,4)                                                               Redução da alíquota externa            OPERACIONAL                        NaN
PCMOVCIAPPREENT              REDBASEIVA   NUMBER(12,4)                                                                            Redução de IVA            OPERACIONAL                        NaN
PCMOVCIAPPREENT              ROTINALANC    NUMBER(4,0)                                                                           Rotina cadastro            OPERACIONAL                        NaN
PCMOVCIAPPREENT               SEQUENCIA   NUMBER(10,0)                                                             Sequencia de individualização            OPERACIONAL                        NaN
PCMOVCIAPPREENT               SITTRIBUT    VARCHAR2(3)                                                                      Situação tributária.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                      ST   NUMBER(18,6)                                                                  Substituição Tributária.            OPERACIONAL                        NaN
PCMOVCIAPPREENT         TAXADEPRECIACAO   NUMBER(10,2)                                                             Indica a taxa de depreciação.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               TIPOBAIXA    VARCHAR2(2)                                                                   Indica o tipo da baixa.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                TIPOMERC    VARCHAR2(2)                                                                Tipo de mercadoria do CIAP            OPERACIONAL                        NaN
PCMOVCIAPPREENT              TIPOMOVBEM    VARCHAR2(2)                                                              Tipo de movimentação do bem.            OPERACIONAL                        NaN
PCMOVCIAPPREENT         VLADICIONALBCST   NUMBER(18,6)                                                             Valor adicional na base do ST            OPERACIONAL                        NaN
PCMOVCIAPPREENT               VLBASEIPI   NUMBER(16,6)                                                                        Valor base do IPI.            OPERACIONAL                        NaN
PCMOVCIAPPREENT         VLBASEPISCOFINS   NUMBER(22,6)                                                                    Valor base Pis/Cofins.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                VLCOFINS   NUMBER(18,6)                                                                             Valor Cofins.            OPERACIONAL                        NaN
PCMOVCIAPPREENT            VLCREDCOFINS   NUMBER(18,6)                                                                              Valor Cofins            OPERACIONAL                        NaN
PCMOVCIAPPREENT              VLCREDICMS   NUMBER(18,6)                                                                       Valor de Créd. ICMS            OPERACIONAL                        NaN
PCMOVCIAPPREENT               VLCREDPIS   NUMBER(18,6)                                                                                 Valor Pis            OPERACIONAL                        NaN
PCMOVCIAPPREENT         VLCREDPRESUMIDO   NUMBER(18,6)                                                                      Valor ICMS presumido            OPERACIONAL                        NaN
PCMOVCIAPPREENT              VLDESCONTO   NUMBER(18,6)                                                      Indica o valor do desconto do item.             OPERACIONAL                        NaN
PCMOVCIAPPREENT          VLDESPDENTRONF   NUMBER(18,6)                                                                  Valor de outras despesas            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 VLFRETE   NUMBER(18,6)                                                                           Valor do Frete.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  VLICMS   NUMBER(18,3)                                                                  Valor do ICMS do Produto            OPERACIONAL                        NaN
PCMOVCIAPPREENT                   VLIPI   NUMBER(16,6)                                                               Valor do IPI do patrimônio.            OPERACIONAL                        NaN
PCMOVCIAPPREENT            VLOUTRASDESP   NUMBER(18,6)                                                                    Valor Outras Despesas.            OPERACIONAL                        NaN
PCMOVCIAPPREENT             VLPAUTAICMS   NUMBER(18,6)                                                                             Pauta de ICMS            OPERACIONAL                        NaN
PCMOVCIAPPREENT              VLPAUTAIPI   NUMBER(18,6)                                                                              Pauta de IPI            OPERACIONAL                        NaN
PCMOVCIAPPREENT        VLPAUTAPISCOFINS   NUMBER(18,6)                                                                          Pauta Pis/Cofins            OPERACIONAL                        NaN
PCMOVCIAPPREENT                   VLPIS   NUMBER(18,6)                                                                                Valor Pis.            OPERACIONAL                        NaN
PCMOVCIAPPREENT             VLRATUALBEM   NUMBER(22,2)                                                              Indica o valor atual do bem.            OPERACIONAL                        NaN
PCMOVCIAPPREENT            VLRDEPRECIAR   NUMBER(22,2)                                                                  Valor a depreciar do bem            OPERACIONAL                        NaN
PCMOVCIAPPREENT                VLSEGURO   NUMBER(18,6)                                                               Valor seguro do item da NF.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                    VLST   NUMBER(18,6)                                                      Valor de Substituição de Tributação.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               VLSUFRAMA   NUMBER(18,6)                                                                            Valor Suframa.            OPERACIONAL                        NaN
PCMOVCIAPPREENT               DATABAIXA           DATE                                                                   Indica a data da baixa.            OPERACIONAL                        NaN
PCMOVCIAPPREENT                DTCANCEL           DATE                                                                      Data de cancelamento            OPERACIONAL                        NaN
PCMOVCIAPPREENT                   DTMOV           DATE                                                                      Data da movimentação            OPERACIONAL                        NaN
PCMOVCIAPPREENT       VLICMSDESONERACAO   NUMBER(18,6)                                                                  Valor do ICMS Desonerado            OPERACIONAL                        NaN
PCMOVCIAPPREENT       APLICPERCIVAPAUTA    VARCHAR2(1)                                                                      Aplica IVA sob pauta            OPERACIONAL                        NaN
PCMOVCIAPPREENT     APLICREDBASEIVAPLIQ    VARCHAR2(1)                                                           Aplica redução IVA sob pliquido            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 LEASING    VARCHAR2(1)                                 Determina se o bem foi adiquirido via operação de leasing            OPERACIONAL                        NaN
PCMOVCIAPPREENT              TIPOCALCST    VARCHAR2(1)                                                                     Tipo do calculo do ST            OPERACIONAL                        NaN
PCMOVCIAPPREENT         PISCOFINSRETIDO    VARCHAR2(1)                                                                         Pis/Cofins retido            OPERACIONAL                        NaN
PCMOVCIAPPREENT               CODENQIPI    VARCHAR2(3)                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 CODCEST    VARCHAR2(7)                                                                               Código CEST            OPERACIONAL                        NaN
PCMOVCIAPPREENT      PERACRESCIMOFUNCEP   NUMBER(12,4)                                             Percentual do Fundo de Combate a Pobreza ICMS            OPERACIONAL                        NaN
PCMOVCIAPPREENT       VLACRESCIMOFUNCEP   NUMBER(18,6)                                                  Valor do Fundo de Combate a Pobreza ICMS            OPERACIONAL                        NaN
PCMOVCIAPPREENT             VLBASEFCPST   NUMBER(18,6)                                 Valor de base de calculo do Fundo de Combate a Pobreza ST            OPERACIONAL                        NaN
PCMOVCIAPPREENT           VLBASEFCPICMS   NUMBER(18,6)                                    Valor da base de calculo do Fundo de Combate a Pobreza            OPERACIONAL                        NaN
PCMOVCIAPPREENT            ALIQICMSFECP   NUMBER(12,4)                                               Percentual do Fundo de Combate a Pobreza ST            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  VLFECP   NUMBER(18,6)                                                    Valor do Fundo de Combate a Pobreza ST            OPERACIONAL                        NaN
PCMOVCIAPPREENT        BASEDIFALIQUOTAS   NUMBER(18,6)                                                   Base de calculo diferencial de aliquota            OPERACIONAL                        NaN
PCMOVCIAPPREENT        PERCDIFALIQUOTAS   NUMBER(12,4)                                                     Percentual do diferencial de aliquota            OPERACIONAL                        NaN
PCMOVCIAPPREENT          VLDIFALIQUOTAS   NUMBER(18,6)                                                          Valor do diferencial de aliquota            OPERACIONAL                        NaN
PCMOVCIAPPREENT            DESCRICAONFE  VARCHAR2(120)                                                             Descrição do produto no Danfe            OPERACIONAL                        NaN
PCMOVCIAPPREENT        UNIDADECOMERCIAL    VARCHAR2(6)                                                              Unidade comercial do produto            OPERACIONAL                        NaN
PCMOVCIAPPREENT               NUMSEQENT    NUMBER(5,0)                                                               Sequencial de itens da nota            OPERACIONAL                        NaN
PCMOVCIAPPREENT               XML_QTRIB   NUMBER(18,6)                                                     Quantidade tributada do item no Danfe            OPERACIONAL                        NaN
PCMOVCIAPPREENT                XML_QCOM   NUMBER(18,6)                                                     Quantidade comercial do item no Danfe            OPERACIONAL                        NaN
PCMOVCIAPPREENT                   UTRIB   VARCHAR2(12)                                                                        Unidade Tributável            OPERACIONAL                        NaN
PCMOVCIAPPREENT           BASECALCFCPST   NUMBER(18,6)                             Base. Calc. FCP ST (Valor da base de calculo em relação a ST)            OPERACIONAL                        NaN
PCMOVCIAPPREENT               PERCFCPST   NUMBER(18,6)                                               %FCP ST (percentual do FCP em relação a ST)            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 VLFCPST   NUMBER(18,6) VL. FCP ST (valor do FCP em relação ao ST) - deverá calcular automático (Base x Alíquota)            OPERACIONAL                        NaN
PCMOVCIAPPREENT               PDIFIBSUF    NUMBER(7,4)                                                                 Percentual do diferimento            OPERACIONAL                        NaN
PCMOVCIAPPREENT               VDIFIBSUF  NUMBER(23,10)                                                                      Valor do Diferimento            OPERACIONAL                        NaN
PCMOVCIAPPREENT           PREDALIQIBSUF    NUMBER(7,4)                                                         Percentual da redução de alíquota            OPERACIONAL                        NaN
PCMOVCIAPPREENT          PALIQEFETIBSUF    NUMBER(7,4)         Alíquota Efetiva do IBS de competência das UF que será aplicada a Base de Cálculo            OPERACIONAL                        NaN
PCMOVCIAPPREENT                   CSTIS    VARCHAR2(3)                                       Código de Situação Tributária do Imposto Seletivo E            OPERACIONAL                        NaN
PCMOVCIAPPREENT            CCLASSTRIBIS    VARCHAR2(6)                                    Código de Classificação Tributária do Imposto Seletivo            OPERACIONAL                        NaN
PCMOVCIAPPREENT                VLBASEIS  NUMBER(23,10)                                              Valor da Base de Cálculo do Imposto Seletivo            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  ALIQIS   NUMBER(10,4)                                                              Alíquota do Imposto Seletivo            OPERACIONAL                        NaN
PCMOVCIAPPREENT                    VLIS  NUMBER(23,10)                                                                 Valor do Imposto Seletivo            OPERACIONAL                        NaN
PCMOVCIAPPREENT        ALIQESPECIFICAIS   NUMBER(10,4)                                      Alíquota específica por unidade de medida apropriada            OPERACIONAL                        NaN
PCMOVCIAPPREENT              PDIFIBSMUN    NUMBER(7,4)                                                                 Percentual do diferimento            OPERACIONAL                        NaN
PCMOVCIAPPREENT              VDIFIBSMUN  NUMBER(23,10)                                                                      Valor do Diferimento            OPERACIONAL                        NaN
PCMOVCIAPPREENT          PREDALIQIBSMUN    NUMBER(7,4)                                                         Percentual da redução de alíquota            OPERACIONAL                        NaN
PCMOVCIAPPREENT         PALIQEFETIBSMUN    NUMBER(7,4)   Alíquota Efetiva do IBS de competência do Município que será aplicada a Base de Cálculo            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 PDIFCBS    NUMBER(7,4)                                                                 Percentual do diferimento            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 VDIFCBS  NUMBER(23,10)                                                                      Valor do Diferimento            OPERACIONAL                        NaN
PCMOVCIAPPREENT             PREDALIQCBS    NUMBER(7,4)                                                         Percentual da redução de alíquota            OPERACIONAL                        NaN
PCMOVCIAPPREENT            PALIQEFETCBS    NUMBER(7,4)                               Alíquota Efetiva da CBS que será aplicada a Base de Cálculo            OPERACIONAL                        NaN
PCMOVCIAPPREENT       PALIQEFETREGIBSUF    NUMBER(7,4)                                                            Valor da alíquota do IBS da UF            OPERACIONAL                        NaN
PCMOVCIAPPREENT           VTRIBREGIBSUF  NUMBER(23,10)                                                             Valor do Tributo do IBS da UF            OPERACIONAL                        NaN
PCMOVCIAPPREENT       ALIQEFETREGIBSMUN    NUMBER(7,4)                                                     Valor da alíquota do IBS do Município            OPERACIONAL                        NaN
PCMOVCIAPPREENT          VTRIBREGIBSMUN  NUMBER(23,10)                                                      Valor do Tributo do IBS do Município            OPERACIONAL                        NaN
PCMOVCIAPPREENT         PALIQEFETREGCBS    NUMBER(7,4)                                                                  Valor da alíquota da CBS            OPERACIONAL                        NaN
PCMOVCIAPPREENT             VTRIBREGCBS  NUMBER(23,10)                                                                   Valor do Tributo da CBS            OPERACIONAL                        NaN
PCMOVCIAPPREENT         PIBSUFCOMPRAGOV    NUMBER(7,4)                        Alíquota do IBS de competência do Estado para compra governamental            OPERACIONAL                        NaN
PCMOVCIAPPREENT         VIBSUFCOMPRAGOV  NUMBER(23,10)                        Valor do Tributo do IBS da UF calculado  para compra governamental            OPERACIONAL                        NaN
PCMOVCIAPPREENT        PIBSMUNCOMPRAGOV    NUMBER(7,4)                     Alíquota do IBS de competência do Município para compra governamental            OPERACIONAL                        NaN
PCMOVCIAPPREENT        VIBSMUNCOMPRAGOV  NUMBER(23,10)                  Valor do Tributo do IBS do Município calculado para compra governamental            OPERACIONAL                        NaN
PCMOVCIAPPREENT           PCBGCOMPRAGOV    NUMBER(7,4)                                                 Alíquota da CBS para compra governamental            OPERACIONAL                        NaN
PCMOVCIAPPREENT           VCBSCOMPRAGOV  NUMBER(23,10)                               Valor do Tributo da CBS calculado para compra governamental            OPERACIONAL                        NaN
PCMOVCIAPPREENT        CCLASSTRIBIBSCBS    VARCHAR2(6)                                                                      CClassTrib IBS e CBS            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 ALIQCBS   NUMBER(10,4)                                                                              Alíquota CBS            OPERACIONAL                        NaN
PCMOVCIAPPREENT                   VLCBS  NUMBER(23,10)                                                                              Valor da CBS            OPERACIONAL                        NaN
PCMOVCIAPPREENT  CODIGOTRIBUTACAOCBSIBS   NUMBER(10,0)                                                Código da figura tributária na Rotina 4000            OPERACIONAL                        NaN
PCMOVCIAPPREENT               CSTIBSCBS    VARCHAR2(3)                                                                          CST de IBS e CBS            OPERACIONAL                        NaN
PCMOVCIAPPREENT            VLBASEIBSCBS  NUMBER(23,10)                                                              Base de cálculo para IBS CBS            OPERACIONAL                        NaN
PCMOVCIAPPREENT                   IBSUF    NUMBER(7,4)                                                     Alíquota do IBS de competência das UF            OPERACIONAL                        NaN
PCMOVCIAPPREENT      CODIGOTRIBUTACAOIS   NUMBER(10,0)                                                Código da figura tributária na Rotina 4000            OPERACIONAL                        NaN
PCMOVCIAPPREENT                  VIBSUF  NUMBER(23,10)                                                         Valor do IBS de competência da UF            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 PIBSMUN    NUMBER(7,4)                                             Alíquota do IBS de competência dos municípios            OPERACIONAL                        NaN
PCMOVCIAPPREENT                 VIBSMUN  NUMBER(23,10)                                                  Valor do IBS de competência do Município            OPERACIONAL                        NaN
PCMOVCIAPPREENT              CSTTRIBREG    VARCHAR2(3)                                                Código de Situação Tributária do IBS e CBS            OPERACIONAL                        NaN
PCMOVCIAPPREENT           CCLASSTRIBREG    VARCHAR2(6)                                           Código de Classificação Tributária do IBS e CBS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*