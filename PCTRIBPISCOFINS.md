# 📊 Tabela: PCTRIBPISCOFINS

### Estrutura de Colunas e Restrições

         Tabela                        Coluna  Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBPISCOFINS              CODTRIBPISCOFINS   NUMBER(4,0)                  Código da figura tributária para cálculo do PIS/COFINS    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBPISCOFINS        DESCRICAOTRIBPISCOFINS  VARCHAR2(40)                                         Descrição Tributação PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINS            CONSIDERAVLFIXOLIT   VARCHAR2(1)                                         Considera Valor Fixo (Litragem)            OPERACIONAL                        NaN
PCTRIBPISCOFINS   UTILIZAPERCPISCOFINSDIFCONS   VARCHAR2(1)         Utiliza percentuais diferentes de PIS/COFINS para venda consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINS            CONSIDERAPRECOMERC   VARCHAR2(1)                                           Considera Preço da mercadoria            OPERACIONAL                        NaN
PCTRIBPISCOFINS                CONSIDERAPAUTA   VARCHAR2(1)                                                         Considera Pauta            OPERACIONAL                        NaN
PCTRIBPISCOFINS                    VLPAUTAPIS  NUMBER(18,6)                                                   Valor da Pauta do PIS            OPERACIONAL                        NaN
PCTRIBPISCOFINS                 VLPAUTACOFINS  NUMBER(18,6)                                                Valor da Pauta do COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINS                  CONSIDERAIPI   VARCHAR2(1)                                                           Considera IPI            OPERACIONAL                        NaN
PCTRIBPISCOFINS                   CONSIDERAST   VARCHAR2(1)                                                            Considera ST            OPERACIONAL                        NaN
PCTRIBPISCOFINS           CONSIDERAOUTRASDESP   VARCHAR2(1)                                               Considera Outras despesas            OPERACIONAL                        NaN
PCTRIBPISCOFINS                CONSIDERAFRETE   VARCHAR2(1)                                  Considera Frete lançado na Nota Fiscal            OPERACIONAL                        NaN
PCTRIBPISCOFINS              CONSIDERASUFRAMA   VARCHAR2(1)                                      Considera Deduzir valor do Suframa            OPERACIONAL                        NaN
PCTRIBPISCOFINS                RETERPISCOFINS   VARCHAR2(1)                    Valor a ser retido do preço da mercadoria (Deduzido)            OPERACIONAL                        NaN
PCTRIBPISCOFINS                       PERCPIS   NUMBER(8,4)                                                          Percentual PIS            OPERACIONAL                        NaN
PCTRIBPISCOFINS                    PERCCOFINS   NUMBER(8,4)                                                       Percentual COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINS                     SITTRIBUT   NUMBER(6,0)                                              Código Situação Tributária            OPERACIONAL                        NaN
PCTRIBPISCOFINS                 PERCPISCALCDI   NUMBER(8,4)                                          Percentual PIS para Cálculo DI            OPERACIONAL                        NaN
PCTRIBPISCOFINS              PERCCOFINSCALCDI   NUMBER(6,2)                                       Percentual COFINS para cálculo DI            OPERACIONAL                        NaN
PCTRIBPISCOFINS              BASEPISCOFINSLIT  NUMBER(18,6)                                                Base PIS/COFINS Litragem            OPERACIONAL                        NaN
PCTRIBPISCOFINS                      VLPISLIT  NUMBER(18,6)                                                      Valor PIS Litragem            OPERACIONAL                        NaN
PCTRIBPISCOFINS                   VLCOFINSLIT  NUMBER(18,6)                                                   Valor COFINS Litragem            OPERACIONAL                        NaN
PCTRIBPISCOFINS                 MENSAGEMGERAL VARCHAR2(200)                                          Mensagem de Informações Gerais            OPERACIONAL                        NaN
PCTRIBPISCOFINS                PERCPISCONSUMO   NUMBER(8,4)                                             Percentual PIS para consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINS             PERCCOFINSCONSUMO   NUMBER(8,4)                                          Percentual COFINS para consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINS              SITTRIBUTCONSUMO   NUMBER(6,0)                                                 Código CST para consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINS               MENSAGEMCONSUMO VARCHAR2(200)                                                   Mensagem para consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINS          CONSIDERADIFALIQUOTA   VARCHAR2(1)                                                Considerar Dif. Alíquota            OPERACIONAL                        NaN
PCTRIBPISCOFINS                  SITTRIBUTDEV   NUMBER(3,0)                                  Cod. Situação Tributária do PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINS           SITTRIBUTCONSUMODEV   NUMBER(3,0)                                                  CST PIS/COFINS Consumo            OPERACIONAL                        NaN
PCTRIBPISCOFINS              CONSIDERADIFALIQ   VARCHAR2(1)                                          Considera Diferencial Alíquota            OPERACIONAL                        NaN
PCTRIBPISCOFINS      GERABASEPISCOFINSSEMALIQ   VARCHAR2(1)                                  Gera a base do PIS/COFINS sem alíquota            OPERACIONAL                        NaN
PCTRIBPISCOFINS                ALIQREDUCAOPIS  NUMBER(12,4)                                         % de Redução de Alíquota de PIS            OPERACIONAL                        NaN
PCTRIBPISCOFINS             ALIQREDUCAOCOFINS  NUMBER(12,4)                                         % de Redução Alíquota da COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINS          CONSIDERAPAUTAMINIMA   VARCHAR2(1)                                                 Considerar Pauta Minima            OPERACIONAL                        NaN
PCTRIBPISCOFINS             SITTRIBUTPAUTAMIN   NUMBER(3,0)                                      CST PIS/COFINS Saídas Pauta Mínima            OPERACIONAL                        NaN
PCTRIBPISCOFINS          SITTRIBUTDEVPAUTAMIN   NUMBER(3,0)                                        CST PIS/COFINS Dev. Pauta Mínima            OPERACIONAL                        NaN
PCTRIBPISCOFINS               IDENTIFICARTRIB VARCHAR2(130)                                     Indentificação do arquivo importado            OPERACIONAL                        NaN
PCTRIBPISCOFINS                  ZERARBCCSTST   VARCHAR2(1)                                                                     NaN            OPERACIONAL                        NaN
PCTRIBPISCOFINS               PERCREDBASCALPC  NUMBER(12,4)                                Perc. de red. base de cálculo PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINS           CODEXCTRIBPISCOFINS   NUMBER(4,0)                                         Código de exceção do PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINS      EXCLUIRICMSBASEPISCOFINS   VARCHAR2(1)                            Exclui o valor do icms da base do pis/cofins            OPERACIONAL                        NaN
PCTRIBPISCOFINS     EXCLUIRDIFALBASEPISCOFINS   VARCHAR2(1) Campo responsável por definir a exclusão do DIFAL da base do pis/cofins            OPERACIONAL                        NaN
PCTRIBPISCOFINS                    DTULTALTER          DATE                                                       Data de alteração            OPERACIONAL                        NaN
PCTRIBPISCOFINS                    DTCADASTRO          DATE                                                        Data de cadastro            OPERACIONAL                        NaN
PCTRIBPISCOFINS                     DTALTERC5  TIMESTAMP(6)                                                          Data alteração            OPERACIONAL                        NaN
PCTRIBPISCOFINS EXCLUIRICMSSTBCRBASEPISCOFINS   VARCHAR2(1)                 Define a exclução do ICMS ST BCR da base do PIS/COFIN.             OPERACIONAL                        NaN
PCTRIBPISCOFINS EXCLUIRVLICMSBCRBASEPISCOFINS   VARCHAR2(1)                    Excluir valor do ICMS BCR base cálculo do PIS/COFINS            OPERACIONAL                        NaN
PCTRIBPISCOFINS                       LC22425   VARCHAR2(1)                                      Figura sujeita a Lei Compl. 224/25            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*