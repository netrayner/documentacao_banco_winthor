# 📊 Tabela: PCRECEITAPRODUCAO

### Estrutura de Colunas e Restrições

           Tabela               Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECEITAPRODUCAO            CODFILIAL   VARCHAR2(2)                             Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEITAPRODUCAO              CODPROD   NUMBER(6,0)                  Código do produto produzido    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEITAPRODUCAO     PRODUZIDOUNIDADE  NUMBER(22,6)                          Unidade da produção            OPERACIONAL                        NaN
PCRECEITAPRODUCAO          PRODUZIDOKG  NUMBER(22,6)                     KG produzido por receita            OPERACIONAL                        NaN
PCRECEITAPRODUCAO        PRODUZIDOPESO  NUMBER(22,6)                   Peso produzido por receita            OPERACIONAL                        NaN
PCRECEITAPRODUCAO   CAPACIDADEEQUIPMAX  NUMBER(22,6)             Capacidade máxima do equipamento            OPERACIONAL                        NaN
PCRECEITAPRODUCAO   CAPACIDADEEQUIPMIN  NUMBER(22,6)             Capacidade mínima do equipamento            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         TEMPOPREPARO  NUMBER(22,6)                             Tempo de preparo            OPERACIONAL                        NaN
PCRECEITAPRODUCAO      PESOINGREDIENTE  NUMBER(22,6)                  Peso total dos ingredientes            OPERACIONAL                        NaN
PCRECEITAPRODUCAO            PERDAEMKG  NUMBER(22,6)                                  Perda em KG            OPERACIONAL                        NaN
PCRECEITAPRODUCAO    PERDAEMPRECENTUAL  NUMBER(22,6)                          Perda em percentual            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         PRECOUNIDADE  NUMBER(22,6)                            Preço por unidade            OPERACIONAL                        NaN
PCRECEITAPRODUCAO              PRECOKG  NUMBER(22,6)                                 Preço por KG            OPERACIONAL                        NaN
PCRECEITAPRODUCAO       PRECOMAODEOBRA  NUMBER(22,6)                       Preço por mão de obras            OPERACIONAL                        NaN
PCRECEITAPRODUCAO       PRECOEMBALAGEM  NUMBER(22,6)                          Preço por embalagem            OPERACIONAL                        NaN
PCRECEITAPRODUCAO    PRECOINGREDIENTES  NUMBER(22,6)                       Preço por ingredientes            OPERACIONAL                        NaN
PCRECEITAPRODUCAO           PRECOFINAL  NUMBER(22,6)                                  Preço final            OPERACIONAL                        NaN
PCRECEITAPRODUCAO    PRODUZIRNASEGUNDA   VARCHAR2(1)                            Produz na segunga            OPERACIONAL                        NaN
PCRECEITAPRODUCAO      PRODUZIRNATERCA   VARCHAR2(1)                              Produz na terça            OPERACIONAL                        NaN
PCRECEITAPRODUCAO     PRODUZIRNAQUARTA   VARCHAR2(1)                             Produz na quarta            OPERACIONAL                        NaN
PCRECEITAPRODUCAO     PRODUZIRNAQUINTA   VARCHAR2(1)                             Produz na quinta            OPERACIONAL                        NaN
PCRECEITAPRODUCAO      PRODUZIRNASEXTA   VARCHAR2(1)                              Produz na sexta            OPERACIONAL                        NaN
PCRECEITAPRODUCAO    PRODUZIRNSASABADO   VARCHAR2(1)                             Produz no sábado            OPERACIONAL                        NaN
PCRECEITAPRODUCAO    PRODUZIRNADOMINGO   VARCHAR2(1)                            Produz no domingo            OPERACIONAL                        NaN
PCRECEITAPRODUCAO                SETOR  VARCHAR2(15)                                        Setor            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         QTPRODUCAO01  NUMBER(22,6)                   Quantidade para produção 1            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         QTPRODUCAO02  NUMBER(22,6)                   Quantidade para produção 2            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         QTPRODUCAO03  NUMBER(22,6)                   Quantidade para produção 3            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         QTPRODUCAO04  NUMBER(22,6)                   Quantidade para produção 4            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         QTPRODUCAO05  NUMBER(22,6)                   Quantidade para produção 5            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         QTPRODUCAO06  NUMBER(22,6)                   Quantidade para produção 6            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         QTPRODUCAO07  NUMBER(22,6)                   Quantidade para produção 7            OPERACIONAL                        NaN
PCRECEITAPRODUCAO         QTPRODUCAO08  NUMBER(22,6)                   Quantidade para produção 8            OPERACIONAL                        NaN
PCRECEITAPRODUCAO       ETIQUETATITULO VARCHAR2(100)                           Título da etiqueta            OPERACIONAL                        NaN
PCRECEITAPRODUCAO  ETIQUETAINGREDIENTE          CLOB                     Ingredientes na etiqueta            OPERACIONAL                        NaN
PCRECEITAPRODUCAO    NUMDIASVENCIMENTO   NUMBER(4,0)      Número de dias de vencimento / validade            OPERACIONAL                        NaN
PCRECEITAPRODUCAO            MODOFAZER          CLOB                                Modo de fazer            OPERACIONAL                        NaN
PCRECEITAPRODUCAO           DTCADASTRO          DATE                             Data de cadastro            OPERACIONAL                        NaN
PCRECEITAPRODUCAO          DTALTERACAO          DATE                            Data de alteração            OPERACIONAL                        NaN
PCRECEITAPRODUCAO        CODUSUARIOINC   NUMBER(8,0)                Código do usuário que incluiu            OPERACIONAL                        NaN
PCRECEITAPRODUCAO        CODUSUARIOALT   NUMBER(8,0)                Código do usuário que alterou            OPERACIONAL                        NaN
PCRECEITAPRODUCAO     PRODUZIRNASABADO   VARCHAR2(1)                             Produz no sábado            OPERACIONAL                        NaN
PCRECEITAPRODUCAO    PERDAEMPERCENTUAL  NUMBER(18,6)              Percentual de perda na produção            OPERACIONAL                        NaN
PCRECEITAPRODUCAO              CUSTOKG  NUMBER(22,6)                                 Custo por kg            OPERACIONAL                        NaN
PCRECEITAPRODUCAO       CUSTOEMBALAGEM  NUMBER(22,6)                           Custo da embalagem            OPERACIONAL                        NaN
PCRECEITAPRODUCAO     CODSETORPRODUCAO   VARCHAR2(5)                  Código do setor de produção            OPERACIONAL                        NaN
PCRECEITAPRODUCAO              TOTALKG  NUMBER(22,6)                           Valor total por kg            OPERACIONAL                        NaN
PCRECEITAPRODUCAO     ESTOQUEPRODUTOKG   VARCHAR2(1)  Estoque do produto por KG senão por Unidade            OPERACIONAL                        NaN
PCRECEITAPRODUCAO PERCVARIACAOPRODUCAO  NUMBER(22,6) Percentual de variação de produção permitida            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*