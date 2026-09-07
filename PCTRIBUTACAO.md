# 📊 Tabela: PCTRIBUTACAO

### Estrutura de Colunas e Restrições

      Tabela                   Coluna  Tipo/Tamanho                                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBUTACAO         CONSUMIDOR_FINAL   VARCHAR2(1)                                                       Define se é consumidor final Sim (S) ou Não (N)            OPERACIONAL                        NaN
PCTRIBUTACAO        CODIGO_TRIBUTACAO  NUMBER(10,0)                                                                          Código sequencial do tributo    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTACAO     DESCRICAO_TRIBUTACAO VARCHAR2(100)                                                                               Descrição da tributação            OPERACIONAL                        NaN
PCTRIBUTACAO             TIPO_IMPOSTO   VARCHAR2(6)                                               Tipo do imposto que está sendo cadastrado, CBSIBS ou IS            OPERACIONAL                        NaN
PCTRIBUTACAO            LOCAL_CONSUMO   VARCHAR2(7) Responsável por armazenar o local de consumo da tributação, poder BR as UF ou o código do município.             OPERACIONAL                        NaN
PCTRIBUTACAO            TIPO_OPERACAO   VARCHAR2(1)                                                        Define se é operação de Entrada(E) ou Saída(S)            OPERACIONAL                        NaN
PCTRIBUTACAO                DEVOLUCAO   VARCHAR2(1)                                   Define se é uma operação especifica de devolução Sim (S) ou Não (N)            OPERACIONAL                        NaN
PCTRIBUTACAO             TIPO_EMPRESA   VARCHAR2(4)                                       Define o tipo de operação das empresas conforme cadastro na 302            OPERACIONAL                        NaN
PCTRIBUTACAO              TIPO_PESSOA   VARCHAR2(1)                                                             Define se é pessoa física F ou jurídica J            OPERACIONAL                        NaN
PCTRIBUTACAO             CONTRIBUINTE   VARCHAR2(1)                                                   Define se é do tipo contribuinte Sim (S) ou Não (N)            OPERACIONAL                        NaN
PCTRIBUTACAO            ORGAO_PUBLICO   VARCHAR2(1)                                                          Define se é órgão publico Sim (S) ou Não (N)            OPERACIONAL                        NaN
PCTRIBUTACAO             BASE_CALCULO VARCHAR2(200)                                               Define a base de cálculo que vem do cadastro de formula            OPERACIONAL                        NaN
PCTRIBUTACAO                 ALIQUOTA VARCHAR2(200)                                           Define a alíquota do imposto que vem do cadastro de formula            OPERACIONAL                        NaN
PCTRIBUTACAO                      CST   VARCHAR2(3)                                                      CST referente a nova tributação do CBS, IBS E IS            OPERACIONAL                        NaN
PCTRIBUTACAO               CCLASSTRIB   VARCHAR2(6)      Classificação Tributária do IBS e da CBS; os três primeiros dígitos são idênticos ao CST-IBS/CBS            OPERACIONAL                        NaN
PCTRIBUTACAO        ORIGEM_MERCADORIA  VARCHAR2(30)                                                                Origem da mercadoria disponível da 238            OPERACIONAL                        NaN
PCTRIBUTACAO                TIPO_MERC VARCHAR2(100)                                                                  Tipo da mercadoria disponível na 238            OPERACIONAL                        NaN
PCTRIBUTACAO        DTINICIO_VIGENCIA          DATE                                                                            Data de inicio da vigência            OPERACIONAL                        NaN
PCTRIBUTACAO           DTFIM_VIGENCIA          DATE                                                                               Data de fim da vigência            OPERACIONAL                        NaN
PCTRIBUTACAO                   STATUS   VARCHAR2(1)                                                                 Status da tributação Ativo ou Inativo            OPERACIONAL                        NaN
PCTRIBUTACAO           VALOR_ALIQUOTA  NUMBER(10,4)                                                                          Valor da alíquota do tributo            OPERACIONAL                        NaN
PCTRIBUTACAO                DTCRIACAO          DATE                                                                Data de criação do registro na tabela.            OPERACIONAL                        NaN
PCTRIBUTACAO               DTULTALTER          DATE                                                       Data da última alteração do registro na tabela.            OPERACIONAL                        NaN
PCTRIBUTACAO             DTINATIVACAO          DATE                                                                       Data de inativação do registro.            OPERACIONAL                        NaN
PCTRIBUTACAO               DTEXCLUSAO          DATE                                                                          Data da exclusão do registro            OPERACIONAL                        NaN
PCTRIBUTACAO              SOMATOTALNF   VARCHAR2(1)                                   Define se o campo irá somar no valor total da nota S(Sim) ou N(Não)            OPERACIONAL                        NaN
PCTRIBUTACAO       TIPO_LOCAL_CONSUMO   VARCHAR2(2)                              Define o tipo do local de consumo, que pode ser Geral(G) ou Município(M)            OPERACIONAL                        NaN
PCTRIBUTACAO      LOCAL_CONSUMO_GERAL   VARCHAR2(2)                                                                Define qual UF será o local de consumo            OPERACIONAL                        NaN
PCTRIBUTACAO  LOCAL_CONSUMO_MUNICIPIO  NUMBER(10,0)                                                        Define o município que será o local de consumo            OPERACIONAL                        NaN
PCTRIBUTACAO                 PERC_CBS   NUMBER(7,4)                                                                                     Percentual do CBS            OPERACIONAL                        NaN
PCTRIBUTACAO             PERC_RED_CBS   NUMBER(7,4)                                                              Percentual de redução da aliquota do CBS            OPERACIONAL                        NaN
PCTRIBUTACAO              PERC_IBS_UF   NUMBER(7,4)                                                                      Percentual do IBS competência UF            OPERACIONAL                        NaN
PCTRIBUTACAO          PERC_RED_IBS_UF   NUMBER(7,4)                                            Percentual de redução da alíquota do IBS competência da UF            OPERACIONAL                        NaN
PCTRIBUTACAO             PERC_IBS_MUN   NUMBER(7,4)                                                          Percentual do IBS competência do município.             OPERACIONAL                        NaN
PCTRIBUTACAO         PERC_RED_IBS_MUN   NUMBER(7,4)                                    Percentual de redução da alíquota do IBS competência do município.            OPERACIONAL                        NaN
PCTRIBUTACAO                  PERC_IS   NUMBER(7,4)                                                                        Percentual do Imposto Seletivo            OPERACIONAL                        NaN
PCTRIBUTACAO                DTALTERC5  TIMESTAMP(6)                                                                                     Data de alteração            OPERACIONAL                        NaN
PCTRIBUTACAO           TIPO_DOCUMENTO VARCHAR2(200)                         Responsável por armazenar os tipos de documentos ficais aceitos na tributação            OPERACIONAL                        NaN
PCTRIBUTACAO           CODTRIBREGULAR  NUMBER(10,0)                                                                          Codigo de tributacao regular            OPERACIONAL                        NaN
PCTRIBUTACAO PERC_DIFERIMENTO_IBS_MUN   NUMBER(7,4)                                                        Percentual do diferimento referente ao IBS Mun            OPERACIONAL                        NaN
PCTRIBUTACAO  PERC_DIFERIMENTO_IBS_UF   NUMBER(7,4)                                                         Percentual do diferimento referente ao IBS UF            OPERACIONAL                        NaN
PCTRIBUTACAO     PERC_DIFERIMENTO_CBS   NUMBER(7,4)                                                            Percentual do diferimento referente ao CBS            OPERACIONAL                        NaN
PCTRIBUTACAO          CODTIPOCREDPRES   NUMBER(2,0)                                               Define qual a regra de crédito presumido será utilizada            OPERACIONAL                        NaN
PCTRIBUTACAO          PERCCREDPRESIBS   NUMBER(7,4)                                                     Percentual IBS. Aplicado sobre a base de cálculo.            OPERACIONAL                        NaN
PCTRIBUTACAO          PERCCREDPRESCBS   NUMBER(7,4)                                                     Percentual CBS. Aplicado sobre a base de cálculo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*