# 📊 Tabela: PCBENEFICMPC

### Estrutura de Colunas e Restrições

      Tabela                       Coluna  Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICMPC                       NUMPED  NUMBER(10,0)                         Número do pedido de materia prima    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICMPC                    CODFILIAL   VARCHAR2(2)                                          Código da filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCBENEFICMPC                    CODFORNEC  NUMBER(10,0)                                      Código do fornecedor CHAVE ESTRANGEIRA (FK)                   PCFORNEC
PCBENEFICMPC                   CODPARCELA   NUMBER(6,0)                                    Código do parcelamento CHAVE ESTRANGEIRA (FK)                PCPARCELASC
PCBENEFICMPC                     CODCONTA  NUMBER(10,0)                                  Código da conta contábil CHAVE ESTRANGEIRA (FK)                    PCCONTA
PCBENEFICMPC                     TIPOVENC   VARCHAR2(1)                               Indica o tipo de vencimento            OPERACIONAL                        NaN
PCBENEFICMPC                      DIABASE   NUMBER(2,0)                              Dia base para o parcelamento            OPERACIONAL                        NaN
PCBENEFICMPC                      DTFATUR          DATE                                       Data de faturamento            OPERACIONAL                        NaN
PCBENEFICMPC                    DTEMISSAO          DATE                                           Data de emissão            OPERACIONAL                        NaN
PCBENEFICMPC                   VLDESCONTO  NUMBER(18,6)                                   Valor total do desconto            OPERACIONAL                        NaN
PCBENEFICMPC                    VLSUFRAMA  NUMBER(18,6)                                    Valor total da suframa            OPERACIONAL                        NaN
PCBENEFICMPC                      VLFRETE  NUMBER(18,6)                                      Valor total do frete            OPERACIONAL                        NaN
PCBENEFICMPC                        VLIPI  NUMBER(18,6)                                        Valor total do ipi            OPERACIONAL                        NaN
PCBENEFICMPC                     VLSEGURO  NUMBER(18,6)                                     Valor total do seguro            OPERACIONAL                        NaN
PCBENEFICMPC               VLDESPDENTRONF  NUMBER(18,6)                     Valor total das despesas dentro da nf            OPERACIONAL                        NaN
PCBENEFICMPC                         VLST  NUMBER(18,6)                                         Valor total do ST            OPERACIONAL                        NaN
PCBENEFICMPC                      VLTOTAL  NUMBER(18,6)                                     Valor total do pedido            OPERACIONAL                        NaN
PCBENEFICMPC                   OBSERVACAO VARCHAR2(200)                                                       NaN            OPERACIONAL                        NaN
PCBENEFICMPC                   CODUSUARIO  NUMBER(10,0)                     Matricula do usuário que fez o pedido            OPERACIONAL                        NaN
PCBENEFICMPC               PEDIDOFATURADO   VARCHAR2(1)                        Indica se o pedido já foi faturado            OPERACIONAL                        NaN
PCBENEFICMPC           CODUSUARIOFATURADO  NUMBER(10,0)                 Matricula do usuário que faturou o pedido            OPERACIONAL                        NaN
PCBENEFICMPC                NUMTRANSVENDA  NUMBER(10,0)                     Transação de saída do pedido faturado            OPERACIONAL                        NaN
PCBENEFICMPC    UTILIZAOUTDESPCALCSUFRAMA   VARCHAR2(1) Indica se utiliza outras despesas para calcular o suframa            OPERACIONAL                        NaN
PCBENEFICMPC     CALCSUFRAMASOBREPLIQUIDO   VARCHAR2(1)         Indica se calcula o suframa sobre o preço liquido            OPERACIONAL                        NaN
PCBENEFICMPC               CALCIPICOMDESC   VARCHAR2(1)            Indica se calcula o ipi com desconto comercial            OPERACIONAL                        NaN
PCBENEFICMPC            CALCIPICOMFRETENF   VARCHAR2(1)                         Indica se calcula o ipi com frete            OPERACIONAL                        NaN
PCBENEFICMPC     UTILIZAOUTRASDESPCALCIPI   VARCHAR2(1)                Indica se cacula o ipi com outras despesas            OPERACIONAL                        NaN
PCBENEFICMPC           CALCULARIPIPESOLIQ   VARCHAR2(1)             Indica se calcula o ipi sobre o preço liquido            OPERACIONAL                        NaN
PCBENEFICMPC           UTILIZAIPICALCICMS   VARCHAR2(1)                            Indica se calcula icms com ipi            OPERACIONAL                        NaN
PCBENEFICMPC          UTILIZADESCCALCICMS   VARCHAR2(1)             Indica se calcula icms com desconto comercial            OPERACIONAL                        NaN
PCBENEFICMPC         UTILIZAFRETECALCICMS   VARCHAR2(1)                          Indica se calcula icms com frete            OPERACIONAL                        NaN
PCBENEFICMPC    UTILIZAOUTRASDESPCALCICMS   VARCHAR2(1)                Indica se calcula icms com outros despesas            OPERACIONAL                        NaN
PCBENEFICMPC    DEDUZIRSUFRAMACALCCREDICM   VARCHAR2(1)                        Indica se calcula icms com suframa            OPERACIONAL                        NaN
PCBENEFICMPC       CONSIPICALCBASECREPRES   VARCHAR2(1)               Indica se calcula credito presumido com ipi            OPERACIONAL                        NaN
PCBENEFICMPC      DEDFRETECIFCREDPRESICMS   VARCHAR2(1)             Indica se calcula credito presumido com frete            OPERACIONAL                        NaN
PCBENEFICMPC       USAPERCICMSNAALIQEXTST   VARCHAR2(1)                Indica se calcula st2 com alíquota de icms            OPERACIONAL                        NaN
PCBENEFICMPC            UTILIZADESCCALCST   VARCHAR2(1)            Indica se calcula st nf com desconto comercial            OPERACIONAL                        NaN
PCBENEFICMPC      DEDUZIRSUFRAMABCSTALIQ1   VARCHAR2(1)                         Indica se calcula st1 com suframa            OPERACIONAL                        NaN
PCBENEFICMPC        DEDUZIRSUFRAMAALIQEXT   VARCHAR2(1)                         Indica se calcula st2 com suframa            OPERACIONAL                        NaN
PCBENEFICMPC            CONSIPICALCBASEST   VARCHAR2(1)                              Indica se calcula st com ipi            OPERACIONAL                        NaN
PCBENEFICMPC            CALCSTGUIAALIQEXT   VARCHAR2(1)            Indica se calcula st guia com alíquota externa            OPERACIONAL                        NaN
PCBENEFICMPC       UTILIZAOUTDESPNFBASEST   VARCHAR2(1)                  Indica se calcula st com outras despesas            OPERACIONAL                        NaN
PCBENEFICMPC                     ISENTOST   VARCHAR2(1)                     Indica se o fornecedor é isento de st            OPERACIONAL                        NaN
PCBENEFICMPC    DEDUZIRSUFRAMACALCCREDPIS   VARCHAR2(1)                  Indica se calcula pis/cofins com suframa            OPERACIONAL                        NaN
PCBENEFICMPC            CONSSTNFPISCOFINS   VARCHAR2(1)                    Indica se calcula pis/cofins com st nf            OPERACIONAL                        NaN
PCBENEFICMPC       CALCULAPISCOFINSCOMIPI   VARCHAR2(1)                      Indica se calcula pis/cofins com ipi            OPERACIONAL                        NaN
PCBENEFICMPC USAOUTRASDESPSEGUROPISCOFINS   VARCHAR2(1) Indica se calcula pis/cofins com seguro e outras despesas            OPERACIONAL                        NaN
PCBENEFICMPC     CALCCREDICMSBASEREDUZIDA   VARCHAR2(1)               Utiliza crédito de ICMS sobre base reduzida            OPERACIONAL                        NaN
PCBENEFICMPC     DEDUZIRICMSBASEPISCOFINS   VARCHAR2(1)    Deduzir valor do ICMS da base de cálculo do PIS/COFINS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*