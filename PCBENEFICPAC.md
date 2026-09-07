# 📊 Tabela: PCBENEFICPAC

### Estrutura de Colunas e Restrições

      Tabela                       Coluna  Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICPAC                       NUMPED  NUMBER(10,0)                       Número do pedido de produto acabado    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICPAC                    CODFILIAL   VARCHAR2(2)                                          Código da filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCBENEFICPAC                    CODFORNEC  NUMBER(10,0)                                      Código do fornecedor CHAVE ESTRANGEIRA (FK)                   PCFORNEC
PCBENEFICPAC                   CODPARCELA   NUMBER(6,0)                                    Código do parcelamento CHAVE ESTRANGEIRA (FK)                PCPARCELASC
PCBENEFICPAC                   FINALIZADO   VARCHAR2(1)                      Indica se o pedido já foi finalizado            OPERACIONAL                        NaN
PCBENEFICPAC                     TIPOVENC   VARCHAR2(1)                               Indica o tipo de vencimento            OPERACIONAL                        NaN
PCBENEFICPAC                      DIABASE   NUMBER(2,0)                              Dia base para o parcelamento            OPERACIONAL                        NaN
PCBENEFICPAC                      DTFATUR          DATE                                       Data de faturamento            OPERACIONAL                        NaN
PCBENEFICPAC                    DTEMISSAO          DATE                                           Data de emissão            OPERACIONAL                        NaN
PCBENEFICPAC                   VLDESCONTO  NUMBER(18,6)                                   Valor total do desconto            OPERACIONAL                        NaN
PCBENEFICPAC                    VLSUFRAMA  NUMBER(18,6)                                    Valor total da suframa            OPERACIONAL                        NaN
PCBENEFICPAC                      VLFRETE  NUMBER(18,6)                                      Valor total do frete            OPERACIONAL                        NaN
PCBENEFICPAC                        VLIPI  NUMBER(18,6)                                        Valor total do ipi            OPERACIONAL                        NaN
PCBENEFICPAC                     VLSEGURO  NUMBER(18,6)                                     Valor total do seguro            OPERACIONAL                        NaN
PCBENEFICPAC               VLDESPDENTRONF  NUMBER(18,6)                     Valor total das despesas dentro da nf            OPERACIONAL                        NaN
PCBENEFICPAC                         VLST  NUMBER(18,6)                                         Valor total do ST            OPERACIONAL                        NaN
PCBENEFICPAC                      VLTOTAL  NUMBER(18,6)                                     Valor total do pedido            OPERACIONAL                        NaN
PCBENEFICPAC                   OBSERVACAO VARCHAR2(200)                   Observação do pedido de produto acabado            OPERACIONAL                        NaN
PCBENEFICPAC                   CODUSUARIO  NUMBER(10,0)                     Matricula do usuário que fez o pedido            OPERACIONAL                        NaN
PCBENEFICPAC    UTILIZAOUTDESPCALCSUFRAMA   VARCHAR2(1) Indica se utiliza outras despesas para calcular o suframa            OPERACIONAL                        NaN
PCBENEFICPAC     CALCSUFRAMASOBREPLIQUIDO   VARCHAR2(1)         Indica se calcula o suframa sobre o preço liquido            OPERACIONAL                        NaN
PCBENEFICPAC               CALCIPICOMDESC   VARCHAR2(1)            Indica se calcula o ipi com desconto comercial            OPERACIONAL                        NaN
PCBENEFICPAC            CALCIPICOMFRETENF   VARCHAR2(1)                         Indica se calcula o ipi com frete            OPERACIONAL                        NaN
PCBENEFICPAC     UTILIZAOUTRASDESPCALCIPI   VARCHAR2(1)                Indica se cacula o ipi com outras despesas            OPERACIONAL                        NaN
PCBENEFICPAC           CALCULARIPIPESOLIQ   VARCHAR2(1)             Indica se calcula o ipi sobre o preço liquido            OPERACIONAL                        NaN
PCBENEFICPAC           UTILIZAIPICALCICMS   VARCHAR2(1)                            Indica se calcula icms com ipi            OPERACIONAL                        NaN
PCBENEFICPAC          UTILIZADESCCALCICMS   VARCHAR2(1)             Indica se calcula icms com desconto comercial            OPERACIONAL                        NaN
PCBENEFICPAC         UTILIZAFRETECALCICMS   VARCHAR2(1)                          Indica se calcula icms com frete            OPERACIONAL                        NaN
PCBENEFICPAC    UTILIZAOUTRASDESPCALCICMS   VARCHAR2(1)                Indica se calcula icms com outros despesas            OPERACIONAL                        NaN
PCBENEFICPAC    DEDUZIRSUFRAMACALCCREDICM   VARCHAR2(1)                        Indica se calcula icms com suframa            OPERACIONAL                        NaN
PCBENEFICPAC       CONSIPICALCBASECREPRES   VARCHAR2(1)               Indica se calcula credito presumido com ipi            OPERACIONAL                        NaN
PCBENEFICPAC      DEDFRETECIFCREDPRESICMS   VARCHAR2(1)             Indica se calcula credito presumido com frete            OPERACIONAL                        NaN
PCBENEFICPAC       USAPERCICMSNAALIQEXTST   VARCHAR2(1)                Indica se calcula st2 com alíquota de icms            OPERACIONAL                        NaN
PCBENEFICPAC            UTILIZADESCCALCST   VARCHAR2(1)            Indica se calcula st nf com desconto comercial            OPERACIONAL                        NaN
PCBENEFICPAC      DEDUZIRSUFRAMABCSTALIQ1   VARCHAR2(1)                         Indica se calcula st1 com suframa            OPERACIONAL                        NaN
PCBENEFICPAC        DEDUZIRSUFRAMAALIQEXT   VARCHAR2(1)                         Indica se calcula st2 com suframa            OPERACIONAL                        NaN
PCBENEFICPAC            CONSIPICALCBASEST   VARCHAR2(1)                              Indica se calcula st com ipi            OPERACIONAL                        NaN
PCBENEFICPAC            CALCSTGUIAALIQEXT   VARCHAR2(1)            Indica se calcula st guia com alíquota externa            OPERACIONAL                        NaN
PCBENEFICPAC       UTILIZAOUTDESPNFBASEST   VARCHAR2(1)                  Indica se calcula st com outras despesas            OPERACIONAL                        NaN
PCBENEFICPAC                     ISENTOST   VARCHAR2(1)                     Indica se o fornecedor é isento de st            OPERACIONAL                        NaN
PCBENEFICPAC    DEDUZIRSUFRAMACALCCREDPIS   VARCHAR2(1)                  Indica se calcula pis/cofins com suframa            OPERACIONAL                        NaN
PCBENEFICPAC            CONSSTNFPISCOFINS   VARCHAR2(1)                    Indica se calcula pis/cofins com st nf            OPERACIONAL                        NaN
PCBENEFICPAC       CALCULAPISCOFINSCOMIPI   VARCHAR2(1)                      Indica se calcula pis/cofins com ipi            OPERACIONAL                        NaN
PCBENEFICPAC USAOUTRASDESPSEGUROPISCOFINS   VARCHAR2(1) Indica se calcula pis/cofins com seguro e outras despesas            OPERACIONAL                        NaN
PCBENEFICPAC     CALCCREDICMSBASEREDUZIDA   VARCHAR2(1)               Utiliza crédito de ICMS sobre base reduzida            OPERACIONAL                        NaN
PCBENEFICPAC     DEDUZIRICMSBASEPISCOFINS   VARCHAR2(1)    Deduzir valor do ICMS da base de cálculo do PIS/COFINS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*