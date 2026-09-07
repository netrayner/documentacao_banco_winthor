# 📊 Tabela: PCBENEFICMPI

### Estrutura de Colunas e Restrições

      Tabela                   Coluna Tipo/Tamanho                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICMPI                   NUMPED NUMBER(10,0)                                                                   Número do pedido de materia prima    CHAVE PRIMÁRIA (PK)               PCBENEFICMPC
PCBENEFICMPI                  CODPROD NUMBER(10,0)                                                                             Código da materia prima    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICMPI                   NUMSEQ  NUMBER(5,0)                                                                         Número sequencial dos itens    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICMPI           QTMATERIAPRIMA NUMBER(18,6)                                                                            Quantidade materia prima            OPERACIONAL                        NaN
PCBENEFICMPI                PRECOBASE NUMBER(18,6)                                                                    Preço base da unidade do produto            OPERACIONAL                        NaN
PCBENEFICMPI               VLDESCONTO NUMBER(18,6)                                                                         Valor do desconto comercial            OPERACIONAL                        NaN
PCBENEFICMPI             PERCDESCONTO NUMBER(12,4)                                                                    Percentual do desconto comercial            OPERACIONAL                        NaN
PCBENEFICMPI                VLSUFRAMA NUMBER(18,6)                                                                                    Valor do suframa            OPERACIONAL                        NaN
PCBENEFICMPI              PERCSUFRAMA NUMBER(12,4)                                                                               Percentual do suframa            OPERACIONAL                        NaN
PCBENEFICMPI                  VLFRETE NUMBER(18,6)                                                                                      Valor do frete            OPERACIONAL                        NaN
PCBENEFICMPI                PERCFRETE NUMBER(12,4)                                                                                 Percentual do frete            OPERACIONAL                        NaN
PCBENEFICMPI                  BASEIPI NUMBER(18,6)                                                                                         Base do ipi            OPERACIONAL                        NaN
PCBENEFICMPI                  VLIPIKG NUMBER(18,6)                                                                               Valor do ipi por kilo            OPERACIONAL                        NaN
PCBENEFICMPI                    VLIPI NUMBER(18,6)                                                                                        Valor do ipi            OPERACIONAL                        NaN
PCBENEFICMPI                  PERCIPI NUMBER(12,4)                                                                                   Percentual do ipi            OPERACIONAL                        NaN
PCBENEFICMPI                 VLSEGURO NUMBER(18,6)                                                                                     Valor do seguro            OPERACIONAL                        NaN
PCBENEFICMPI               PERCSEGURO NUMBER(12,4)                                                                                Percentual do seguro            OPERACIONAL                        NaN
PCBENEFICMPI           VLDESPDENTRONF NUMBER(18,6)                                                                   Valor das despesas dentro da nota            OPERACIONAL                        NaN
PCBENEFICMPI         PERCDESPDENTRONF NUMBER(12,4)                                                              Percentual das despesas dentro da nota            OPERACIONAL                        NaN
PCBENEFICMPI                   BASEST NUMBER(18,6)                                                                                       Base do st nf            OPERACIONAL                        NaN
PCBENEFICMPI                     VLST NUMBER(18,6)                                                                                      Valor do st nf            OPERACIONAL                        NaN
PCBENEFICMPI                   PERCST NUMBER(12,4)                                                                                 Percentual do st nf            OPERACIONAL                        NaN
PCBENEFICMPI               TIPOCALCST  VARCHAR2(1)                                                                               Tipo de calculo do st            OPERACIONAL                        NaN
PCBENEFICMPI        APLICPERCIVAPAUTA  VARCHAR2(1)                                        Determina se o valor de iva será agregado no valor da pauta.            OPERACIONAL                        NaN
PCBENEFICMPI      APLICREDBASEIVAPLIQ  VARCHAR2(1)                                                              Aplicar redução base iva preço líquido            OPERACIONAL                        NaN
PCBENEFICMPI             USAPMCBASEST  VARCHAR2(1)                                                                           Indica se usa PMC base st            OPERACIONAL                        NaN
PCBENEFICMPI                  VLPAUTA NUMBER(18,6)                                                                                Valor da pauta de st            OPERACIONAL                        NaN
PCBENEFICMPI              PERCALIQINT NUMBER(12,4)                                                                              Alíquota interna do st            OPERACIONAL                        NaN
PCBENEFICMPI              PERCALIQEXT NUMBER(12,4)                                                                              Alíquota externa do st            OPERACIONAL                        NaN
PCBENEFICMPI                  PERCIVA NUMBER(12,4)                                                                                     Alíquota de iva            OPERACIONAL                        NaN
PCBENEFICMPI              PERCMVAORIG NUMBER(12,4)                                                                            Alíquota de iva original            OPERACIONAL                        NaN
PCBENEFICMPI       PERCCARGATRIBMEDIA NUMBER(12,4) Percentual de carga tributária média, utilizado no SEFAZ MT para calculo da substituição tributária            OPERACIONAL                        NaN
PCBENEFICMPI               REDBASEIVA NUMBER(12,4)                                                                          Alíquota de redução do iva            OPERACIONAL                        NaN
PCBENEFICMPI           REDBASEALIQEXT NUMBER(12,4)                                                             Alíquota de redução da alíquota externa            OPERACIONAL                        NaN
PCBENEFICMPI          PERCALIQEXTGUIA NUMBER(12,4)                                                                               Alíquota externa guia            OPERACIONAL                        NaN
PCBENEFICMPI       PERCICMSFRETEFOBST NUMBER(12,4)                                                                          Alíquota de icms frete fob            OPERACIONAL                        NaN
PCBENEFICMPI          VLADICIONALBCST NUMBER(18,6)                                                                  Valor adicional base de calculo st            OPERACIONAL                        NaN
PCBENEFICMPI               PERCREDPMC NUMBER(12,4)                                                                          Alíquota de redução do pmc            OPERACIONAL                        NaN
PCBENEFICMPI           PRECOMAXCONSUM NUMBER(18,6)                                                                 Indica o preço máximo ao consumidor            OPERACIONAL                        NaN
PCBENEFICMPI                PAUTAICMS NUMBER(18,6)                                                                              Valor da pauta de icms            OPERACIONAL                        NaN
PCBENEFICMPI                 BASEICMS NUMBER(18,6)                                                                                        Base do icms            OPERACIONAL                        NaN
PCBENEFICMPI                   VLICMS NUMBER(18,6)                                                                                       Valor do icms            OPERACIONAL                        NaN
PCBENEFICMPI                 ALIQICMS NUMBER(12,4)                                                                                    Alíquota de icms            OPERACIONAL                        NaN
PCBENEFICMPI              ALIQICMSRED NUMBER(12,4)                                                                         Alíquota de redução do icms            OPERACIONAL                        NaN
PCBENEFICMPI               VLCREDICMS NUMBER(18,6)                                                                            Valor do crédito de icms            OPERACIONAL                        NaN
PCBENEFICMPI              PERCREDICMS NUMBER(12,4)                                                                       Percentual do crédito de icms            OPERACIONAL                        NaN
PCBENEFICMPI               VLPAUTAIPI NUMBER(18,6)                                                                               Valor da pauta de ipi            OPERACIONAL                        NaN
PCBENEFICMPI        BASECREDPRESUMIDO NUMBER(18,6)                                                                   Base do crédito presumido de icms            OPERACIONAL                        NaN
PCBENEFICMPI     PERCCREDICMPRESUMIDO NUMBER(12,4)                                                                     Percentual do crédido presumido            OPERACIONAL                        NaN
PCBENEFICMPI          VLCREDPRESUMIDO NUMBER(18,6)                                                                          Valor do crédito presumido            OPERACIONAL                        NaN
PCBENEFICMPI            VLDESCICMSDIF NUMBER(12,4)                                                                             Valor do icms diferido.            OPERACIONAL                        NaN
PCBENEFICMPI          PERCDESCICMSDIF NUMBER(12,4)                                                                         Percentual do icms diferido            OPERACIONAL                        NaN
PCBENEFICMPI GERABASEPISCOFINSSEMALIQ  VARCHAR2(1)                                                      Indica se gera base de pis/cofins sem alíquota            OPERACIONAL                        NaN
PCBENEFICMPI         VLPAUTAPISCOFINS NUMBER(18,6)                                                                        Valor da pauta de pis/cofins            OPERACIONAL                        NaN
PCBENEFICMPI                VLCREDPIS NUMBER(18,6)                                                                             Valor do crédito de pis            OPERACIONAL                        NaN
PCBENEFICMPI             VLCREDCOFINS NUMBER(18,6)                                                                          Valor do crédito de cofins            OPERACIONAL                        NaN
PCBENEFICMPI                   PERPIS NUMBER(12,4)                                                                          Alíquota de crédito de pis            OPERACIONAL                        NaN
PCBENEFICMPI                PERCOFINS NUMBER(12,4)                                                                       Alíquota de crédito de cofins            OPERACIONAL                        NaN
PCBENEFICMPI          VLBASEPISCOFINS NUMBER(18,6)                                                                                  Base de pis/cofins            OPERACIONAL                        NaN
PCBENEFICMPI      CODSITTRIBPISCOFINS  NUMBER(3,0)                                                                           Código cst de pis/cofins'            OPERACIONAL                        NaN
PCBENEFICMPI          PRECOMERCADORIA NUMBER(18,6)                                                                                 Preço da mercadoria            OPERACIONAL                        NaN
PCBENEFICMPI                CODFISCAL NUMBER(10,0)                                                                            Código fiscal do produto            OPERACIONAL                        NaN
PCBENEFICMPI                SITTRIBUT  VARCHAR2(3)                                                                      Situação tributária do produto            OPERACIONAL                        NaN
PCBENEFICMPI              CALCCREDIPI  VARCHAR2(1)                                                         Indica se deduz o crédito de ipi no produto            OPERACIONAL                        NaN
PCBENEFICMPI             ORIGMERCTRIB  VARCHAR2(1)                                                                      Código da origem da mercadoria            OPERACIONAL                        NaN
PCBENEFICMPI  CODMOTIVOICMSDESONERADO  VARCHAR2(2)                                                                   Código do motivo desoneração icms            OPERACIONAL                        NaN
PCBENEFICMPI        VLICMSDESONERACAO NUMBER(18,6)                                                                            Valor do icms desonerado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*