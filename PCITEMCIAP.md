# 📊 Tabela: PCITEMCIAP

### Estrutura de Colunas e Restrições

    Tabela               Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMCIAP              CODPROD   NUMBER(6,0)                                 Código Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCIAP               NUMPED  NUMBER(10,0)                               Numero do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCIAP               NUMSEQ   NUMBER(6,0)                                     Sequencial    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCIAP              PCOMPRA  NUMBER(18,6)                                Preço de compra            OPERACIONAL                        NaN
PCITEMCIAP             QTPEDIDA  NUMBER(20,6)                          Qtde pedida de compra            OPERACIONAL                        NaN
PCITEMCIAP           QTENTREGUE  NUMBER(20,6)                                  Qtde entregue            OPERACIONAL                        NaN
PCITEMCIAP             PERCDESC  NUMBER(12,4)               Percentual de desconto comercial            OPERACIONAL                        NaN
PCITEMCIAP           VLDESCONTO  NUMBER(18,6)                    Valor do desconto comercial            OPERACIONAL                        NaN
PCITEMCIAP            PERCDESC1  NUMBER(12,4)             Percentual de desconto comercial 1            OPERACIONAL                        NaN
PCITEMCIAP            PERCDESC2  NUMBER(12,4)             Percentual de desconto comercial 2            OPERACIONAL                        NaN
PCITEMCIAP            PERCDESC3  NUMBER(12,4)             Percentual de desconto comercial 3            OPERACIONAL                        NaN
PCITEMCIAP            PERCDESC4  NUMBER(12,4)             Percentual de desconto comercial 4            OPERACIONAL                        NaN
PCITEMCIAP            PERCDESC5  NUMBER(12,4)             Percentual de desconto comercial 5            OPERACIONAL                        NaN
PCITEMCIAP            PERCDESC6  NUMBER(12,4)             Percentual de desconto comercial 6            OPERACIONAL                        NaN
PCITEMCIAP            PERCDESC7  NUMBER(12,4)             Percentual de desconto comercial 7            OPERACIONAL                        NaN
PCITEMCIAP            PERCDESC8  NUMBER(12,4)             Percentual de desconto comercial 8            OPERACIONAL                        NaN
PCITEMCIAP            PERCDESC9  NUMBER(12,4)             Percentual de desconto comercial 9            OPERACIONAL                        NaN
PCITEMCIAP           PERCDESC10  NUMBER(12,4)            Percentual de desconto comercial 10            OPERACIONAL                        NaN
PCITEMCIAP          PERCSUFRAMA  NUMBER(12,4)                          Percentual de SUFRAMA            OPERACIONAL                        NaN
PCITEMCIAP            VLSUFRAMA  NUMBER(18,6)                               Valor de SUFRAMA            OPERACIONAL                        NaN
PCITEMCIAP             PLIQUIDO  NUMBER(18,6)                        Preço líquido de compra            OPERACIONAL                        NaN
PCITEMCIAP            PERCFRETE  NUMBER(12,4)                        Percentual de Frete CIF            OPERACIONAL                        NaN
PCITEMCIAP              VLFRETE  NUMBER(18,6)                             Valor de Frete CIF            OPERACIONAL                        NaN
PCITEMCIAP           PERCSEGURO  NUMBER(12,4)                              Percentual Seguro            OPERACIONAL                        NaN
PCITEMCIAP             VLSEGURO  NUMBER(18,6)                                Valor do Seguro            OPERACIONAL                        NaN
PCITEMCIAP     PERCDESPDENTRONF  NUMBER(12,4)             Percentual de despesa dentro da NF            OPERACIONAL                        NaN
PCITEMCIAP       VLDESPDENTRONF  NUMBER(18,6)                  Valor de despesa dentro da NF            OPERACIONAL                        NaN
PCITEMCIAP           VLPAUTAIPI  NUMBER(18,6)               Valor de Pauta p/ Calc.Base IPI.            OPERACIONAL                        NaN
PCITEMCIAP               PERIPI  NUMBER(12,4)                              Percentual de IPI            OPERACIONAL                        NaN
PCITEMCIAP                VLIPI  NUMBER(18,6)                                   Valor de IPI            OPERACIONAL                        NaN
PCITEMCIAP              PERCIVA  NUMBER(12,4)                          Índice Valor Agregado            OPERACIONAL                        NaN
PCITEMCIAP           REDBASEIVA  NUMBER(18,6)                    Percentual redução base IVA            OPERACIONAL                        NaN
PCITEMCIAP              VLPAUTA  NUMBER(18,6)                Valor de Pauta p/ Calc.Base ST.            OPERACIONAL                        NaN
PCITEMCIAP      VLADICIONALBCST  NUMBER(18,6)                 Valor adicional p/Calc.Base ST            OPERACIONAL                        NaN
PCITEMCIAP             BASEICST  NUMBER(18,6)                          Base de Calculo do ST            OPERACIONAL                        NaN
PCITEMCIAP          PERCALIQINT  NUMBER(12,4)            Alíquota de venda dentro UF Calc.ST            OPERACIONAL                        NaN
PCITEMCIAP          PERCALIQEXT  NUMBER(12,4)   Alíquota fora da UF (NF de entrada) Calc.ST)            OPERACIONAL                        NaN
PCITEMCIAP       REDBASEALIQEXT  NUMBER(18,6) Percentual de Redução alíquota Externa Calc.ST            OPERACIONAL                        NaN
PCITEMCIAP               PERCST  NUMBER(12,4)                                  Percentual ST            OPERACIONAL                        NaN
PCITEMCIAP                 VLST  NUMBER(18,6)                                 Valor do ST NF            OPERACIONAL                        NaN
PCITEMCIAP          VLPAUTAICMS  NUMBER(18,6)            Valor de Pauta p/ Calc.Base do ICMS            OPERACIONAL                        NaN
PCITEMCIAP             BASEICMS  NUMBER(18,6)                        Base de Calculo do ICMS            OPERACIONAL                        NaN
PCITEMCIAP               PERICM  NUMBER(12,4)                               Alíquota de ICMS            OPERACIONAL                        NaN
PCITEMCIAP           PERCICMRED  NUMBER(12,4)                       Alíquota de redução ICMS            OPERACIONAL                        NaN
PCITEMCIAP               VLICMS  NUMBER(18,6)                                  Valor do ICMS            OPERACIONAL                        NaN
PCITEMCIAP          PERCREDICMS  NUMBER(12,4)                Alíquota de ICMS p/ Calc.Custo.            OPERACIONAL                        NaN
PCITEMCIAP           VLCREDICMS  NUMBER(18,6)                    Valor do ICMS p/ Calc.Custo            OPERACIONAL                        NaN
PCITEMCIAP PERCCREDICMPRESUMIDO  NUMBER(12,4)                     Alíquota de ICMS Presumido            OPERACIONAL                        NaN
PCITEMCIAP      VLCREDPRESUMIDO  NUMBER(18,6)                        Valor do ICMS presumido            OPERACIONAL                        NaN
PCITEMCIAP      VLBASEPISCOFINS  NUMBER(18,6)            Valor da Base de calculo PIS/COFINS            OPERACIONAL                        NaN
PCITEMCIAP               PERPIS  NUMBER(12,4)                                Alíquota de PIS            OPERACIONAL                        NaN
PCITEMCIAP            VLCREDPIS  NUMBER(18,6)                        Valor do crédito de PIS            OPERACIONAL                        NaN
PCITEMCIAP            PERCOFINS  NUMBER(12,4)                             Alíquota de COFINS            OPERACIONAL                        NaN
PCITEMCIAP         VLCREDCOFINS  NUMBER(18,6)                     Valor de crédito de COFINS            OPERACIONAL                        NaN
PCITEMCIAP                  OBS VARCHAR2(500)                            Observação do item.            OPERACIONAL                        NaN
PCITEMCIAP  CODSITTRIBPISCOFINS   NUMBER(3,0)          Código Situação tributaria PIS/COFINS            OPERACIONAL                        NaN
PCITEMCIAP     VLPAUTAPISCOFINS  NUMBER(18,6)                               Pauta Pis/Cofins            OPERACIONAL                        NaN
PCITEMCIAP    APLICPERCIVAPAUTA   VARCHAR2(1)              Aplica IVA sobre o valor de Pauta            OPERACIONAL                        NaN
PCITEMCIAP  APLICREDBASEIVAPLIQ   VARCHAR2(1)           Aplica Redução Base s/ Preço Líquido            OPERACIONAL                        NaN
PCITEMCIAP      PISCOFINSRETIDO   VARCHAR2(1)                              Pis/Cofins Retido            OPERACIONAL                        NaN
PCITEMCIAP     BASEDIFALIQUOTAS  NUMBER(18,6)        Base de calculo diferencial de aliquota            OPERACIONAL                        NaN
PCITEMCIAP     PERCDIFALIQUOTAS  NUMBER(12,4)          Percentual do diferencial de aliquota            OPERACIONAL                        NaN
PCITEMCIAP       VLDIFALIQUOTAS  NUMBER(18,6)               Valor do diferencial de aliquota            OPERACIONAL                        NaN
PCITEMCIAP      PERCALIQINTICMS  NUMBER(12,4)           Percentual de alíquota interna ICMS             OPERACIONAL                        NaN
PCITEMCIAP      PERCALIQEXTICMS  NUMBER(12,4)            Percentual de alíquota externa ICMS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*