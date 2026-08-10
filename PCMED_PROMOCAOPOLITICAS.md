# 📊 Tabela: PCMED_PROMOCAOPOLITICAS

### Estrutura de Colunas e Restrições

                 Tabela                   Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMED_PROMOCAOPOLITICAS                  TIPOREG  VARCHAR2(3)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                   CODIGO  NUMBER(9,0)                           Descricao coluna CODIGO            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                 PERCDESC NUMBER(10,4)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS              PERCDESCFIN NUMBER(10,4)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS               PERCOMMINT NUMBER(10,4)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                PERCOMREP NUMBER(10,4)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                PERCOMEXT NUMBER(10,4)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                PRECOFIXO NUMBER(18,6)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS              OBRIGATORIO  VARCHAR2(1)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                    QTKIT NUMBER(10,4)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS            QTOBRIGATORIO NUMBER(10,4)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS PARTICIPACOMISSGARANTIDA  VARCHAR2(1)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS          PERCDESCBASERCA NUMBER(10,4)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS      CODIGOINTEGRACAOWMS VARCHAR2(20)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS     VLDESCCMVPROMOCAOMED NUMBER(18,6)                                               NaN            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                  NUMLOTE VARCHAR2(50)                                   Lote Fabricação            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS          INICIOINTERVALO NUMBER(10,4)                     Inicio Intervalo Quantidade\t            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS             FIMINTERVALO NUMBER(10,4)                          Fim Intervalo Quantidade            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                VALORCOTA NUMBER(18,2)                                     Valor da Cota            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS   CONSIDERACALCGIROMEDIC  VARCHAR2(1)                                 Considera no Giro            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS     CREDITASOBREPOLITICA  VARCHAR2(1)                        Credita conta corrente rca            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS           BASECREDDEBRCA  VARCHAR2(1) Realiza debito e credito de conta corrente do rca            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                 DTINICIO         DATE                                      Data Inicial            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS                    DTFIM         DATE                                        Data Final            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS  PERMITIRAUMENTARQTDEKIT  VARCHAR2(1)             Permitir aumentar a quantidade do kit            OPERACIONAL                        NaN
PCMED_PROMOCAOPOLITICAS     REGRAALTERARDESCONTO  VARCHAR2(1)              Regra de Alteração do Desconto/Preço            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*