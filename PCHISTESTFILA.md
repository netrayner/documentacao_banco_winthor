# 📊 Tabela: PCHISTESTFILA

### Estrutura de Colunas e Restrições

       Tabela                    Coluna Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTESTFILA                 CODFILIAL  VARCHAR2(2)                                                                               Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTFILA                   CODPROD  NUMBER(6,0)                                                                              Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTFILA                      DATA         DATE                                                  Data do dia de processamento da PCHISTESTFILA    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTFILA                     QTEST NUMBER(22,8)                                                                 Quantidade do estoque contábil            OPERACIONAL                        NaN
PCHISTESTFILA                  QTESTGER NUMBER(22,8)                                                                Quantidade do estoque gerencial            OPERACIONAL                        NaN
PCHISTESTFILA                 CUSTOCONT NUMBER(18,6)                                                                      Custo contábil do produto            OPERACIONAL                        NaN
PCHISTESTFILA                 CUSTOREAL NUMBER(18,6)                                                                          Custo real do produto            OPERACIONAL                        NaN
PCHISTESTFILA                  CUSTOFIN NUMBER(18,6)                                                                    Custo financeiro do produto            OPERACIONAL                        NaN
PCHISTESTFILA                  CUSTOREP NUMBER(18,6)                                                                             Custo de reposição            OPERACIONAL                        NaN
PCHISTESTFILA               CUSTOULTENT NUMBER(18,6)                                                                        Custo da ultima entrada            OPERACIONAL                        NaN
PCHISTESTFILA                   VLVENDA NUMBER(14,2)                                                                      Valor de venda do produto            OPERACIONAL                        NaN
PCHISTESTFILA               VLCUSTOREAL NUMBER(14,2)                                                                 Valor do custo real do produto            OPERACIONAL                        NaN
PCHISTESTFILA                VLCUSTOFIN NUMBER(14,2)                                                           Valor do custo financeiro do produto            OPERACIONAL                        NaN
PCHISTESTFILA               VALORULTENT NUMBER(18,6)                                                             Valor da ultima entrada do produto            OPERACIONAL                        NaN
PCHISTESTFILA                CUSTODOLAR NUMBER(18,6)                                                                                 Custo do dolar            OPERACIONAL                        NaN
PCHISTESTFILA            CUSTOREALSEMST NUMBER(18,6)                                                                              Custo real sem ST            OPERACIONAL                        NaN
PCHISTESTFILA            CUSTOULTENTMED NUMBER(18,6)                                                        Custo da ultima entrada do medicamentos            OPERACIONAL                        NaN
PCHISTESTFILA         CUSTOULTPEDCOMPRA NUMBER(18,6)                                                    Custo da ultima entrada do pedido de compra            OPERACIONAL                        NaN
PCHISTESTFILA            VALORULTENTMED NUMBER(18,6)                                                         Valor da ultima entrada do medicamento            OPERACIONAL                        NaN
PCHISTESTFILA                      VLST NUMBER(18,6)                                                                         Valor do st do produto            OPERACIONAL                        NaN
PCHISTESTFILA                  QTRESERV NUMBER(22,8)                                                                Quantidade reservada do produto            OPERACIONAL                        NaN
PCHISTESTFILA               QTBLOQUEADA NUMBER(16,3)                                                                Quantidade bloqueada do produto            OPERACIONAL                        NaN
PCHISTESTFILA                 QTINDENIZ NUMBER(16,3)                                                                 Quantidade avariada do produto            OPERACIONAL                        NaN
PCHISTESTFILA                QTPENDENTE NUMBER(16,3)                                                                 Quantidade pendente do produto            OPERACIONAL                        NaN
PCHISTESTFILA                 DTGERACAO         DATE                                                              Data de inserção da PCHISTESTFILA            OPERACIONAL                        NaN
PCHISTESTFILA               TOTALVLICMS NUMBER(16,2)                                                              Total de ICMS contido no estoque.            OPERACIONAL                        NaN
PCHISTESTFILA                 TOTALVLST NUMBER(16,2)                                                                Total de ST contido no estoque.            OPERACIONAL                        NaN
PCHISTESTFILA                 DESCRICAO VARCHAR2(40)                                                                          Descrição do produto.            OPERACIONAL                        NaN
PCHISTESTFILA                    PERICM NUMBER(10,2)                                                                                % ICMS produto.            OPERACIONAL                        NaN
PCHISTESTFILA           ALIQICMSVIGENTE  NUMBER(5,2)                                                       Aliq. ICMS vigente para o produto na UF.            OPERACIONAL                        NaN
PCHISTESTFILA                   UNIDADE  VARCHAR2(2)                                                                  Unidade de medida do produto.            OPERACIONAL                        NaN
PCHISTESTFILA             TIPOMERCDEPTO  VARCHAR2(2)                                                    Tipo Merc. Do departamento do departamento.            OPERACIONAL                        NaN
PCHISTESTFILA                       NBM VARCHAR2(15)                                                                                NCM do produto.            OPERACIONAL                        NaN
PCHISTESTFILA                        DV  NUMBER(1,0)                                                       Digito verificador do código do produto.            OPERACIONAL                        NaN
PCHISTESTFILA                  TIPOMERC  VARCHAR2(2)                                                                         Tipo Merc. do produto.            OPERACIONAL                        NaN
PCHISTESTFILA           CODPRODSINTEGRA VARCHAR2(20)                                                      Cód.Prod. para envio no arquivo Sintegra.            OPERACIONAL                        NaN
PCHISTESTFILA                 IMPORTADO  VARCHAR2(1)                                                               Indica se o produto é Importado.            OPERACIONAL                        NaN
PCHISTESTFILA                 EMBALAGEM VARCHAR2(12)                                                                          Embalagem do produto.            OPERACIONAL                        NaN
PCHISTESTFILA           CLASSIFICFISCAL VARCHAR2(20)                                                               Classificação fiscal do produto.            OPERACIONAL                        NaN
PCHISTESTFILA               CODAUXILIAR VARCHAR2(20)                                                                       Cód.Auxiliar do produto.            OPERACIONAL                        NaN
PCHISTESTFILA            DTEXCLUSAOPROD         DATE                                                                   Data de exclusão do produto.            OPERACIONAL                        NaN
PCHISTESTFILA                 HISTORICO  VARCHAR2(1)                                                   Gerou histórico para o registro, sim ou não.            OPERACIONAL                        NaN
PCHISTESTFILA           PISCOFINSRETIDO  VARCHAR2(1)                                                               Indica se o PIS/COFINS é retido.            OPERACIONAL                        NaN
PCHISTESTFILA                    PERPIS NUMBER(12,4)                                                         Indica o percentual do PIS do produto.            OPERACIONAL                        NaN
PCHISTESTFILA                 PERCOFINS NUMBER(12,4)                                                         Indica o percentual COFINS do produto.            OPERACIONAL                        NaN
PCHISTESTFILA                    CODICM  NUMBER(8,4)                                                        Indica o percentual do ICMS do produto.            OPERACIONAL                        NaN
PCHISTESTFILA                 SITTRIBUT  VARCHAR2(3)                                                                  Indica a situação tributária.            OPERACIONAL                        NaN
PCHISTESTFILA                    PERCST NUMBER(12,4)                                                                     Indica o percentual de ST.            OPERACIONAL                        NaN
PCHISTESTFILA           CODGENEROFISCAL  NUMBER(6,0)                                                              Indica o código do genero fiscal.            OPERACIONAL                        NaN
PCHISTESTFILA               CUSTOFORNEC NUMBER(12,6)                                                                  Indica o custo do fornecedor.            OPERACIONAL                        NaN
PCHISTESTFILA              CODPRODRELEV NUMBER(10,0)                                                                   Código de Produto Relevante.            OPERACIONAL                        NaN
PCHISTESTFILA       CODSITTRIBPISCOFINS  NUMBER(3,0)                                                   Código da Situação tributária do PIS/COFINS.            OPERACIONAL                        NaN
PCHISTESTFILA                FUNDAPIANO  VARCHAR2(1) Produto pertencente ao FUNDAP, legislação do Espirito Santo, para impressão de livros fiscais.            OPERACIONAL                        NaN
PCHISTESTFILA                  QTULTENT NUMBER(16,3)                                                         Indica a quantidade da ultima entrada.            OPERACIONAL                        NaN
PCHISTESTFILA                QTTRANSITO NUMBER(22,8)                                                                         Quantidade em Trânsito            OPERACIONAL                        NaN
PCHISTESTFILA           TOTALVLBASEICMS NUMBER(16,2)                                                                    Valor Total da Base de ICMS            OPERACIONAL                        NaN
PCHISTESTFILA                TOTALVLIPI NUMBER(16,2)                                                                               Total Valor IPI.            OPERACIONAL                        NaN
PCHISTESTFILA                TOTALVLPIS NUMBER(16,2)                                                                               Total Valor PIS.            OPERACIONAL                        NaN
PCHISTESTFILA             TOTALVLCOFINS NUMBER(16,2)                                                                            Total Valor COFINS.            OPERACIONAL                        NaN
PCHISTESTFILA                CODINTERNO VARCHAR2(20)                                                           Código interno do produto da empresa            OPERACIONAL                        NaN
PCHISTESTFILA              QTFRENTELOJA NUMBER(22,6)                                                                  Quantidade no estoque da loja            OPERACIONAL                        NaN
PCHISTESTFILA             CUSTOFINSEMST NUMBER(18,6)                                                                        Custo financeiro sem ST            OPERACIONAL                        NaN
PCHISTESTFILA       CUSTOULTENTFINSEMST NUMBER(18,6)                                                      Custo financeiro sem ST da última entrada            OPERACIONAL                        NaN
PCHISTESTFILA          CUSTOULTENTSEMST NUMBER(18,6)                                                                 Custo sem ST da ultima entrada            OPERACIONAL                        NaN
PCHISTESTFILA          CUSTOFORNECSEMST NUMBER(18,6)                                                                           Custo fornece sem ST            OPERACIONAL                        NaN
PCHISTESTFILA    CUSTONFSEMSTGUIAULTENT NUMBER(18,6)                                                         Custo NF sem ST Guia da última entrada            OPERACIONAL                        NaN
PCHISTESTFILA              CUSTONFSEMST NUMBER(18,6)                                                                             Custo da NF sem ST            OPERACIONAL                        NaN
PCHISTESTFILA CUSTONFSEMSTGUIAULTENTTAB NUMBER(18,6)                                                     Custo NF sem ST Guia da última entrada TAB            OPERACIONAL                        NaN
PCHISTESTFILA           CUSTONFSEMSTTAB NUMBER(18,6)                                                                            Custo NF sem ST Tab            OPERACIONAL                        NaN
PCHISTESTFILA        CUSTOPROXIMACOMPRA NUMBER(18,6)                                                                           Custo próxima compra            OPERACIONAL                        NaN
PCHISTESTFILA   CUSTOPROXIMACOMPRASEMST NUMBER(18,6)                                                                    Custo próxima compra sem ST            OPERACIONAL                        NaN
PCHISTESTFILA              CUSTOREALLIQ NUMBER(18,6)                                                                             Custo real Líquido            OPERACIONAL                        NaN
PCHISTESTFILA            CUSTOULTENTANT NUMBER(18,6)                                                                  Custo última entrada anterior            OPERACIONAL                        NaN
PCHISTESTFILA           CUSTOULTENTCONT NUMBER(18,6)                                                               Custo contabil da última entrada            OPERACIONAL                        NaN
PCHISTESTFILA            CUSTOULTENTFIN NUMBER(18,6)                                                                Custo Financeiro última entrada            OPERACIONAL                        NaN
PCHISTESTFILA            CUSTOULTENTLIQ NUMBER(18,6)                                                                Custo Líquido da última entrada            OPERACIONAL                        NaN
PCHISTESTFILA                  DTULTENT         DATE                                                                            Data última entrada            OPERACIONAL                        NaN
PCHISTESTFILA             VLCUSTODIAFIN NUMBER(12,2)                                                                           Custo Financeiro dia            OPERACIONAL                        NaN
PCHISTESTFILA            VLCUSTODIAREAL NUMBER(12,2)                                                                              Custo Real do dia            OPERACIONAL                        NaN
PCHISTESTFILA             VLCUSTOMESFIN NUMBER(12,2)                                                                        Custo Financeiro do Mês            OPERACIONAL                        NaN
PCHISTESTFILA          VLCUSTOMESFINANT NUMBER(14,2)                                                               Custo Financeiro do Mês anterior            OPERACIONAL                        NaN
PCHISTESTFILA            VLCUSTOMESREAL NUMBER(12,2)                                                                              Custo Real do Mês            OPERACIONAL                        NaN
PCHISTESTFILA         VLCUSTOMESREALANT NUMBER(14,2)                                                                     Custo Real do Mês anterior            OPERACIONAL                        NaN
PCHISTESTFILA       VLFRETECONHECULTENT NUMBER(18,6)                                                     Valor conhecimento de frete última entrada            OPERACIONAL                        NaN
PCHISTESTFILA    VLFRETECONHECULTENTTAB NUMBER(18,6)                                              Valor conhecimento de frete última entrada Futuro            OPERACIONAL                        NaN
PCHISTESTFILA           VLIMPORTACAOFCI NUMBER(18,6)                                                                           Valor importação FCI            OPERACIONAL                        NaN
PCHISTESTFILA           VLPARCELAIMPFCI NUMBER(18,6)                                                                   Valor Parcela Importação FCI            OPERACIONAL                        NaN
PCHISTESTFILA            VLSTGUIAULTENT NUMBER(18,6)                                                             Valor do ST guia da última entrada            OPERACIONAL                        NaN
PCHISTESTFILA         VLSTGUIAULTENTTAB NUMBER(18,6)                                                         Valor Tab do ST guia da última entrada            OPERACIONAL                        NaN
PCHISTESTFILA                VLSTULTENT NUMBER(18,6)                                                                  Valor do ST da última entrada            OPERACIONAL                        NaN
PCHISTESTFILA             VLSTULTENTTAB NUMBER(18,6)                                                              Valor do ST da última entrada TAB            OPERACIONAL                        NaN
PCHISTESTFILA         VLULTENTCONTSEMST NUMBER(18,6)                                                        Valor contabil da última entrada sem ST            OPERACIONAL                        NaN
PCHISTESTFILA              VLULTPCOMPRA NUMBER(18,6)                                                               Valor do última pedido de compra            OPERACIONAL                        NaN
PCHISTESTFILA                   BASEBCR NUMBER(18,6)                                                                                 Valor base BCR            OPERACIONAL                        NaN
PCHISTESTFILA                     STBCR NUMBER(18,6)                                                                                      ST de BCR            OPERACIONAL                        NaN
PCHISTESTFILA               VLIPIULTENT NUMBER(18,6)                                                                 Valor de IPI da ultima entrada            OPERACIONAL                        NaN
PCHISTESTFILA             BASEIPIULTENT NUMBER(18,6)                                                                  Base de IPI da ultima entrada            OPERACIONAL                        NaN
PCHISTESTFILA             PERCIPIULTENT NUMBER(18,6)                                                            Percentual de IPI da ultima entrada            OPERACIONAL                        NaN
PCHISTESTFILA            QTTRANSITOTV13 NUMBER(22,8)                                                              Quantidade de estoque em trânsito            OPERACIONAL                        NaN
PCHISTESTFILA                   CODCEST  VARCHAR2(7)                                                                         Código CEST do produto            OPERACIONAL                        NaN
PCHISTESTFILA               QTINDUSTRIA NUMBER(22,8) Campo destinado a quantidade de produtos que está em poder da indústria, aguardando liberação.            OPERACIONAL                        NaN
PCHISTESTFILA       QTESTOQUEEMTERCEIRO NUMBER(22,8)                                                            Quantidade de estoque em terceiros.            OPERACIONAL                        NaN
PCHISTESTFILA       QTESTOQUEDETERCEIRO NUMBER(22,8)                                                            Quantidade de estoque de terceiros.            OPERACIONAL                        NaN
PCHISTESTFILA            QTTRANSITOTV10 NUMBER(22,8)                         Quantidade em transito com o tipo de venda igual a 10 - Transferência.            OPERACIONAL                        NaN
PCHISTESTFILA               CUSTOFISCAL NUMBER(18,6)                                                                             Custo Medio Fiscal            OPERACIONAL                        NaN
PCHISTESTFILA         CUSTOULTENTFISCAL NUMBER(18,6)                                                                    Custo fiscal ultima entrada            OPERACIONAL                        NaN
PCHISTESTFILA         QTTRANSITOBENEFIC NUMBER(22,8)                               Quantidade de estoque em trânsito específica para beneficiamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*