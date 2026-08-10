# 📊 Tabela: PCORIGEMDESC

### Estrutura de Colunas e Restrições

      Tabela                      Coluna Tipo/Tamanho                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORIGEMDESC                      NUMPED NUMBER(10,0)                                                                   Número do pedido no Winthor            OPERACIONAL                        NaN
PCORIGEMDESC                   ORIGEMPED  VARCHAR2(1)             Origem do pedido, se 'T' Telemarketing, se  'F' Força de vendas, se 'W' Web, etc.            OPERACIONAL                        NaN
PCORIGEMDESC                     CODPROD  NUMBER(6,0)                                                                             Código do Produto            OPERACIONAL                        NaN
PCORIGEMDESC                 CODAUXILIAR NUMBER(20,0)                                                                     Código de barras auxiliar            OPERACIONAL                        NaN
PCORIGEMDESC                      NUMSEQ NUMBER(20,0)                                                                         Sequência de inserção            OPERACIONAL                        NaN
PCORIGEMDESC                     PTABELA NUMBER(18,6)                     Preço de tabela encontrado e utilizado  como base para validação de preço            OPERACIONAL                        NaN
PCORIGEMDESC                  PEMBALAGEM  VARCHAR2(1)                                  Se o preço do produto é por embalagem "S"    ou pela 201 "N"            OPERACIONAL                        NaN
PCORIGEMDESC                     PERDESC NUMBER(18,6)                                                       Percentual de desconto aplicado no item            OPERACIONAL                        NaN
PCORIGEMDESC                 PERCBASERCA NUMBER(18,6)                                               Percentual de desconto aplicado no Flex  do RCA            OPERACIONAL                        NaN
PCORIGEMDESC             PERCDESCPCATIVI  NUMBER(5,2)                                        Percentual de desconto aplicado por Ramo  de Atividade            OPERACIONAL                        NaN
PCORIGEMDESC                    PERTXFIM  NUMBER(8,4)                                    Se o preço sofreu alteração de taxa do  plano de pagamento            OPERACIONAL                        NaN
PCORIGEMDESC                  PERACRESPF  NUMBER(8,4)         Percentual de acréscimo Pessoa Física /  Jurídica Isenta aplicado ao preço de  tabela            OPERACIONAL                        NaN
PCORIGEMDESC                    TIPODESC  VARCHAR2(1)                                        Se o tipo de desconto é Automático "A" ou Flexível "F"            OPERACIONAL                        NaN
PCORIGEMDESC                   PRECOFIXO  VARCHAR2(1)                                                      Indica se o ptabela gravado é preço fixo            OPERACIONAL                        NaN
PCORIGEMDESC               CODROTINADESC  VARCHAR2(4)                                     Rotina utilizada para lançamento da  política de desconto            OPERACIONAL                        NaN
PCORIGEMDESC             CODPOLITICADESC NUMBER(10,0)                                          Código do registro da política de desconto  validado            OPERACIONAL                        NaN
PCORIGEMDESC            CODROTINABASERCA  VARCHAR2(4)        Rotina utilizada para validar o preço base   de venda para movimentação do Flex do RCA            OPERACIONAL                        NaN
PCORIGEMDESC          CODPOLITICABASERCA NUMBER(10,0)         Código do registro da política de desconto  validado para movimentação do Flex do RCA            OPERACIONAL                        NaN
PCORIGEMDESC              BASEDEBCREDRCA  VARCHAR2(1)                  Indica se o percentual de desconto é  descontado ou não do saldo Flex do RCA            OPERACIONAL                        NaN
PCORIGEMDESC CREDITASOBREPOLITICABASERCA  VARCHAR2(1) Indica se a diferença do preço de tabela e o preço com o desconto é creditado no  Flex do RCA            OPERACIONAL                        NaN
PCORIGEMDESC                 PRIORITARIA  VARCHAR2(1)        Indica se a política de desconto validado estava ou não parametrizada como Prioritária            OPERACIONAL                        NaN
PCORIGEMDESC            PRIORITARIAGERAL  VARCHAR2(1)  Indica se a política de desconto validado estava ou não parametrizada como Prioritária Geral            OPERACIONAL                        NaN
PCORIGEMDESC               ALTERAPTABELA  VARCHAR2(1)                                    Indica se a política de desconto altera o  preço de tabela            OPERACIONAL                        NaN
PCORIGEMDESC VALIDARPOLITICASDESCCLIBLOQ  VARCHAR2(1)                           Indica se o parâmetro 2618 da rotina 132  estava marcado "S" ou "N"            OPERACIONAL                        NaN
PCORIGEMDESC                  DTINCLUSAO         DATE                                               Data em que o registro foi inserido na   tabela            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*