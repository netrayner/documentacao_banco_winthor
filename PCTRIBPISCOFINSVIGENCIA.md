# 📊 Tabela: PCTRIBPISCOFINSVIGENCIA

### Estrutura de Colunas e Restrições

                 Tabela                        Coluna  Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBPISCOFINSVIGENCIA              CODTRIBPISCOFINS   NUMBER(4,0)                                             Código da figura tributúria    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBPISCOFINSVIGENCIA        DESCRICAOTRIBPISCOFINS  VARCHAR2(40)                                         Descrição Tributação PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                      DTINICIO          DATE                                              Data de inicio da vigência    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBPISCOFINSVIGENCIA                       DTFINAL          DATE                                               Data de final da vigência    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBPISCOFINSVIGENCIA            CONSIDERAVLFIXOLIT   VARCHAR2(1)                                         Considera Valor Fixo (Litragem)            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA   UTILIZAPERCPISCOFINSDIFCONS   VARCHAR2(1)         Utiliza percentuais diferentes de PIS/COFINS para venda consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA            CONSIDERAPRECOMERC   VARCHAR2(1)                                                         Considera Preço            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                CONSIDERAPAUTA   VARCHAR2(1)                                                         Considera Pauta            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                    VLPAUTAPIS  NUMBER(18,6)                                                   Valor da Pauta do PIS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                 VLPAUTACOFINS  NUMBER(18,6)                                                Valor da Pauta do COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                  CONSIDERAIPI   VARCHAR2(1)                                                           Considera IPI            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                   CONSIDERAST   VARCHAR2(1)                                                            Considera ST            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA           CONSIDERAOUTRASDESP   VARCHAR2(1)                                               Considera Outras despesas            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                CONSIDERAFRETE   VARCHAR2(1)                                  Considera Frete lançado na Nota Fiscal            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA              CONSIDERASUFRAMA   VARCHAR2(1)                                      Considera Deduzir valor do Suframa            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                RETERPISCOFINS   VARCHAR2(1)                    Valor a ser retido do preço da mercadoria (Deduzido)            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                       PERCPIS   NUMBER(8,4)                                                          Percentual PIS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                    PERCCOFINS   NUMBER(8,4)                                                       Percentual COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                     SITTRIBUT   NUMBER(6,0)                                              Código Situação Tributúria            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                 PERCPISCALCDI   NUMBER(8,4)                                          Percentual PIS para Cálculo DI            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA              PERCCOFINSCALCDI   NUMBER(6,2)                                       Percentual COFINS para cálculo DI            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA              BASEPISCOFINSLIT  NUMBER(18,6)                                                Base PIS/COFINS Litragem            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                      VLPISLIT  NUMBER(18,6)                                                      Valor PIS Litragem            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                   VLCOFINSLIT  NUMBER(18,6)                                                   Valor COFINS Litragem            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                 MENSAGEMGERAL VARCHAR2(200)                                          Mensagem de Informações Gerais            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                PERCPISCONSUMO   NUMBER(8,4)                                             Percentual PIS para consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA             PERCCOFINSCONSUMO   NUMBER(8,4)                                          Percentual COFINS para consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA              SITTRIBUTCONSUMO   NUMBER(6,0)                                                 Código CST para consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA               MENSAGEMCONSUMO VARCHAR2(200)                                                   Mensagem para consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA          CONSIDERADIFALIQUOTA   VARCHAR2(1)                                                Considerar Dif. Alíquota            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                  SITTRIBUTDEV   NUMBER(3,0)                                   Cod. Situção Tributária do PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA           SITTRIBUTCONSUMODEV   NUMBER(3,0)                                                  CST PIS/COFINS Consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA              CONSIDERADIFALIQ   VARCHAR2(1)                                          Considera Diferencial Alíquota            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA      GERABASEPISCOFINSSEMALIQ   VARCHAR2(1)                                  Gera a base do PIS/COFINS sem alíquota            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                ALIQREDUCAOPIS  NUMBER(12,4)                                         % de Redução de Alíquota de PIS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA             ALIQREDUCAOCOFINS  NUMBER(12,4)                                         % de Redução Alíquota da COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA          CONSIDERAPAUTAMINIMA   VARCHAR2(1)                                                 Considerar Pauta Minima            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA             SITTRIBUTPAUTAMIN   NUMBER(3,0)                                      CST PIS/COFINS Saídas Pauta Mínima            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA          SITTRIBUTDEVPAUTAMIN   NUMBER(3,0)                                        CST PIS/COFINS Dev. Pauta Mínima            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                  ZERARBCCSTST   VARCHAR2(1)                                                                     NaN            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA               PERCREDBASCALPC  NUMBER(12,4)                                Perc. de red. base de cálculo PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA           CODEXCTRIBPISCOFINS   NUMBER(4,0)                                         Código de exceção do PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA      EXCLUIRICMSBASEPISCOFINS   VARCHAR2(1)                            Exclui o valor do icms da base do pis/cofins            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA     EXCLUIRDIFALBASEPISCOFINS   VARCHAR2(1) Campo responsável por definir a exclusão do DIFAL da base do pis/cofins            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA EXCLUIRICMSSTBCRBASEPISCOFINS   VARCHAR2(1)                  Define a exclução do ICMS ST BCR da base do PIS/COFIN.            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA EXCLUIRVLICMSBCRBASEPISCOFINS   VARCHAR2(1)                    Excluir valor do ICMS BCR base cálculo do PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINSVIGENCIA                       LC22425   VARCHAR2(1)                                      Figura sujeita a Lei Compl. 224/25            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*