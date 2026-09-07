# 📊 Tabela: PCCORTEVENDAASSISTIDA

### Estrutura de Colunas e Restrições

               Tabela    Coluna Tipo/Tamanho                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCORTEVENDAASSISTIDA    NUMPED NUMBER(10,0) Campo para armazenar o número do pedido de venda assistida que sofreu exclusão de produtos.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA   CODPROD  NUMBER(6,0)                                          Campo para armazenar o código do produto excluído.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA    NUMSEQ NUMBER(20,0)                             Campo para armazenar o número da seqüência do produto excluído.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA        QT NUMBER(20,6)                                        Campo para armazenar quantidade do produto excluído.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA      DATA         DATE                                    Campo para armazenar data e hora da exclusão do produto.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA   CODFUNC  NUMBER(8,0)                       Campo para armazenar código do funcionário responsável pela exclusão.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA    PVENDA NUMBER(18,6)                                    Campo para armazenar preço de venda do produto excluído.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA  DTPEDIDO         DATE                                    Campo para armazenar data do pedido que sofreu exclusão.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA CODFILIAL  VARCHAR2(2)                        Campo para armazenar código da filial do pedido que sofreu exclusão.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA    CODCLI  NUMBER(6,0)                       Campo para armazenar código do cliente do pedido que sofreu exclusão.            OPERACIONAL                        NaN
PCCORTEVENDAASSISTIDA   CODUSUR  NUMBER(4,0)                      Campo para armazenar código do vendedor do pedido que sofreu exclusão.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*