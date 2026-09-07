# 📊 Tabela: PCITEMCOTACAOIMP

### Estrutura de Colunas e Restrições

          Tabela              Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMCOTACAOIMP           CODFILIAL  VARCHAR2(2)                                         Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAOIMP             CODPROD  NUMBER(6,0)                                        Código do produto            OPERACIONAL                        NaN
PCITEMCOTACAOIMP           CODFORNEC  NUMBER(6,0)                                     Código do fornecedor            OPERACIONAL                        NaN
PCITEMCOTACAOIMP          NUMCOTACAO  NUMBER(8,0)                                        Número da cotação    CHAVE PRIMÁRIA (PK)               PCCOTACAOIMP
PCITEMCOTACAOIMP             PCOMPRA NUMBER(18,6)                                          Preço de compra            OPERACIONAL                        NaN
PCITEMCOTACAOIMP            GANHADOR      CHAR(1) Flag verificando se o fornecedor é o vencedor da cotação            OPERACIONAL                        NaN
PCITEMCOTACAOIMP              NUMPED NUMBER(10,0)                                         Número do pedido            OPERACIONAL                        NaN
PCITEMCOTACAOIMP VALORULTENTPREVISTO NUMBER(18,6)                            Valor última entrada prevista            OPERACIONAL                        NaN
PCITEMCOTACAOIMP CUSTOULTENTPREVISTO NUMBER(18,6)                            Custo última entrada prevista            OPERACIONAL                        NaN
PCITEMCOTACAOIMP   CODPRODCOTACAOIMP  NUMBER(8,0)          Código de ligação com a tabela PCPRODCOTACAOIMP    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAOIMP              STATUS      CHAR(1)                      Status do item cotado por fonecedor            OPERACIONAL                        NaN
PCITEMCOTACAOIMP     CODFORNECCOTIMP  NUMBER(8,0)                             Código do fornecedor cotação    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMCOTACAOIMP    DESPESAADICIONAL NUMBER(18,6)         Despesas que devem ser somadas ao preço ofertado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*