# 📊 Tabela: PCLOGMONTAGEMCARGA

### Estrutura de Colunas e Restrições

            Tabela         Coluna  Tipo/Tamanho                                                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGMONTAGEMCARGA    NUMCARATUAL  NUMBER(10,0)                                                          Número do carregamento atual em que o produto do pedido está vinculado.            OPERACIONAL                        NaN
PCLOGMONTAGEMCARGA NUMCARANTERIOR  NUMBER(10,0)                                                     Número do carregamento anterior em que o produto do pedido estava vinculado.            OPERACIONAL                        NaN
PCLOGMONTAGEMCARGA         NUMPED  NUMBER(10,0)                                                                           Número do pedido do produto vinculado ao carregamento.            OPERACIONAL                        NaN
PCLOGMONTAGEMCARGA        CODPROD   NUMBER(6,0)                                                                            Código do produto que está vinculado ao carregamento.            OPERACIONAL                        NaN
PCLOGMONTAGEMCARGA        CODFUNC   NUMBER(8,0)                                                    Código do funcionário que efetuou a montagem ou a manutenção no carregamento.            OPERACIONAL                        NaN
PCLOGMONTAGEMCARGA         STATUS   VARCHAR2(1) Status do produto no carregamento, podendo assumir três possiveis valor, "M" para Montado, "I" para Incluso e "R" para retirado.            OPERACIONAL                        NaN
PCLOGMONTAGEMCARGA           DATA          DATE                                                                 Data em que o carregamento foi montado ou que sofreu manutenção.            OPERACIONAL                        NaN
PCLOGMONTAGEMCARGA             QT  NUMBER(20,6)                                                                                  Quantidade do item no pedido e no carregamento.            OPERACIONAL                        NaN
PCLOGMONTAGEMCARGA     OBSERVACAO VARCHAR2(200)                                                                                                       Observação do carregamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*