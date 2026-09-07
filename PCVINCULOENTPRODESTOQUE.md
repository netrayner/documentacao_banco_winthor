# 📊 Tabela: PCVINCULOENTPRODESTOQUE

### Estrutura de Colunas e Restrições

                 Tabela               Coluna Tipo/Tamanho                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVINCULOENTPRODESTOQUE        CODSEQVINCULO NUMBER(18,0)                                                                    Sequência de cadastro            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE            CODFILIAL  VARCHAR2(2)                                                             Código da Filial da Operação            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE              CODPROD  NUMBER(6,0)                                                                        Código do Produto            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE          NUMTRANSENT NUMBER(10,0)                                                   Número da transaçaõ da nota de entrada            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE              NUMNOTA NUMBER(10,0)                                                                Número da nota de entrada            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE         DTINVENTARIO         DATE                                                            Data do inventário processado            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE            CODFORNEC  NUMBER(6,0)                                                                     Código do Fornecedor            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE DESCRICAO_FORNECEDOR VARCHAR2(60)                                                                  Descrição do fornecedor            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE         UFFORNECEDOR  VARCHAR2(2)                                                                         UF do Fornecedor            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE            DTENTRADA         DATE                                                                          Data da entrada            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE                 CFOP  NUMBER(4,0)                                                                                     Cfop            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE              CSTICMS  NUMBER(3,0)                                                                                      CST            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE                   QT NUMBER(22,8)                                                  Quantidade utilizada da nota de entrada            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE           VLBASEICMS NUMBER(18,6)                                                                    Valor da base de icms            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE               VLICMS NUMBER(18,6)                                                                            Valor do icms            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE             VLBASEST NUMBER(18,6)                                                                 Valor da base do icms ST            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE                 VLST NUMBER(18,6)                                                                         Valor do icms ST            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE        VLBASEICMSBCR NUMBER(18,6)                                                                Valor da base do icms BCR            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE            VLICMSBCR NUMBER(18,6)                                                                        Valor do icms BCR            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE       VLBASESTFORANF NUMBER(18,6)                                                                 Valor da base ST fora NF            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE           VLSTFORANF NUMBER(18,6)                                                                      Valor da ST fora NF            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE          VLBASESTBCR NUMBER(18,6)                                                                     Valor da base ST BCR            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE            VLSTSTBCR NUMBER(18,6)                                                                          Valor da ST BCR            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE      VLBASEPISCOFINS NUMBER(20,6)                                                   Valor da base de cálculo do Pis/Cofins            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE                VLPIS NUMBER(18,6)                                                                             Valor do Pis            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE             VLCOFINS NUMBER(24,6)                                                                          Valor do Cofins            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE            VLBASEIPI NUMBER(18,6)                                                          Valor da base de cálculo do IPI            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE                VLIPI NUMBER(18,6)                                                                             Valor do IPI            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE               VLFECP NUMBER(18,6)                                                                            Valor do FECP            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE         VLFECPSTGUIA NUMBER(18,6)                                                                 Valor do FECP de ST Guia            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE           VLFCPSTRET NUMBER(18,6)                                                                  Valor do FECP ST Retido            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE            PUNITCONT NUMBER(18,6)                                                        Valor unitário do item de entrada            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE         ORIGMERCTRIB  VARCHAR2(1)                                                                     Origem da Mercadoria            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE             CST_H020  VARCHAR2(3)                                                               Cst informado na tela 1074            OPERACIONAL                        NaN
PCVINCULOENTPRODESTOQUE      VLICMSRESTITUIR NUMBER(18,6) Valor ICMS a restituir (Base ST pela Alíquota interna do cadastro de produto por filial)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*