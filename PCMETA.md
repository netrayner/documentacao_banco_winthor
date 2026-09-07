# 📊 Tabela: PCMETA

### Estrutura de Colunas e Restrições

Tabela                 Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETA                 CODIGO  NUMBER(8,0)                                                             NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMETA              CODFILIAL  VARCHAR2(2)                                                             NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMETA                CODUSUR  NUMBER(4,0)                                                             NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMETA               TIPOMETA  VARCHAR2(2)                                                             NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMETA                   DATA         DATE                                                             NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMETA            VLVENDAPREV NUMBER(12,2)                                                             NaN            OPERACIONAL                        NaN
PCMETA            QTVENDAPREV NUMBER(20,6)                                                             NaN            OPERACIONAL                        NaN
PCMETA             QTPESOPREV NUMBER(12,2)                                                             NaN            OPERACIONAL                        NaN
PCMETA                MIXPREV NUMBER(10,4)                                                             NaN            OPERACIONAL                        NaN
PCMETA             CLIPOSPREV NUMBER(10,4)                                                             NaN            OPERACIONAL                        NaN
PCMETA             VOLUMEPREV NUMBER(20,8)                                                             NaN            OPERACIONAL                        NaN
PCMETA            CODPROMOCAO  NUMBER(6,0)                                                             NaN            OPERACIONAL                        NaN
PCMETA             CLICADPREV NUMBER(10,4)                          Indica a meta de clientes cadastrados.            OPERACIONAL                        NaN
PCMETA             MARGEMPREV  NUMBER(8,4)                                 Indica o percentual lucro meta.            OPERACIONAL                        NaN
PCMETA        EFETIVIDADEPREV NUMBER(12,6)                                     Indica meta de efetividade.            OPERACIONAL                        NaN
PCMETA    EFETIVIDADEZEROPREV NUMBER(12,6)         Indica meta sem efetividade (resto ou desconto de meta.            OPERACIONAL                        NaN
PCMETA    EFETIVIDADESEM1PREV NUMBER(12,6)                      Indica a meta de efetividade com 1 semana.            OPERACIONAL                        NaN
PCMETA    EFETIVIDADESEM2PREV NUMBER(12,6)                      Indica a efetividade 2 semanas(quinzenal).            OPERACIONAL                        NaN
PCMETA    EFETIVIDADESEM3PREV NUMBER(12,6)                     Indica a meta de efetividade com 3 semanas.            OPERACIONAL                        NaN
PCMETA    EFETIVIDADESEM4PREV NUMBER(12,6)                        Indica a efetividade 4 semanas(semanal).            OPERACIONAL                        NaN
PCMETA            PEDIDOSPREV  NUMBER(8,4)                                   Indica a meta de pedidos/dia.            OPERACIONAL                        NaN
PCMETA           QTMEDIAITENS  NUMBER(8,4)                     Indica a meta de média de itens por pedido.            OPERACIONAL                        NaN
PCMETA            VLMEDIOITEM NUMBER(12,6)                           Indica a meta de valor médio de item.            OPERACIONAL                        NaN
PCMETA          VLMEDIOPEDIDO NUMBER(12,2)                         Indica a meta de valor médio de pedido.            OPERACIONAL                        NaN
PCMETA      VLMEDIOPEDIDOSDIA NUMBER(12,2)                    Indica a meta de valor médio de pedidos/dia.            OPERACIONAL                        NaN
PCMETA        DESCVLVENDAPREV  NUMBER(7,4)                  Indica o % desconto na meta de valor de venda.            OPERACIONAL                        NaN
PCMETA           QTMETROSPREV NUMBER(12,6)                        Indica a quantidade de metros previstos.            OPERACIONAL                        NaN
PCMETA         PERVLDEVOLPREV  NUMBER(8,4)                      Indica o percentual de devolução esperado.            OPERACIONAL                        NaN
PCMETA         PERINADIMPPREV  NUMBER(8,4)                           Indica o percentual de inadimplência.            OPERACIONAL                        NaN
PCMETA          VLMINVENDAPOS NUMBER(10,2)                                  Indica o valor mínimode venda.            OPERACIONAL                        NaN
PCMETA         PRAZOMEDIOPREV  NUMBER(4,0)                                  Indica o prazo médio esperado.            OPERACIONAL                        NaN
PCMETA         PRECOMEDIOPREV NUMBER(18,6)                                  Indica o preço médio esperado.            OPERACIONAL                        NaN
PCMETA       PRECOMEDIOKGPREV NUMBER(18,6)                               Indica o preço médio/Kg esperado.            OPERACIONAL                        NaN
PCMETA      QTVENDAINVESTPREV NUMBER(20,6)                      Indica a meta de quant. venda por cliente.            OPERACIONAL                        NaN
PCMETA      VLVENDAINVESTPREV NUMBER(14,2)          Indica a meta de valor venda por cliente investimento.            OPERACIONAL                        NaN
PCMETA        QTVENDAFOCOPREV NUMBER(20,6)                 Indica a meta de quant. venda por cliente foco.            OPERACIONAL                        NaN
PCMETA        VLVENDAFOCOPREV NUMBER(14,2)                  Indica a meta de valor venda por cliente foco.            OPERACIONAL                        NaN
PCMETA         PERQTDEVOLPREV  NUMBER(8,4)               Indica o percentual de quant. devolvida esperado.            OPERACIONAL                        NaN
PCMETA      MEDIAITENSCLIPREV  NUMBER(6,2)                       Indica a média de itens/cliente esperada.            OPERACIONAL                        NaN
PCMETA      EFETIVIDADEDIARIA NUMBER(12,6)                  Indica a freqüência de visita diária esperada.            OPERACIONAL                        NaN
PCMETA  EFETIVIDADEBISSEMANAL NUMBER(12,6)              Indica a freqüência de visita bissemanal esperada.            OPERACIONAL                        NaN
PCMETA               SEGURADA  VARCHAR2(1)                                          Indica carga segurada.            OPERACIONAL                        NaN
PCMETA          PERCLIPOSPREV  NUMBER(6,2)                             Percentual de clientes positivados.            OPERACIONAL                        NaN
PCMETA       QTDCLIENTESATIVO NUMBER(12,4)                    Qtd. De clientes ativos na data da inclusão.            OPERACIONAL                        NaN
PCMETA AMORTIZACAOEFETIVIDADE NUMBER(12,6) Percentual lançado para amortizar carteira efetividade semanal.            OPERACIONAL                        NaN
PCMETA      PERVLDESCONTOPREV  NUMBER(8,4)                                Percentual de desconto previsto.            OPERACIONAL                        NaN
PCMETA           MIXMEDIOPREV NUMBER(10,4)                               Quantidade do mix medio previsto.            OPERACIONAL                        NaN
PCMETA             ROTINALANC  NUMBER(6,0)                                              Rotina lançamento.            OPERACIONAL                        NaN
PCMETA                CODIGO2  NUMBER(8,0)                    Indica o segundo código da meta relacionada.    CHAVE PRIMÁRIA (PK)                        NaN
PCMETA             PERCRATEIO  NUMBER(8,4)                                 Percentual de rateio entre RCA.            OPERACIONAL                        NaN
PCMETA               CODMETAC  NUMBER(8,0)                       Indica o valor da chave da tabela PCMETAC            OPERACIONAL                        NaN
PCMETA    EFETIVIDADESEM5PREV NUMBER(12,6)                        Indica a efetividade 5 semanas(semanal).            OPERACIONAL                        NaN
PCMETA               LITRAGEM NUMBER(18,6)                               Indica a meta de litragem vendida            OPERACIONAL                        NaN
PCMETA             DTMXSALTER         DATE                                                             NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*