# 📊 Tabela: PCCONTROLENUMSERIE

### Estrutura de Colunas e Restrições

            Tabela            Coluna Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTROLENUMSERIE          NUMSERIE VARCHAR2(30)                                                                      Indica o número de série.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLENUMSERIE           CODPROD  NUMBER(6,0)                                                                    Indica o código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLENUMSERIE       NUMTRANSENT NUMBER(10,0)                                                       Indica o número da transação de entrada.            OPERACIONAL                        NaN
PCCONTROLENUMSERIE           DTSAIDA         DATE                                                                        Indica a data de saída.            OPERACIONAL                        NaN
PCCONTROLENUMSERIE           DTDEVOL         DATE                                                                    Indica a data da devolução.            OPERACIONAL                        NaN
PCCONTROLENUMSERIE     NUMTRANSVENDA NUMBER(10,0)                                                         Indica o número da transação de venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLENUMSERIE     PRAZOGARANTIA  NUMBER(5,0)                                                          Indica o prazo de grantia do produto.            OPERACIONAL                        NaN
PCCONTROLENUMSERIE DTTERMINOGARANTIA         DATE                                                          Indica a data de término da garantia.            OPERACIONAL                        NaN
PCCONTROLENUMSERIE            NUMPED NUMBER(10,0) Campo para identificar o pedido que está vinculado a atribuição do número de série ao produto.            OPERACIONAL                        NaN
PCCONTROLENUMSERIE           NUMNOTA NUMBER(10,0)                                                                                 Número da Nota            OPERACIONAL                        NaN
PCCONTROLENUMSERIE            NUMSEQ NUMBER(20,0)                                                                              Número Sequêncial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*