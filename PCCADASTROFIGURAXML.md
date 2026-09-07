# 📊 Tabela: PCCADASTROFIGURAXML

### Estrutura de Colunas e Restrições

             Tabela                    Coluna Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCADASTROFIGURAXML       TIPOPESQUISAPRODUTO  VARCHAR2(5)                                 Tipo de pesquisa de produto.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML                      CFOP  VARCHAR2(4)                   Código CFOP referente a figura cadastrada.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML               BONIFICACAO  VARCHAR2(1) Campo de identificação do CFOP, se é do tipo de bonificação.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML   NOTAFISCALUNIDADEMASTER  VARCHAR2(1)                          Nota fiscal está na unidade master.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML     UTILIZAFATORCONVERSAO  VARCHAR2(1)                    Utiliza fator de conversão da rotina 253.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML    UTILIZAREDUCAOBASEICMS  VARCHAR2(1)                         Utiliza redução de base ICMS "PARA".            OPERACIONAL                        NaN
PCCADASTROFIGURAXML ACEITAPRODUTPROIBIDOVENDA  VARCHAR2(1)                        Aceita produtos proibidos para venda.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML       GRAVARCODIGOFABRICA  VARCHAR2(1)                             Código de fábrica da rotina 253.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML   ACEITAPRODUTOSFORALINHA  VARCHAR2(1)                               Aceita produtos fora de linha.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML      GERARPEDIDOCOMPRAXML  VARCHAR2(1)                              Gerar pedido de compra com XML.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML CONSIDERARICMSDESOCALCSUF  VARCHAR2(1)     Considera ICMS desoneração motivo 9 cálculo SUF/REPASSE.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML ACEITAPRODPRECMOEDESTRANG  VARCHAR2(1)       Aceita produtos com precificação em moeda estrangeira.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML              VALORCOTACAO  NUMBER(6,4)                         Valor da cotação(moeda estrangeira).            OPERACIONAL                        NaN
PCCADASTROFIGURAXML   CARREGARTRIBPOLITCOMERC  VARCHAR2(1)                 Carregar tributos/pol. Comercial fora da NF.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML  CONSIDERARORIGEMCADASTRO  VARCHAR2(1)             Considerar origem da mercadoria do cadastro 238.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML               TIPOENTRADA  VARCHAR2(1)                                       Tipo de entrada da NF.            OPERACIONAL                        NaN
PCCADASTROFIGURAXML                 CODFIGXML  NUMBER(6,0)                       Código identificador da figura de XML.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*