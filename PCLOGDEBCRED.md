# 📊 Tabela: PCLOGDEBCRED

### Estrutura de Colunas e Restrições

      Tabela                         Coluna  Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDEBCRED                           DATA          DATE                                                   Data o lançamento            OPERACIONAL                        NaN
PCLOGDEBCRED                     DTBLOQUEIO          DATE                                                    Data do bloqueio            OPERACIONAL                        NaN
PCLOGDEBCRED                    DTBLOQCOMIS          DATE                                           Data bloqueio da comissão            OPERACIONAL                        NaN
PCLOGDEBCRED                        CODFUNC   NUMBER(8,0)                          Codigo do funcionário que fez o lançamento            OPERACIONAL                        NaN
PCLOGDEBCRED                         CODIGO   NUMBER(8,0)                                     Código do gerente ou supervisor            OPERACIONAL                        NaN
PCLOGDEBCRED                         ROTINA   NUMBER(6,0)                                                    Código da rotina            OPERACIONAL                        NaN
PCLOGDEBCRED                     VLCORRENTE  NUMBER(22,6)                                             Valor do conta corrente            OPERACIONAL                        NaN
PCLOGDEBCRED                      VLLIMCRED  NUMBER(22,6)                                          Valor do limite de crédito            OPERACIONAL                        NaN
PCLOGDEBCRED                  VLCORRENTEANT  NUMBER(22,6)                                    Valor do conta corrente anterior            OPERACIONAL                        NaN
PCLOGDEBCRED                   VLLIMCREDANT  NUMBER(22,6)                                 Valor do limite de crédito anterior            OPERACIONAL                        NaN
PCLOGDEBCRED                      HISTORICO VARCHAR2(300)                                             Histórico do lançamento            OPERACIONAL                        NaN
PCLOGDEBCRED                         NUMPED  NUMBER(10,0)                                           Número do pedido de venda            OPERACIONAL                        NaN
PCLOGDEBCRED                        POSICAO   VARCHAR2(1)                                          Posição do pedido de venda            OPERACIONAL                        NaN
PCLOGDEBCRED                  NUMTRANSVENDA  NUMBER(10,0)                                        Número da transação de venda            OPERACIONAL                        NaN
PCLOGDEBCRED                    NUMTRANSENT  NUMBER(10,0)                                      Número de transação de entrada            OPERACIONAL                        NaN
PCLOGDEBCRED                        CODPROD   NUMBER(6,0)                                                   Código do produto            OPERACIONAL                        NaN
PCLOGDEBCRED                         NUMSEQ  NUMBER(20,0)                                      Número de sequeência no pedido            OPERACIONAL                        NaN
PCLOGDEBCRED                     HISTORICO2 VARCHAR2(300)                                     Histório do motivo da lateração            OPERACIONAL                        NaN
PCLOGDEBCRED                    VLDIFERENCA  NUMBER(22,6)                   Valor da diferença entre o valor atual e anterior            OPERACIONAL                        NaN
PCLOGDEBCRED                      VLRESERVA  NUMBER(22,6)                                                    Valor da reserva            OPERACIONAL                        NaN
PCLOGDEBCRED               PERCSALDORESERVA  NUMBER(22,6)                                      Percentual do saldo da reserva            OPERACIONAL                        NaN
PCLOGDEBCRED                      CODFILIAL   VARCHAR2(2)                                                    Código da filial            OPERACIONAL                        NaN
PCLOGDEBCRED                         PVENDA  NUMBER(22,6)                                                      Preço de venda            OPERACIONAL                        NaN
PCLOGDEBCRED                             ST  NUMBER(22,6)                                                         Valor do ST            OPERACIONAL                        NaN
PCLOGDEBCRED                       PBASERCA  NUMBER(22,6)               Preço do PBASE rca, usando para comparação com pVENDA            OPERACIONAL                        NaN
PCLOGDEBCRED                     STPBASERCA  NUMBER(22,6)                                             ST do preço base do RCA            OPERACIONAL                        NaN
PCLOGDEBCRED                        PTABELA  NUMBER(22,6)                                                        Preço tabela            OPERACIONAL                        NaN
PCLOGDEBCRED                      STPTABELA  NUMBER(22,6)                                               ST do preço de tabela            OPERACIONAL                        NaN
PCLOGDEBCRED                         BONIFC  NUMBER(22,6)                                       Indica se o item o bonificado            OPERACIONAL                        NaN
PCLOGDEBCRED                             QT  NUMBER(22,6)                                               Quantidade do prdouto            OPERACIONAL                        NaN
PCLOGDEBCRED               USADEBCREDBRINDE   VARCHAR2(1)                                         Usa débito e crédito brinde            OPERACIONAL                        NaN
PCLOGDEBCRED      MOVIMENTACAOCONTACORRENTE   VARCHAR2(1)                                            Movimenta conta corrente            OPERACIONAL                        NaN
PCLOGDEBCRED        AUTORIZEDICAOITEMPEDMED   VARCHAR2(1)                   Autoriza edição no item do pedido do medicamentos            OPERACIONAL                        NaN
PCLOGDEBCRED  MOTIVOAUTORIZEDICAOITEMPEDMED VARCHAR2(200)       Movito da autorização da edição do item de pedido medicamento            OPERACIONAL                        NaN
PCLOGDEBCRED CODFUNCAUTORIZEDICAOITEMPEDMED   NUMBER(8,0)       Codigo do funcionário que editou o item do pedido medicamento            OPERACIONAL                        NaN
PCLOGDEBCRED              TIPOCONTACORRENTE   VARCHAR2(1) Tipo de conta corrente a ser movimentado: RCA,Gerente ou Supervisor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*