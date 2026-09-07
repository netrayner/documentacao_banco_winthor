# 📊 Tabela: PCCONFABASTECIMENTOWMS

### Estrutura de Colunas e Restrições

                Tabela                         Coluna  Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFABASTECIMENTOWMS                    CODOPERACAO   NUMBER(4,0)                                   Código da operação    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFABASTECIMENTOWMS                      DESCRICAO VARCHAR2(100)             Descrição modelo abastecimento corretivo            OPERACIONAL                        NaN
PCCONFABASTECIMENTOWMS    TIPOPRIORIDADEABASTECIMENTO  VARCHAR2(15)         Define o tipo da prioridade do abastecimento            OPERACIONAL                        NaN
PCCONFABASTECIMENTOWMS   TIPOTRATAMENTOQTDEFRACIONADA  VARCHAR2(15) Define o tipo do tratamento da quantidade fracionada            OPERACIONAL                        NaN
PCCONFABASTECIMENTOWMS     TIPOABASTECIMENTOCORRETIVO  VARCHAR2(15)             Define o tipo do abastecimento corretivo            OPERACIONAL                        NaN
PCCONFABASTECIMENTOWMS ABASTECEPICKINGVENDAPELOMASTER   VARCHAR2(1)       Define se abastece o picking venda pelo master            OPERACIONAL                        NaN
PCCONFABASTECIMENTOWMS USAENDERECOPREPICKINGPARAVENDA   VARCHAR2(1)      Define se usa o endereço pré-picking para venda            OPERACIONAL                        NaN
PCCONFABASTECIMENTOWMS MOVIMENTACAOHORIZONTALVERTICAL   VARCHAR2(1)   Define se utiliza movimentação horizontal vertical            OPERACIONAL                        NaN
PCCONFABASTECIMENTOWMS                          ATIVO       CHAR(1)      Informa se o modelo de abastecimento está ativo            OPERACIONAL                        NaN
PCCONFABASTECIMENTOWMS              CODCONTROLEACESSO   NUMBER(3,0) Código controle de acesso ao modelo de abastecimento            OPERACIONAL                        NaN
PCCONFABASTECIMENTOWMS           USAENDERECOLOJAABAST       CHAR(1)           Considerar estoque loja para abastecimento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*