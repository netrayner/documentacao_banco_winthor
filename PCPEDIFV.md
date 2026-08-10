# 📊 Tabela: PCPEDIFV

### Estrutura de Colunas e Restrições

  Tabela                    Coluna   Tipo/Tamanho                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIFV                 NUMPEDRCA   NUMBER(10,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFV                    CGCCLI   VARCHAR2(18)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFV                   CODUSUR    NUMBER(4,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFV         DTABERTURAPEDPALM           DATE                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFV                   CODPROD    NUMBER(6,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFV                        QT   NUMBER(20,6)                                                                                               NaN            OPERACIONAL                        NaN
PCPEDIFV                    PVENDA   NUMBER(18,6)                                                                           Descricao coluna PVENDA            OPERACIONAL                        NaN
PCPEDIFV               CODAUXILIAR   NUMBER(20,0)                                                                                               NaN            OPERACIONAL                        NaN
PCPEDIFV                    NUMSEQ   NUMBER(20,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIFV           CODFILIALRETIRA    VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCPEDIFV               QT_FATURADA   NUMBER(20,6)                                                                                               NaN            OPERACIONAL                        NaN
PCPEDIFV             OBSERVACAO_PC VARCHAR2(4000)                                                                                               NaN            OPERACIONAL                        NaN
PCPEDIFV                DTINCLUSAO           DATE                                                                      Data de Inclusão no registro            OPERACIONAL                        NaN
PCPEDIFV             UNIDADE_FRIOS    VARCHAR2(2)                                                           Determina o tipo de unidade para frios.            OPERACIONAL                        NaN
PCPEDIFV                   BONIFIC    VARCHAR2(1)                       Serve para o palm enviar para a package a informação se o item é bonificado            OPERACIONAL                        NaN
PCPEDIFV                  CODCOMBO   NUMBER(10,0)                                                                          Informar código do combo            OPERACIONAL                        NaN
PCPEDIFV       POLITICAPRIORITARIA    VARCHAR2(1)                                         Informar se item utiliza politica de desconto prioritaria            OPERACIONAL                        NaN
PCPEDIFV               DTALTERACAO           DATE                                                                     Data de Alteração no registro            OPERACIONAL                        NaN
PCPEDIFV               PERCDESCEDI   NUMBER(18,6)                                                           Percentual de Desconto enviado pelo EDI            OPERACIONAL                        NaN
PCPEDIFV         CODMOTIVONAOATEND    NUMBER(3,0)                                                               Código do Motivo de Não Atendimento            OPERACIONAL                        NaN
PCPEDIFV             PERDESCBOLETO   NUMBER(12,4)                                                                  Percentual de Desconto do Boleto            OPERACIONAL                        NaN
PCPEDIFV                 CODPRODOL   VARCHAR2(20)                                                                           Código do Produto no OL            OPERACIONAL                        NaN
PCPEDIFV                     CORTE    VARCHAR2(1)                                                    Informa se teve corte ou não no item do pedido            OPERACIONAL                        NaN
PCPEDIFV                  SUGESTAO    VARCHAR2(1)                                                           Informa se o item foi sugestão de venda            OPERACIONAL                        NaN
PCPEDIFV               TIPOENTREGA    VARCHAR2(2)                                                              Tipo de entrega do item para venda 7            OPERACIONAL                        NaN
PCPEDIFV                    NUMPED   NUMBER(10,0)                                                                       Número do pedido no winthor            OPERACIONAL                        NaN
PCPEDIFV           RESTRICAOTRANSP    VARCHAR2(1)                                                         Indica o tipo de restrição de transporte.            OPERACIONAL                        NaN
PCPEDIFV                  TIPOTV11    VARCHAR2(1)                              Define se o produto será a enviar(E) ou recolher(R) nos pedidos TV11            OPERACIONAL                        NaN
PCPEDIFV                 VERSAOPKG   VARCHAR2(20)                                                          Versão da Package que Processou o Pedido            OPERACIONAL                        NaN
PCPEDIFV            VLBASEPARTDEST   NUMBER(18,6)                                                         Valor da base de calculo na Uf de destino            OPERACIONAL                        NaN
PCPEDIFV                   ALIQFCP   NUMBER(18,6)                                                      Aliquota de FCP (fundo de combate a pobreza)            OPERACIONAL                        NaN
PCPEDIFV           ALIQINTERNADEST   NUMBER(18,6)                                                         Aliquota de ICMS interna na UF de destino            OPERACIONAL                        NaN
PCPEDIFV                 VLFCPPART   NUMBER(18,6)                                                                                   Valor do FUNCEP            OPERACIONAL                        NaN
PCPEDIFV            VLICMSPARTDEST   NUMBER(18,6)                                                     Valor do ICMS Interestadual para a UF Destino            OPERACIONAL                        NaN
PCPEDIFV                VLICMSPART   NUMBER(18,6)       Valor de ICMS de partilha (valor que deverá ser utilizado para acrescer o valor do produto)            OPERACIONAL                        NaN
PCPEDIFV              PERCPROVPART    NUMBER(5,2)                                                         Percentual provisório de partilha de ICMS            OPERACIONAL                        NaN
PCPEDIFV         VLICMSDIFALIQPART   NUMBER(22,6)                                      Valor de ICMS do diferencial de aliquota da partilha de ICMS            OPERACIONAL                        NaN
PCPEDIFV           PERCBASEREDPART    NUMBER(5,2)                                                              Redução aplicada na base de Partilha            OPERACIONAL                        NaN
PCPEDIFV             VLICMSPARTREM   NUMBER(18,6)                                                       Valor do ICMS de partilha para UF remetente            OPERACIONAL                        NaN
PCPEDIFV         ALIQINTERORIGPART   NUMBER(18,6)                                                                 Aliquota de  ICMS da UF de origem            OPERACIONAL                        NaN
PCPEDIFV          USAUNIDADEMASTER    VARCHAR2(1)                          Indica se a quantidade do produto deve ser múltipla da quantidade master            OPERACIONAL                        NaN
PCPEDIFV      CODDESCONTOSIMULADOR    NUMBER(8,0)                                                                   Código de simulador do desconto            OPERACIONAL                        NaN
PCPEDIFV          DEVOLUCAOCARCACA    VARCHAR2(1)                                       Define se o produto irá ser com devolução de carcaça ou não            OPERACIONAL                        NaN
PCPEDIFV             VLDESCCARCACA   NUMBER(18,6)                                                             Contém o valor do desconto de carcaça            OPERACIONAL                        NaN
PCPEDIFV                 TIPOCOMBO    VARCHAR2(1)                            Identifica se o compo 'A - Ativando campanha ' ou 'C - Combo Contínuo'            OPERACIONAL                        NaN
PCPEDIFV MOVIMENTACONTACORRENTERCA    VARCHAR2(1)                                            Identifica se irá movimentar conta corrente RCA ou não            OPERACIONAL                        NaN
PCPEDIFV             VLBASEFCPICMS   NUMBER(18,6)                                            Valor da base de calculo do Fundo de Combate a Pobreza            OPERACIONAL                        NaN
PCPEDIFV               VLBASEFCPST   NUMBER(18,6)                                         Valor de base de calculo do Fundo de Combate a Pobreza ST            OPERACIONAL                        NaN
PCPEDIFV              VLBCFCPSTRET   NUMBER(18,6)                                       Valor da base de calculo do FCP retido anteriormente por ST            OPERACIONAL                        NaN
PCPEDIFV               PERFCPSTRET   NUMBER(12,4)                                Percentual do FCP retido anteriormente por Substituição Tributaria            OPERACIONAL                        NaN
PCPEDIFV                VLFCPSTRET   NUMBER(18,6)                                                   Valor do FCP retido por Substituição Tributária            OPERACIONAL                        NaN
PCPEDIFV                  PERFCPSN   NUMBER(12,4)                                        Aliquota aplicável de cálculo do crédito(SIMPLES NACIONAL)            OPERACIONAL                        NaN
PCPEDIFV           VLCREDFCPICMSSN   NUMBER(18,6) Valor crédito do ICMS que pode ser aproveitado nos termos do art. 23 da LC 123 (SIMPLES NACIONAL)            OPERACIONAL                        NaN
PCPEDIFV                    VLFECP   NUMBER(18,6)                                                                                       Valor Fecp.            OPERACIONAL                        NaN
PCPEDIFV         VLACRESCIMOFUNCEP   NUMBER(18,6)                                                                            Valor Acrescimo FUNCEP            OPERACIONAL                        NaN
PCPEDIFV        PERACRESCIMOFUNCEP   NUMBER(12,4)                                                                       Percentual Acrescimo FUNCEP            OPERACIONAL                        NaN
PCPEDIFV              ALIQICMSFECP   NUMBER(12,4)                                                                            Alíquota de ICMS Fecp.            OPERACIONAL                        NaN
PCPEDIFV              PERREDCOMISS   NUMBER(18,6)                                                                       Aplicar Redução de Comissão            OPERACIONAL                        NaN
PCPEDIFV                 NUMPEDCLI   NUMBER(10,0)                                             Indica o número do pedido original de comprar do item            OPERACIONAL                        NaN
PCPEDIFV                NUMITEMPED    NUMBER(8,0)                                                                     NÚMERO DO ITEM NO XML DA NOTA            OPERACIONAL                        NaN
PCPEDIFV               CODDESCONTO    NUMBER(8,0)                                                     Código da politica prioritária que será usada            OPERACIONAL                        NaN
PCPEDIFV            CODDESCONTOMED    NUMBER(8,0)                                           Código do desconto selecionado no pedido de venda farma            OPERACIONAL                        NaN
PCPEDIFV                 DTENTREGA           DATE                                                                                   Data de entrega            OPERACIONAL                        NaN
PCPEDIFV            RESPQUESTFRETE    VARCHAR2(1)                                                       Resposta do Questionamento do rateio frete.            OPERACIONAL                        NaN
PCPEDIFV               USACASHBACK    VARCHAR2(1)                                  Indica que o % informado PERDESCBOLETO é relacionado a CASHBACK.            OPERACIONAL                        NaN
PCPEDIFV                      IDFV   VARCHAR2(60)                                                Campo que identifica o pedido do força de vendas\t            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*