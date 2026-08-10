# 📊 Tabela: PCTRIBUTACAO_EXCECAO

### Estrutura de Colunas e Restrições

              Tabela            Coluna  Tipo/Tamanho                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBUTACAO_EXCECAO CODIGO_TRIBUTACAO  NUMBER(10,0)                                              Código da tributação que vem da tabela PCTRIBUTACAO            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO      TIPO_EMPRESA   VARCHAR2(4)                                  Define o tipo de operação das empresas conforme cadastro na 302            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO       TIPO_PESSOA   VARCHAR2(1)                                                        Define se é pessoa física F ou jurídica J            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO      CONTRIBUINTE   VARCHAR2(1)                                              Define se é do tipo contribuinte Sim (S) ou Não (N)            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO  CONSUMIDOR_FINAL   VARCHAR2(1)                                                  Define se é consumidor final Sim (S) ou Não (N)            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO     ORGAO_PUBLICO   VARCHAR2(1)                                                     Define se é órgão publico Sim (S) ou Não (N)            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO      BASE_CALCULO VARCHAR2(200)                                          Define a base de cálculo que vem do cadastro de formula            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO          ALIQUOTA VARCHAR2(200)                                      Define a alíquota do imposto que vem do cadastro de formula            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO               CST   VARCHAR2(3)                                                 CST referente a nova tributação do CBS, IBS E IS            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO        CCLASSTRIB   VARCHAR2(6) Classificação Tributária do IBS e da CBS; os três primeiros dígitos são idênticos ao CST-IBS/CBS            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO ORIGEM_MERCADORIA  VARCHAR2(30)                                                           Origem da mercadoria disponível da 238            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO         TIPO_MERC VARCHAR2(100)                                                             Tipo da mercadoria disponível na 238            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO    VALOR_ALIQUOTA  NUMBER(10,4)                                                                     Valor da alíquota do imposto            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO         DTCRIACAO          DATE                                                           Data de criação do registro na tabela.            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO        DTULTALTER          DATE                                                  Data da última alteração do registro na tabela.            OPERACIONAL                        NaN
PCTRIBUTACAO_EXCECAO      DTINATIVACAO          DATE                                                                  Data de inativação do registro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*