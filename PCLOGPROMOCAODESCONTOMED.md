# 📊 Tabela: PCLOGPROMOCAODESCONTOMED

### Estrutura de Colunas e Restrições

                  Tabela                     Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPROMOCAODESCONTOMED                CODDESCONTO   NUMBER(8,0)                              Código do desconto    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPROMOCAODESCONTOMED                     CODCLI   NUMBER(9,0)                               Código do Cliente            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                    CODEPTO   NUMBER(6,0)                          Código do Departamento            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                     CODSEC   NUMBER(6,0)                                 Código da Seção            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED               CODCATEGORIA   NUMBER(6,0)                             Código da Categoria            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                    CODPROD   NUMBER(6,0)                               Código do Produto            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                   PERCDESC  NUMBER(10,4)                          Percentual de Desconto            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                   DTINICIO          DATE                                     Data Inicio    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPROMOCAODESCONTOMED                      DTFIM          DATE                                      Data Final    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPROMOCAODESCONTOMED                    CODUSUR   NUMBER(4,0)                                   Código do RCA            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                   CODPLPAG   NUMBER(4,0)                    Código do Plano de Pagamento            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED             BASECREDDEBRCA   VARCHAR2(1)                                Usa Déb/Créd RCA            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED            UTILIZADESCREDE   VARCHAR2(1)                           Utiliza Desconto Rede            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  CODFORNEC   NUMBER(6,0)                            Código do Fornecedor            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED              CODSUPERVISOR   NUMBER(4,0)                            Código do Supervisor            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  TIPOVENDA   VARCHAR2(2)                                      Tipo Venda            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  NUMREGIAO   NUMBER(4,0)                                Número da Região            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                CODFUNCLANC   NUMBER(8,0)                   Código Funcionário Lançamento            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                   DATALANC          DATE                              Data do Lançamento            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                         UF   VARCHAR2(2)                                   UF do Cliente            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                    CODATIV   NUMBER(6,0)                     Código do Ramo de Atividade            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  ORIGEMPED   VARCHAR2(1)                                Origem do Pedido            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                   CODPRACA   NUMBER(4,0)                                 Código da Praça            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED               CODPRODPRINC   NUMBER(6,0)                     Código do Produto Principal            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                    NUMORCA  NUMBER(10,0)                             Número do Orçamento            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                 TIPOCLIMED   VARCHAR2(2)                       Tipo Cliente Medicamentos            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED             PERCDESCFORNEC  NUMBER(10,4)            Percentual de Desconto do Fornecedor            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                CLASSEVENDA   VARCHAR2(1)                                    Classe Venda            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED             APLICADESCONTO   VARCHAR2(1)                 Aplica Desconto automaticamente            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  TIPOCARGA   VARCHAR2(1)                                      Tipo Carga            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED       CREDITASOBREPOLITICA   VARCHAR2(1)                                 Credita c/c RCA            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                       TIPO   VARCHAR2(1)                                Tipo do desconto            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                PERCDESCFIN  NUMBER(10,4)               Percentual de Desconto Financeiro            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED              PERDESCFORNEC  NUMBER(10,4)                            Perc Desc Fornecedor            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED              ALTERAPTABELA   VARCHAR2(1)                                Alterar P Tabela            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED        TIPOAPLICDESCONTOCB   VARCHAR2(1)                      Tipo Aplicação Desconto CB            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  CODPRODCB   NUMBER(6,0)                               Código Produto CB            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED PERCCCOMPROFISSIONALMINIMO   NUMBER(8,4)                Percentual Comissão Profissional            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                 DTEXCLUSAO          DATE                                Data da Exclusão    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPROMOCAODESCONTOMED            CODFUNCEXCLUSAO   NUMBER(8,0)                  Código Funcionário da Exclusão            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED               DATAULTALTER          DATE                           Data última alteração            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED            CODFUNCULTALTER   NUMBER(8,0)                    Código funcionário alteração            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                AREAATUACAO   VARCHAR2(1)                                    Área atuação            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED         QTDEMAXIMAPOLITICA  NUMBER(10,4)                            Qtde Máxima Política            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  CODFILIAL   VARCHAR2(2)                                Código da filial            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED           QTDEMAXIMAPEDIDO  NUMBER(10,4)                              Qtde máxima pedido            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                   CODGRUPO  NUMBER(10,0)                                 Código do grupo            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED             APENASPLPAGMAX   VARCHAR2(1)                   Apenas plano pagamento máximo            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                 PERCOMMINT  NUMBER(10,4)         Percentual de comissão vendedor interno            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  PERCOMREP  NUMBER(10,4)                   Percentual de comissão do rca            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  PERCOMEXT  NUMBER(10,4)      Percentual de comissão do vendedor externo            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED  APLICADESCSIMPLESNACIONAL   VARCHAR2(1)                Aplica desconto simples nacional            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                   CODMARCA   NUMBER(8,0)                                 Código da Marca            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                    CODREDE   NUMBER(4,0)                                  Código da Rede            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED     CONSIDERACALCGIROMEDIC   VARCHAR2(1)     Considera no cálculo do giro do medicamento            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED           CODIDENTIFICADOR  NUMBER(10,0)                            Código identificador            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  PRECOFIXO  NUMBER(10,4)                                      Preço Fixo            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                 CODCLICONV   NUMBER(8,0)                             Código Cliente CONV            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED            QTDEMINDESCONTO   NUMBER(8,0)                            Qtde mínima desconto            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED               SUBCATEGORIA   NUMBER(8,0)                          Código da subcategoria            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                FISCALCAIXA   VARCHAR2(1)                                    Fiscal Caixa            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED               CODGRUPOREST   NUMBER(6,0)                    Código do grupo de restrição            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED              TIPOGRUPOREST   VARCHAR2(2)                            Tipo grupo restrição            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                PERCDESCMAX  NUMBER(10,4)                    Percentual de desconto máxim            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                      QTINI  NUMBER(10,4)                               Quantidade mínima            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                      QTFIM  NUMBER(10,4)                                Quantidade final            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  VLRMINIMO  NUMBER(18,6)                                    Valor Mínimo            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  VLRMAXIMO  NUMBER(18,6)                                    Valor máximo            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED               TIPODESCONTO   VARCHAR2(1)                                   Tipo Desconto            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                CODAUXILIAR  NUMBER(20,0)                                      Código EAN            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                 CLASSEPROD   VARCHAR2(1)                                  Classe Produto            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED          QTDAPLICACOESDESC  NUMBER(10,4)                        Qtde aplicações desconto            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED           QTMINESTPARADESC  NUMBER(10,4)                             Qt minima para desc            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED              CODDESCONTOID  NUMBER(16,0)                              Código desconto ID            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED             CODPROMOCAOMED   NUMBER(9,0)              Código da Promoção de Medicamentos            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED               CODLINHAPROD   NUMBER(6,0)                      Código da Linha de Produto            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED    TIPOPOLITICAPROMOCAOMED   VARCHAR2(1)                    Tipo de política da promoção            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED INICIOINTERVALOPROMOCAOMED  NUMBER(10,4)                   Inicio intervalo promoção MED            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED    FIMINTERVALOPROMOCAOMED  NUMBER(10,4)             Fim intervalo promoção medicamentos            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED   PARTICIPACOMISSGARANTIDA   VARCHAR2(1)                 Participa da comissão garantida            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED            PERCDESCBASERCA  NUMBER(10,4)              Percentual desconto sobre pbaserca            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED            PERCBONIFICMERC  NUMBER(10,4)         Percentual de bonificação de mercadoria            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED              PERCMARKUPMED  NUMBER(10,4)            Percentual de markup de medicamentos            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                 PERCFORNEC  NUMBER(10,4)                           Percentual Fornecedor            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                  DESCRICAO VARCHAR2(100)                           Descrição da politica            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                   NUMVERBA   NUMBER(8,0)                                 Número da verba            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED             PERCCUSTFORNEC  NUMBER(12,4)             Percentual rebaixa custo fornecedor            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                TIPOENTREGA   VARCHAR2(2)                                    Tipo Entrega            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED       VLDESCCMVPROMOCAOMED  NUMBER(18,6)          Valor desconto rebaixa CMV medicamento            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED        CODIGOINTEGRACAOWMS  VARCHAR2(20)                           Código Integração WMS            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED               VALORCOTAMED  NUMBER(18,6)                       Valor da Cota Medicamento            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED       PRECOFIXOPROMOCAOMED  NUMBER(18,6)                          Preço Fixo da Promoção            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED       REGRAALTERARDESCONTO   VARCHAR2(1)            Regra de Alteração do Desconto/Preço            OPERACIONAL                        NaN
PCLOGPROMOCAODESCONTOMED                 QTCOMBOMED  NUMBER(10,4) Quantidade no combo para promoções Kit Variável            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*