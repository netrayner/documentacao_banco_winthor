# 📊 Tabela: PCCAPAVINCULOENTPRODESTOQUE

### Estrutura de Colunas e Restrições

                     Tabela               Coluna Tipo/Tamanho                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCAPAVINCULOENTPRODESTOQUE        CODSEQVINCULO NUMBER(18,0)                                                                    Sequência de cadastro    CHAVE PRIMÁRIA (PK)                        NaN
PCCAPAVINCULOENTPRODESTOQUE            CODFILIAL  VARCHAR2(2)                                                             Código da Filial da Operação            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE              CODPROD  NUMBER(6,0)                                                                        Código do Produto            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE         DTINVENTARIO         DATE                                                                       Data do inventário            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE                QTEST NUMBER(22,8)                    Quantidade de produtos em estoque com base na informação da pchistest            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE       QTTRANSITOTV13 NUMBER(22,8)                                                  Quantidade de produtos em transito TV13            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE            SITTRIBUT  VARCHAR2(3)                                                            Código da Situação Tributária            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE              UNIDADE  VARCHAR2(2)                                                                                  Unidade            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE           CODINTERNO VARCHAR2(20)                                                                Código Interno do produto            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE            DESCRICAO VARCHAR2(40)                                                                     Descrição do produto            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE                  NCM VARCHAR2(15)                                                                            Código do NCM            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE      VLTOTALBASEICMS NUMBER(18,6)                                         Soma da base de cálculo de icms normal das notas            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE          VLTOTALICMS NUMBER(18,6)                                                            Soma do icms normal das notas            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE        VLTOTALBASEST NUMBER(18,6)                                                       Soma da base de cálculo de icms ST            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE            VLTOTALST NUMBER(18,6)                                                                          Soma do icms ST            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE   VLTOTALBASEICMSBCR NUMBER(18,6)                                                      Soma da base de cálculo de icms BCR            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE       VLTOTALICMSBCR NUMBER(18,6)                                                                         Soma so icms BCR            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE  VLTOTALBASESTFORANF NUMBER(18,6)                                               Soma da Base de cálculo do ST fora da Nota            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE      VLTOTALSTFORANF NUMBER(18,6)                                                                  Soma do ST fora da Nota            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE     VLTOTALBASESTBCR NUMBER(18,6)                                                                   Soma da Base do ST BCR            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE       VLTOTALSTSTBCR NUMBER(18,6)                                                                           Soma do ST BCR            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE      VLMEDIABASEICMS NUMBER(18,6)                                                              Valor médio da Base de icms            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE          VLMEDIAICMS NUMBER(18,6)                                                                      Valor médio do icms            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE        VLMEDIABASEST NUMBER(18,6)                                                                   Valor médio da Base ST            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE            VLMEDIAST NUMBER(18,6)                                                                        Valor médio da ST            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE          VLCUSTOCONT NUMBER(18,6)                                                                    Custo Contábio do Dia            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE           VLCUSTOFIN NUMBER(18,6)                                                                  Custo Financeiro do dia            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE          VLCUSTOREAL NUMBER(18,6)                                                                        Custo Real do dia            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE     VLCUSTOREALSEMST NUMBER(18,6)                                                                 Custo Real sem ST do dia            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE           VLCUSTOREP NUMBER(18,6)                                                                         Custo Rep do dia            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE        VLCUSTOULTENT NUMBER(18,6)                                                              Custo última entrada do dia            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE             VLULTENT NUMBER(18,6)                                                                     Valor última entrada            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE    VLULTENTCONTSEMST NUMBER(18,6)                                                              Valor última entrada sem ST            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE      VLBASEPISCOFINS NUMBER(20,6)                                                   Valor da base de cálculo do Pis/Cofins            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE                VLPIS NUMBER(18,6)                                                                             Valor do Pis            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE             VLCOFINS NUMBER(24,6)                                                                          Valor do Cofins            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE            VLBASEIPI NUMBER(18,6)                                                          Valor da base de cálculo do IPI            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE                VLIPI NUMBER(18,6)                                                                             Valor do IPI            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE               VLFECP NUMBER(18,6)                                                                            Valor do FECP            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE         VLFECPSTGUIA NUMBER(18,6)                                                                 Valor do FECP de ST Guia            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE           VLFCPSTRET NUMBER(18,6)                                                                  Valor do FECP ST Retido            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE           VLMEDIAFCP NUMBER(18,6)                                                                       Valor média do FCP            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE VLTOTALICMSRESTITUIR NUMBER(18,6) Total ICMS a restituir (Base ST pela Alíquota interna do cadastro de produto por filial)            OPERACIONAL                        NaN
PCCAPAVINCULOENTPRODESTOQUE         VLMEDIAPUNIT NUMBER(18,6)                                                                     Valor médio do punit            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*