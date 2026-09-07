# 📊 Tabela: PCLOGINTEGRACAOWMS

### Estrutura de Colunas e Restrições

            Tabela         Coluna  Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGINTEGRACAOWMS           DATA          DATE                                   Data e hora de integração.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS     INTEGRACAO   NUMBER(4,0)                                        Integração efetuada..            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS      MATRICULA   NUMBER(8,0)                          Matricula que efetuou a integração.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS      CODFILIAL   VARCHAR2(2)                   Código da Filial que efetuou a integração.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS      NUMPEDIDO  NUMBER(10,0)                                  Número do pedido integrado.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS   NUMNOTASAIDA  NUMBER(10,0)                                     Nota de saída integrada.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS NUMNOTAENTRADA  NUMBER(10,0)                                   Nota de entrada integrada.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS         STATUS  VARCHAR2(50)                                        Status da integração.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS     COMENTARIO VARCHAR2(500)                                    Comentário da integração.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS  PROCESSAMENTO  VARCHAR2(20) Tipo de processamento da integração: Exportação, Importação.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS  CODINTEGRACAO  NUMBER(10,0)                            Sequência da integração numérica.            OPERACIONAL                        NaN
PCLOGINTEGRACAOWMS        CODPROD   NUMBER(6,0)                  Código do produto na integração do produto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*