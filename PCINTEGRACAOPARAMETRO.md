# 📊 Tabela: PCINTEGRACAOPARAMETRO

### Estrutura de Colunas e Restrições

               Tabela          Coluna  Tipo/Tamanho                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOPARAMETRO      SEQPED2562   NUMBER(6,0)                            Indica o número sequencial do pedido a ser exportado.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO FAIXAINIPED2562   NUMBER(6,0)                  Indica o valor inicial do sequencial do pedido a ser exportado.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO FAIXAFIMPED2562   NUMBER(6,0)                   Indica o valor final do squencicial do pedido a ser exportado.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO  IDTRANSPED2562   NUMBER(6,0)                  Indica o código da transação de estoque para o pedido de venda.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO      SEQNFE2562   NUMBER(6,0)             Indica o número sequencial da nota fisca de entrada a ser exportado.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO FAIXAININFE2562   NUMBER(6,0) Indica o valor inicial do sequencial da noata fiscal de entrada a ser exportado.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO FAIXAFIMNFE2562   NUMBER(6,0)   Indica o valor final do squencicial da nota fiscal de entrada a ser exportado.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO  IDTRANSNFE2562   NUMBER(6,0)             Indica o código da transação de estoque para nota fiscal de entrada.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO       CODFILIAL   VARCHAR2(2)                                                                Código da filial.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO          DIRENT VARCHAR2(100)                 Diretório dos arquivo de entreda onde os arquivos serão gerados.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO       DIRENTBKP VARCHAR2(100)                                      Diretório de backup dos arquivo de entreda.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO          DIRSAI VARCHAR2(100)                                                  Diretório dos arquivo de saída.            OPERACIONAL                        NaN
PCINTEGRACAOPARAMETRO       DIRSAIBKP VARCHAR2(100)                                        Diretório de backup dos arquivo de saída.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*