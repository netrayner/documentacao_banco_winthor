# 📊 Tabela: PCREGIAO

### Estrutura de Colunas e Restrições

  Tabela             Coluna Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREGIAO          NUMREGIAO  NUMBER(4,0)                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCREGIAO             REGIAO VARCHAR2(40)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO           PERFRETE  NUMBER(8,4)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO                 UF  VARCHAR2(2)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO          VLFRETEKG NUMBER(10,4)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO          CODFILIAL  VARCHAR2(2)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO           SEGMENTO  VARCHAR2(1)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO  PERFRETETERCEIROS  NUMBER(8,4)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO   PERFRETEESPECIAL  NUMBER(8,4)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO             STATUS  VARCHAR2(1)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO             TAREPF  VARCHAR2(1)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO          REGIAOZFM  VARCHAR2(1)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO     PERFRETECONHEC  NUMBER(8,4)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO         VLMINFATBK NUMBER(14,6)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO         VLMINFATCH NUMBER(14,6)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO          EXPORTAFV  NUMBER(1,0)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO          NUMTABELA VARCHAR2(20)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO CODESTABELECIMENTO  VARCHAR2(3)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO        ATUALIZAF11  VARCHAR2(1)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO                OBS VARCHAR2(60)                                 Campo para informar observações importantes sobre a Região.             OPERACIONAL                        NaN
PCREGIAO    VLFRETEKGPADRAO NUMBER(10,4) Valor de Frete Kg por Região, que será gravado na Tabela de Preço (PCTABPR.VLACRESFRETEKG).             OPERACIONAL                        NaN
PCREGIAO     VLFRETEKGVENDA NUMBER(10,4)                                                               Valor de Venda Kg por Região.             OPERACIONAL                        NaN
PCREGIAO         VLMINVENDA NUMBER(18,6)                                        Valor mínimo de venda para cálculo da taxa de entrega            OPERACIONAL                        NaN
PCREGIAO            VLTXENT NUMBER(18,6)                                                                     Valor da taxa de entrega            OPERACIONAL                        NaN
PCREGIAO   CODREPRESENTANTE  VARCHAR2(4)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO         DTMXSALTER         DATE                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO             SYNCFV  VARCHAR2(1)                                                                                          NaN            OPERACIONAL                        NaN
PCREGIAO       USAECOMMERCE  VARCHAR2(1)                            Define se os preços da região serão exportados para o E-Commerce.            OPERACIONAL                        NaN
PCREGIAO          DTALTERC5 TIMESTAMP(6)                                                                            Data de alteração            OPERACIONAL                        NaN
PCREGIAO        DTALTERACAO TIMESTAMP(6)  Data e hora de alteração preenchido caso algum registro seja alterado ou excluído na tabela            OPERACIONAL                        NaN
PCREGIAO          DTCRIACAO TIMESTAMP(6)                                                Data e hora de criação de registro na tabela.            OPERACIONAL                        NaN
PCREGIAO        TIPOEMPRESA  VARCHAR2(4)                                                                    Indica o tipo da empresa.            OPERACIONAL                        NaN
PCREGIAO           ORGAOPUB  VARCHAR2(1)                                                                        Tipo de Órgão Público            OPERACIONAL                        NaN
PCREGIAO       CONTRIBUINTE  VARCHAR2(1)                                                                                 Contribuinte            OPERACIONAL                        NaN
PCREGIAO    CONSUMIDORFINAL  VARCHAR2(1)                                                                             Consumidor Final            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*