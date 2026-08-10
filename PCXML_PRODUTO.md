# 📊 Tabela: PCXML_PRODUTO

### Estrutura de Colunas e Restrições

       Tabela         Coluna  Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCXML_PRODUTO        CODPROD   NUMBER(9,0)                                  Código do produto no winthor            OPERACIONAL                        NaN
PCXML_PRODUTO   PROD_NUMNOTA   NUMBER(9,0)                                  Número da nota fiscal do xml            OPERACIONAL                        NaN
PCXML_PRODUTO     PROD_NITEM   NUMBER(4,0)                                         Número do item no xml            OPERACIONAL                        NaN
PCXML_PRODUTO     PROD_CPROD  VARCHAR2(60)                                     Valor da TAG cprod no xml            OPERACIONAL                        NaN
PCXML_PRODUTO      PROD_CEAN  VARCHAR2(20)                                       Código de barras do xml            OPERACIONAL                        NaN
PCXML_PRODUTO     PROD_XPROD VARCHAR2(200)                                          Descrição do produto            OPERACIONAL                        NaN
PCXML_PRODUTO       PROD_NCM  VARCHAR2(10)                                         Ncm do produto no xml            OPERACIONAL                        NaN
PCXML_PRODUTO      PROD_CEST  VARCHAR2(10)                                                   Código CEST            OPERACIONAL                        NaN
PCXML_PRODUTO PROD_INDESCALA   VARCHAR2(1)                                           Indicador de escala            OPERACIONAL                        NaN
PCXML_PRODUTO      PROD_CFOP   VARCHAR2(4)                       Código Fiscal de Operações e Prestações            OPERACIONAL                        NaN
PCXML_PRODUTO      PROD_UCOM   VARCHAR2(6)                                             Unidade comercial            OPERACIONAL                        NaN
PCXML_PRODUTO      PROD_QCOM  NUMBER(18,4)                                          Quantidade comercial            OPERACIONAL                        NaN
PCXML_PRODUTO    PROD_VUNCOM NUMBER(22,10)                                      Valor unitário comercial            OPERACIONAL                        NaN
PCXML_PRODUTO     PROD_VPROD  NUMBER(18,2)                                              Valor do produto            OPERACIONAL                        NaN
PCXML_PRODUTO  PROD_CEANTRIB  VARCHAR2(15)                                               CEAN tributário            OPERACIONAL                        NaN
PCXML_PRODUTO     PROD_UTRIB   VARCHAR2(6)                                            Unidade tributária            OPERACIONAL                        NaN
PCXML_PRODUTO     PROD_QTRIB  NUMBER(18,4)                                         Quantidade tributária            OPERACIONAL                        NaN
PCXML_PRODUTO   PROD_VUNTRIB NUMBER(22,10)                                     Valor unitário tributário            OPERACIONAL                        NaN
PCXML_PRODUTO    PROD_INDTOT   VARCHAR2(1)                                      Indicador de totalização            OPERACIONAL                        NaN
PCXML_PRODUTO      PROD_XPED  VARCHAR2(15)                                           Descrição do pedido            OPERACIONAL                        NaN
PCXML_PRODUTO  PROD_NITEMPED   NUMBER(6,0)                            Número do item no pedido de compra            OPERACIONAL                        NaN
PCXML_PRODUTO   RASTRO_NLOTE  VARCHAR2(40)                               Identificador do numero do lote            OPERACIONAL                        NaN
PCXML_PRODUTO   RASTRO_QLOTE NUMBER(22,12)                                            Quantidade do lote            OPERACIONAL                        NaN
PCXML_PRODUTO    RASTRO_DFAB          DATE                                            Data de fabricação            OPERACIONAL                        NaN
PCXML_PRODUTO    RASTRO_DVAL          DATE                                              Data de validade            OPERACIONAL                        NaN
PCXML_PRODUTO     ATUALIZADO   VARCHAR2(1) Flag para verificar se o registro foi atualizado pelo usuário            OPERACIONAL                        NaN
PCXML_PRODUTO  PROD_CHAVENFE  VARCHAR2(44)                         Chave NFE ao qual o produto se refere            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*