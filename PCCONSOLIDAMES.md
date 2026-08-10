# 📊 Tabela: PCCONSOLIDAMES

### Estrutura de Colunas e Restrições

        Tabela          Coluna Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONSOLIDAMES            TIPO  VARCHAR2(1) Define o tipo de consolidação: PCAUXPROD = "P", PCAUXCLI = "C", PCAUXFOR = "F", VENDA = "V"     CHAVE PRIMÁRIA (PK)                        NaN
PCCONSOLIDAMES          CODIGO  NUMBER(9,0)                                                   Codigo definido pelo tipo de consolidação.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSOLIDAMES       CODFILIAL  VARCHAR2(2)                                                                Código da filial consolidado.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSOLIDAMES             MES  NUMBER(2,0)                                                                             Mês consolidado.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSOLIDAMES             ANO  NUMBER(4,0)                                                                             Ano consolidado.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSOLIDAMES         QTVENDA NUMBER(22,6)                                                     Quantidade venda consolidado no período.            OPERACIONAL                        NaN
PCCONSOLIDAMES         VLVENDA NUMBER(22,6)                                                       Valor da venda consolidado no período.            OPERACIONAL                        NaN
PCCONSOLIDAMES        VLCOMPRA NUMBER(22,6)                                                      Valor da compra consolidado no período.            OPERACIONAL                        NaN
PCCONSOLIDAMES     QTPRODUZIDA NUMBER(22,6)                                                                        Quantidade Produzida.            OPERACIONAL                        NaN
PCCONSOLIDAMES        QTCOMPRA NUMBER(22,6)                                                                    Quantidade compra por mês            OPERACIONAL                        NaN
PCCONSOLIDAMES QTDEVFORNECEDOR NUMBER(22,6)                                                 Quantidade de devolução a fornecedor por mês            OPERACIONAL                        NaN
PCCONSOLIDAMES    QTDEVCLIENTE NUMBER(22,6)                                                           Quantidade de devolução de cliente            OPERACIONAL                        NaN
PCCONSOLIDAMES     VLULTENTMES NUMBER(18,6)                                                             Média do valor da última entrada            OPERACIONAL                        NaN
PCCONSOLIDAMES   VLPONDSAIDMES NUMBER(18,6)                                                        Média ponderada das vendas no período            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*