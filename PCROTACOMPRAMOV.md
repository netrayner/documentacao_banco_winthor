# 📊 Tabela: PCROTACOMPRAMOV

### Estrutura de Colunas e Restrições

         Tabela                      Coluna Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTACOMPRAMOV                      NUMPED NUMBER(10,0)                                       Número do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCROTACOMPRAMOV                 NUMTRANSENT NUMBER(10,0)                         Número da transação de entrada            OPERACIONAL                        NaN
PCROTACOMPRAMOV                NUMTRANSITEM NUMBER(10,0)                            Número de transação do item    CHAVE PRIMÁRIA (PK)                        NaN
PCROTACOMPRAMOV                     CODPROD  NUMBER(6,0)                                      Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCROTACOMPRAMOV                      NUMSEQ  NUMBER(3,0)              Número sequencial dos produtos na entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCROTACOMPRAMOV                     CODROTA NUMBER(10,0)          Código da rota do item referenciado na PCITEM            OPERACIONAL                        NaN
PCROTACOMPRAMOV                   QTENTRADA NUMBER(20,6)                          Quantidade de entrada do item            OPERACIONAL                        NaN
PCROTACOMPRAMOV                  NUMPEDTV10 NUMBER(10,0)               Número do pedido gerado a partir da TV10            OPERACIONAL                        NaN
PCROTACOMPRAMOV                 NUMSEQVENDA  NUMBER(3,0)      Número sequencial dos itens gerados da venda TV10            OPERACIONAL                        NaN
PCROTACOMPRAMOV            DTESTORNOENTRADA         DATE                   Data de estorno da entrada de compra            OPERACIONAL                        NaN
PCROTACOMPRAMOV               DTESTORNOTV10         DATE              Data de estorno da nota do pedido da TV10            OPERACIONAL                        NaN
PCROTACOMPRAMOV        NUMTRANSDEVOLENTRADA NUMBER(10,0)       Número da transação de devolução de entrada 1302            OPERACIONAL                        NaN
PCROTACOMPRAMOV        DTCANCELDEVOLENTRADA         DATE           Data de cancelamento da devolução de entrada            OPERACIONAL                        NaN
PCROTACOMPRAMOV NUMTRANSESTORNODEVOLENTRADA NUMBER(10,0) Número da transação de estorno da devolução de entrada            OPERACIONAL                        NaN
PCROTACOMPRAMOV                  DTINCLUSAO         DATE          Data e hora da inclusão do registro na tabela            OPERACIONAL                        NaN
PCROTACOMPRAMOV                       ORDEM NUMBER(10,0)                Ordem sequencial relacionada ao CODROTA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*