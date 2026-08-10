# 📊 Tabela: PCCODIGOBENEFICIOFISCALVINCULO

### Estrutura de Colunas e Restrições

                        Tabela                   Coluna  Tipo/Tamanho                                                                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCODIGOBENEFICIOFISCALVINCULO    TIPOTRIBUTACAOENTRADA   VARCHAR2(1)                                                      Tipo de tributação determinado na 132, parametro 1533 - Tipo Tributação de Entrada            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO          NATUREZAVINCULO   VARCHAR2(1)                                                                                 Identifica a natureza do vinculo S = Saída, E = Entrada            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO        TIPOCLIENTEFORNEC  VARCHAR2(10)                                                            Identifica o tipo do cliente para Saída e o tipo do Fornecedor para Entrada.            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO                CODFILIAL   VARCHAR2(2) Identifica o código da filial de destino - Utilizado para o tipo de tributação (NCM / Figura Tributaria e  Produto / figura tributária)            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO                  CODPROD   NUMBER(6,0)                                                                                                      Identificação do código do produto            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO          CODIGOBENEFICIO  VARCHAR2(10)                                                                                             Identificação do código do benefício fiscal            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO         FIGURATRIBUTARIA   NUMBER(8,0)                                                                                                      Identificação da figura tributária            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO                 UFORIGEM   VARCHAR2(2)                                                                                                           Identificação da uf de origem            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO                UFDESTINO   VARCHAR2(2)                                                                                                          identificação da uf de destino            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO                      NCM  VARCHAR2(20)                                                                                                                    Identificação do NCM            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO                CODFISCAL   NUMBER(8,0)                                                                                                   Código Fiscal de Operação e Prestaçáo            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO                SITTRIBUT   VARCHAR2(3)                                                                                                             Situação Tributária do ICMS            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO CODBENEFICIOFISCALCOMPLE VARCHAR2(100)                                                                                                 Código de beneficio fiscal complementar            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO                DTALTERC5  TIMESTAMP(6)                                                                                                              Data alteração do registro            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO                CBENEFRBC  VARCHAR2(10)                                                                                                          Código de Benefício Fiscal RBC            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO            DTVIGENCIAINI          DATE                                                                                                                Data inicial de vigência            OPERACIONAL                        NaN
PCCODIGOBENEFICIOFISCALVINCULO            DTVIGENCIAFIM          DATE                                                                                                                  Data final da Vigência            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*