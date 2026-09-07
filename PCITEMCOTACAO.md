# 📊 Tabela: PCITEMCOTACAO

### Estrutura de Colunas e Restrições

       Tabela              Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMCOTACAO           CODFILIAL  VARCHAR2(2)                          Indica o código filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAO             CODPROD  NUMBER(6,0)                      Indica o código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAO           CODFORNEC  NUMBER(6,0)                   Indica o código do fornecedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAO          NUMCOTACAO  NUMBER(8,0)                      Indica o número da cotação.    CHAVE PRIMÁRIA (PK)                  PCCOTACAO
PCITEMCOTACAO             PCOMPRA NUMBER(18,6)                        Indica o preço de compra.            OPERACIONAL                        NaN
PCITEMCOTACAO            GANHADOR  VARCHAR2(1)                    Indica o fornecedor ganhador.            OPERACIONAL                        NaN
PCITEMCOTACAO              NUMPED NUMBER(10,0)                Indica o pedido de compra gerado.            OPERACIONAL                        NaN
PCITEMCOTACAO VALORULTENTPREVISTO NUMBER(18,6)        GRAVAR O VALOR DA ULTIMA ENTRADA PREVISTA            OPERACIONAL                        NaN
PCITEMCOTACAO CUSTOULTENTPREVISTO NUMBER(18,6)        GRAVAR O CUSTO DA ULTIMA ENTRADA PREVISTA            OPERACIONAL                        NaN
PCITEMCOTACAO    DESPESAADICIONAL NUMBER(18,6) Despesas que devem ser somadas ao preço ofertado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*