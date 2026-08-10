# 📊 Tabela: PCPEDIFVMANIF

### Estrutura de Colunas e Restrições

       Tabela             Coluna   Tipo/Tamanho                                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIFVMANIF          NUMPEDRCA   NUMBER(10,0)                                                                                                         Número do pedido.            OPERACIONAL                        NaN
PCPEDIFVMANIF            CODPROD    NUMBER(6,0)                                                                                                        Código do produto.            OPERACIONAL                        NaN
PCPEDIFVMANIF                 QT   NUMBER(14,4)                                                                                                       Quantidade vendida.            OPERACIONAL                        NaN
PCPEDIFVMANIF             PVENDA   NUMBER(18,6)                                                                                                           Preço de venda.            OPERACIONAL                        NaN
PCPEDIFVMANIF         BASECALCST   NUMBER(18,6)                                                                                                       Base de calculo ST.            OPERACIONAL                        NaN
PCPEDIFVMANIF                 ST   NUMBER(18,6)                                                                                                              Valor da ST.            OPERACIONAL                        NaN
PCPEDIFVMANIF            PERCICM   NUMBER(12,4)                                                                                                                   % ICMS.            OPERACIONAL                        NaN
PCPEDIFVMANIF        PERCBASERED   NUMBER(12,4)                                                                                                   % de redução base ICMS.            OPERACIONAL                        NaN
PCPEDIFVMANIF           BASEICMS   NUMBER(12,4)                                                                                                  Base de calculo de ICMS.            OPERACIONAL                        NaN
PCPEDIFVMANIF          CANCELADO    VARCHAR2(1)                                                                                                       "S" para cancelado.            OPERACIONAL                        NaN
PCPEDIFVMANIF      OBSERVACAO_PC VARCHAR2(4000) Observações do processamento. Este campo será alimentado pela PC Sistemas com críticas sobre a importação deste registro.            OPERACIONAL                        NaN
PCPEDIFVMANIF        DTALTERACAO           DATE                                                                                             Data de Alteração no registro            OPERACIONAL                        NaN
PCPEDIFVMANIF         DTINCLUSAO           DATE                                                                                              Data de Inclusão no registro            OPERACIONAL                        NaN
PCPEDIFVMANIF        CODAUXILIAR   NUMBER(20,0)                                                                                               Codigo de barras do produto            OPERACIONAL                        NaN
PCPEDIFVMANIF            PERCIPI   NUMBER(12,4)                                                                                                         Percentual de IPI            OPERACIONAL                        NaN
PCPEDIFVMANIF              VLIPI   NUMBER(18,6)                                                                                                              Valor de IPI            OPERACIONAL                        NaN
PCPEDIFVMANIF           SUGESTAO    VARCHAR2(1)                                                                                   Informa se o item foi sugestão de venda            OPERACIONAL                        NaN
PCPEDIFVMANIF           CODCOMBO   NUMBER(10,0)                                                                                                           Código do Combo            OPERACIONAL                        NaN
PCPEDIFVMANIF  DTABERTURAPEDPALM           DATE                                                                                               Data de abertura do pedido.            OPERACIONAL                        NaN
PCPEDIFVMANIF             CGCENT   VARCHAR2(18)                                                                                                           CGC do Cliente.            OPERACIONAL                        NaN
PCPEDIFVMANIF            CODUSUR    NUMBER(4,0)                                                                                                            Código do RCA.            OPERACIONAL                        NaN
PCPEDIFVMANIF       CODPRODTROCA    NUMBER(6,0)                                                                     Código do produto que está sendo entregue ao cliente.            OPERACIONAL                        NaN
PCPEDIFVMANIF            QTTROCA   NUMBER(20,6)                                                                                             Quantidade de itens trocados.            OPERACIONAL                        NaN
PCPEDIFVMANIF          DTVALPROD           DATE                                                                     Data de validade do produto que está sendo recolhido.            OPERACIONAL                        NaN
PCPEDIFVMANIF     DTVALPRODTROCA           DATE                                                                                Data de validade do novo produto entregue.            OPERACIONAL                        NaN
PCPEDIFVMANIF         CODINDENIZ   NUMBER(10,0)                                                                                Código da indenizacao gravada na PCINDCFV.            OPERACIONAL                        NaN
PCPEDIFVMANIF             AVARIA    VARCHAR2(1)                                                           Indica se item está avariado, utilizado pelo processo de troca.            OPERACIONAL                        NaN
PCPEDIFVMANIF   CODAUXILIARTROCA   NUMBER(20,0)                                                                              Codigo de barras do produto a ser recolhido.            OPERACIONAL                        NaN
PCPEDIFVMANIF           VLOUTROS   NUMBER(18,6)                                                                                                  Valor de outras despesas            OPERACIONAL                        NaN
PCPEDIFVMANIF          TIPOCOMBO    VARCHAR2(1)                                                    Identifica se o compo 'A - Ativando campanha ' ou 'C - Combo Contínuo'            OPERACIONAL                        NaN
PCPEDIFVMANIF      VLBASEFCPICMS   NUMBER(18,6)                                                                    Valor da base de calculo do Fundo de Combate a Pobreza            OPERACIONAL                        NaN
PCPEDIFVMANIF        VLBASEFCPST   NUMBER(18,6)                                                                 Valor de base de calculo do Fundo de Combate a Pobreza ST            OPERACIONAL                        NaN
PCPEDIFVMANIF       VLBCFCPSTRET   NUMBER(18,6)                                                               Valor da base de calculo do FCP retido anteriormente por ST            OPERACIONAL                        NaN
PCPEDIFVMANIF        PERFCPSTRET   NUMBER(12,4)                                                        Percentual do FCP retido anteriormente por Substituição Tributaria            OPERACIONAL                        NaN
PCPEDIFVMANIF         VLFCPSTRET   NUMBER(18,6)                                                                           Valor do FCP retido por Substituição Tributária            OPERACIONAL                        NaN
PCPEDIFVMANIF           PERFCPSN   NUMBER(12,4)                                                                Aliquota aplicável de cálculo do crédito(SIMPLES NACIONAL)            OPERACIONAL                        NaN
PCPEDIFVMANIF    VLCREDFCPICMSSN   NUMBER(18,6)                         Valor crédito do ICMS que pode ser aproveitado nos termos do art. 23 da LC 123 (SIMPLES NACIONAL)            OPERACIONAL                        NaN
PCPEDIFVMANIF             VLFECP   NUMBER(18,6)                                                                                                               Valor Fecp.            OPERACIONAL                        NaN
PCPEDIFVMANIF  VLACRESCIMOFUNCEP   NUMBER(18,6)                                                                                                    Valor Acrescimo FUNCEP            OPERACIONAL                        NaN
PCPEDIFVMANIF PERACRESCIMOFUNCEP   NUMBER(12,4)                                                                                               Percentual Acrescimo FUNCEP            OPERACIONAL                        NaN
PCPEDIFVMANIF       ALIQICMSFECP   NUMBER(12,4)                                                                                                    Alíquota de ICMS Fecp.            OPERACIONAL                        NaN
PCPEDIFVMANIF            BONIFIC    VARCHAR2(1)                                                                                      Indica se o item é bonificado ou não            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*