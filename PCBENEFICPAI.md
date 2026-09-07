# 📊 Tabela: PCBENEFICPAI

### Estrutura de Colunas e Restrições

      Tabela                   Coluna Tipo/Tamanho                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICPAI                   NUMPED NUMBER(10,0)                                                                 Número do pedido de produto acabado    CHAVE PRIMÁRIA (PK)               PCBENEFICPAC
PCBENEFICPAI                  CODPROD NUMBER(10,0)                                                                           Código do produto acabado    CHAVE PRIMÁRIA (PK)                   PCPRODUT
PCBENEFICPAI                   NUMSEQ  NUMBER(5,0)                                                                         Número sequencial dos itens    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICPAI              QTAPRODUZIR NUMBER(18,6)                                                                   Quantidade de produtos a produzir            OPERACIONAL                        NaN
PCBENEFICPAI             CUSTOUNIDADE NUMBER(18,6)                                                                    Preço base da unidade do produto            OPERACIONAL                        NaN
PCBENEFICPAI              QTPRODUZIDA NUMBER(18,6)                                                                  Quantidade já produzida do produto            OPERACIONAL                        NaN
PCBENEFICPAI               VLDESCONTO NUMBER(18,6)                                                                         Valor do desconto comercial            OPERACIONAL                        NaN
PCBENEFICPAI             PERCDESCONTO NUMBER(12,4)                                                                    Percentual do desconto comercial            OPERACIONAL                        NaN
PCBENEFICPAI                VLSUFRAMA NUMBER(18,6)                                                                                    Valor do suframa            OPERACIONAL                        NaN
PCBENEFICPAI              PERCSUFRAMA NUMBER(12,4)                                                                               Percentual do suframa            OPERACIONAL                        NaN
PCBENEFICPAI                  VLFRETE NUMBER(18,6)                                                                                      Valor do frete            OPERACIONAL                        NaN
PCBENEFICPAI                PERCFRETE NUMBER(12,4)                                                                                 Percentual do frete            OPERACIONAL                        NaN
PCBENEFICPAI                  BASEIPI NUMBER(18,6)                                                                                         Base do ipi            OPERACIONAL                        NaN
PCBENEFICPAI                  VLIPIKG NUMBER(18,6)                                                                               Valor do ipi por kilo            OPERACIONAL                        NaN
PCBENEFICPAI                    VLIPI NUMBER(18,6)                                                                                        Valor do ipi            OPERACIONAL                        NaN
PCBENEFICPAI                  PERCIPI NUMBER(12,4)                                                                                   Percentual do ipi            OPERACIONAL                        NaN
PCBENEFICPAI                 VLSEGURO NUMBER(18,6)                                                                                     Valor do seguro            OPERACIONAL                        NaN
PCBENEFICPAI               PERCSEGURO NUMBER(12,4)                                                                                Percentual do seguro            OPERACIONAL                        NaN
PCBENEFICPAI           VLDESPDENTRONF NUMBER(18,6)                                                                   Valor das despesas dentro da nota            OPERACIONAL                        NaN
PCBENEFICPAI         PERCDESPDENTRONF NUMBER(12,4)                                                              Percentual das despesas dentro da nota            OPERACIONAL                        NaN
PCBENEFICPAI                   BASEST NUMBER(18,6)                                                                                       Base do st nf            OPERACIONAL                        NaN
PCBENEFICPAI                     VLST NUMBER(18,6)                                                                                      Valor do st nf            OPERACIONAL                        NaN
PCBENEFICPAI                   PERCST NUMBER(12,4)                                                                                 Percentual do st nf            OPERACIONAL                        NaN
PCBENEFICPAI               TIPOCALCST  VARCHAR2(1)                                                                               Tipo de calculo do st            OPERACIONAL                        NaN
PCBENEFICPAI        APLICPERCIVAPAUTA  VARCHAR2(1)                                        Determina se o valor de iva será agregado no valor da pauta.            OPERACIONAL                        NaN
PCBENEFICPAI      APLICREDBASEIVAPLIQ  VARCHAR2(1)                                                              Aplicar redução base iva preço líquido            OPERACIONAL                        NaN
PCBENEFICPAI             USAPMCBASEST  VARCHAR2(1)                                                                           Indica se usa PMC base st            OPERACIONAL                        NaN
PCBENEFICPAI                  VLPAUTA NUMBER(18,6)                                                                                Valor da pauta de st            OPERACIONAL                        NaN
PCBENEFICPAI              PERCALIQINT NUMBER(12,4)                                                                              Alíquota interna do st            OPERACIONAL                        NaN
PCBENEFICPAI              PERCALIQEXT NUMBER(12,4)                                                                              Alíquota externa do st            OPERACIONAL                        NaN
PCBENEFICPAI                  PERCIVA NUMBER(12,4)                                                                                     Alíquota de iva            OPERACIONAL                        NaN
PCBENEFICPAI              PERCMVAORIG NUMBER(12,4)                                                                            Alíquota de iva original            OPERACIONAL                        NaN
PCBENEFICPAI       PERCCARGATRIBMEDIA NUMBER(12,4) Percentual de carga tributária média, utilizado no SEFAZ MT para calculo da substituição tributária            OPERACIONAL                        NaN
PCBENEFICPAI               REDBASEIVA NUMBER(12,4)                                                                          Alíquota de redução do iva            OPERACIONAL                        NaN
PCBENEFICPAI           REDBASEALIQEXT NUMBER(12,4)                                                             Alíquota de redução da alíquota externa            OPERACIONAL                        NaN
PCBENEFICPAI          PERCALIQEXTGUIA NUMBER(12,4)                                                                               Alíquota externa guia            OPERACIONAL                        NaN
PCBENEFICPAI       PERCICMSFRETEFOBST NUMBER(12,4)                                                                          Alíquota de icms frete fob            OPERACIONAL                        NaN
PCBENEFICPAI          VLADICIONALBCST NUMBER(18,6)                                                                  Valor adicional base de calculo st            OPERACIONAL                        NaN
PCBENEFICPAI               PERCREDPMC NUMBER(12,4)                                                                          Alíquota de redução do pmc            OPERACIONAL                        NaN
PCBENEFICPAI           PRECOMAXCONSUM NUMBER(18,6)                                                                 Indica o preço máximo ao consumidor            OPERACIONAL                        NaN
PCBENEFICPAI                PAUTAICMS NUMBER(18,6)                                                                              Valor da pauta de icms            OPERACIONAL                        NaN
PCBENEFICPAI                 BASEICMS NUMBER(18,6)                                                                                        Base do icms            OPERACIONAL                        NaN
PCBENEFICPAI                   VLICMS NUMBER(18,6)                                                                                       Valor do icms            OPERACIONAL                        NaN
PCBENEFICPAI                 ALIQICMS NUMBER(12,4)                                                                                    Alíquota de icms            OPERACIONAL                        NaN
PCBENEFICPAI              ALIQICMSRED NUMBER(12,4)                                                                         Alíquota de redução do icms            OPERACIONAL                        NaN
PCBENEFICPAI               VLCREDICMS NUMBER(18,6)                                                                            Valor do crédito de icms            OPERACIONAL                        NaN
PCBENEFICPAI              PERCREDICMS NUMBER(12,4)                                                                       Percentual do crédito de icms            OPERACIONAL                        NaN
PCBENEFICPAI               VLPAUTAIPI NUMBER(18,6)                                                                               Valor da pauta de ipi            OPERACIONAL                        NaN
PCBENEFICPAI        BASECREDPRESUMIDO NUMBER(18,6)                                                                   Base do crédito presumido de icms            OPERACIONAL                        NaN
PCBENEFICPAI     PERCCREDICMPRESUMIDO NUMBER(12,4)                                                                     Percentual do crédido presumido            OPERACIONAL                        NaN
PCBENEFICPAI          VLCREDPRESUMIDO NUMBER(18,6)                                                                          Valor do crédito presumido            OPERACIONAL                        NaN
PCBENEFICPAI            VLDESCICMSDIF NUMBER(18,6)                                                                              Valor do icms diferido            OPERACIONAL                        NaN
PCBENEFICPAI          PERCDESCICMSDIF NUMBER(12,4)                                                                         Percentual do icms diferido            OPERACIONAL                        NaN
PCBENEFICPAI GERABASEPISCOFINSSEMALIQ  VARCHAR2(1)                                                      Indica se gera base de pis/cofins sem alíquota            OPERACIONAL                        NaN
PCBENEFICPAI         VLPAUTAPISCOFINS NUMBER(18,6)                                                                        Valor da pauta de pis/cofins            OPERACIONAL                        NaN
PCBENEFICPAI                VLCREDPIS NUMBER(18,6)                                                                             Valor do crédito de pis            OPERACIONAL                        NaN
PCBENEFICPAI             VLCREDCOFINS NUMBER(18,6)                                                                          Valor do crédito de cofins            OPERACIONAL                        NaN
PCBENEFICPAI                   PERPIS NUMBER(12,4)                                                                          Alíquota de crédito de pis            OPERACIONAL                        NaN
PCBENEFICPAI                PERCOFINS NUMBER(12,4)                                                                       Alíquota de crédito de cofins            OPERACIONAL                        NaN
PCBENEFICPAI          VLBASEPISCOFINS NUMBER(18,6)                                                                                  Base de pis/cofins            OPERACIONAL                        NaN
PCBENEFICPAI      CODSITTRIBPISCOFINS  NUMBER(3,0)                                                                            Código cst de pis/cofins            OPERACIONAL                        NaN
PCBENEFICPAI          PRECOMERCADORIA NUMBER(18,6)                                                                                 Preço da mercadoria            OPERACIONAL                        NaN
PCBENEFICPAI                CODFISCAL NUMBER(10,0)                                                                            Código fiscal do produto            OPERACIONAL                        NaN
PCBENEFICPAI                SITTRIBUT  VARCHAR2(3)                                                                      Situação tributária do produto            OPERACIONAL                        NaN
PCBENEFICPAI              CALCCREDIPI  VARCHAR2(1)                                                         Indica se deduz o crédito de ipi no produto            OPERACIONAL                        NaN
PCBENEFICPAI             ORIGMERCTRIB  VARCHAR2(1)                                                                      Código da origem da mercadoria            OPERACIONAL                        NaN
PCBENEFICPAI  CODMOTIVOICMSDESONERADO  VARCHAR2(2)                                                                   Código do motivo desoneração icms            OPERACIONAL                        NaN
PCBENEFICPAI        VLICMSDESONERACAO NUMBER(18,6)                                                                            Valor do icms desonerado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*