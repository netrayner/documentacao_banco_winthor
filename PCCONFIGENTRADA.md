# 📊 Tabela: PCCONFIGENTRADA

### Estrutura de Colunas e Restrições

         Tabela                   Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGENTRADA        USAACRESCIMOCUSTO  VARCHAR2(1)                         Usa acréscimo custo            OPERACIONAL                        NaN
PCCONFIGENTRADA     USADESCONTOCOMERCIAL  VARCHAR2(1)                      Usa desconto comercial            OPERACIONAL                        NaN
PCCONFIGENTRADA    USADESCONTOFINANCEIRO  VARCHAR2(1)                     Usa Desconto financeiro            OPERACIONAL                        NaN
PCCONFIGENTRADA USADESCONTOPRODUTORRURAL  VARCHAR2(1)                 Usa desconto produtor rural            OPERACIONAL                        NaN
PCCONFIGENTRADA     USADESPESAFINANCEIRA  VARCHAR2(1)                     Usa despesas financeira            OPERACIONAL                        NaN
PCCONFIGENTRADA   USADIFERENCIALALIQUOTA  VARCHAR2(1)                 Usa diferencial de alíquota            OPERACIONAL                        NaN
PCCONFIGENTRADA              USAFRETECIF  VARCHAR2(1)                               Usa Frete CIF            OPERACIONAL                        NaN
PCCONFIGENTRADA              USAFRETEFOB  VARCHAR2(1)                               Usa Frete FOB            OPERACIONAL                        NaN
PCCONFIGENTRADA                  USAICMS  VARCHAR2(1)                                    Usa ICMS            OPERACIONAL                        NaN
PCCONFIGENTRADA        USAICMSANTECIPADO  VARCHAR2(1)                         Usa ICMS antecipado            OPERACIONAL                        NaN
PCCONFIGENTRADA         USAICMSPRESUMIDO  VARCHAR2(1)                  Usa ICMS crédito presumido            OPERACIONAL                        NaN
PCCONFIGENTRADA                   USAIPI  VARCHAR2(1)                                     Usa IPI            OPERACIONAL                        NaN
PCCONFIGENTRADA     USAOUTRASDESPESAGUIA  VARCHAR2(1)     Usa outras despesas - fora da NF / Guia            OPERACIONAL                        NaN
PCCONFIGENTRADA       USAOUTRASDESPESANF  VARCHAR2(1)          Usa outras despesas - dentro da NF            OPERACIONAL                        NaN
PCCONFIGENTRADA             USAPISCOFINS  VARCHAR2(1)                              Usa PIS/COFINS            OPERACIONAL                        NaN
PCCONFIGENTRADA      USAPRAZOENTREGAITEM  VARCHAR2(1)               Usa prazo de entrega por item            OPERACIONAL                        NaN
PCCONFIGENTRADA                USASEGURO  VARCHAR2(1)                                  Usa seguro            OPERACIONAL                        NaN
PCCONFIGENTRADA                USASTGUIA  VARCHAR2(1)                  Usa ST - fora da NF / Guia            OPERACIONAL                        NaN
PCCONFIGENTRADA                  USASTNF  VARCHAR2(1)                       Usa ST - dentro da NF            OPERACIONAL                        NaN
PCCONFIGENTRADA               USASUFRAMA  VARCHAR2(1)                                 Usa SUFRAMA            OPERACIONAL                        NaN
PCCONFIGENTRADA         USAVERBADINHEIRO  VARCHAR2(1)                        Usa verba - dinheiro            OPERACIONAL                        NaN
PCCONFIGENTRADA       USAVERBAMERCADORIA  VARCHAR2(1)                      Usa verba - mercadoria            OPERACIONAL                        NaN
PCCONFIGENTRADA           USAVERBAOUTRAS  VARCHAR2(1)                          Usa verba - outras            OPERACIONAL                        NaN
PCCONFIGENTRADA            USAIMPORTACAO  VARCHAR2(1) Usa tributação de importação de mercadoria.            OPERACIONAL                        NaN
PCCONFIGENTRADA            USACONSIGNADO  VARCHAR2(1)         Usa compra de produtos consignados.            OPERACIONAL                        NaN
PCCONFIGENTRADA           USAMEDICAMENTO  VARCHAR2(1) Usa tributação de importação de mercadoria.            OPERACIONAL                        NaN
PCCONFIGENTRADA      USAMOEDAESTRANGEIRA  VARCHAR2(1)         Usa compra de produtos consignados.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*