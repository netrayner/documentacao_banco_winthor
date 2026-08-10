# 📊 Tabela: PCANALISEPDV

### Estrutura de Colunas e Restrições

      Tabela                  Coluna Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCANALISEPDV                  NUMSEQ NUMBER(10,0)                                                                         NÚMERO DE SEQUÊNCIA.    CHAVE PRIMÁRIA (PK)                        NaN
PCANALISEPDV                    DATA         DATE                                                                            DATA DE GRAVACAO.    CHAVE PRIMÁRIA (PK)                        NaN
PCANALISEPDV               CODFILIAL  VARCHAR2(2)                                                                               CÓDIGO FILIAL.    CHAVE PRIMÁRIA (PK)                        NaN
PCANALISEPDV                NUMCAIXA  NUMBER(4,0)                                                                             NÚMERO DO CAIXA.    CHAVE PRIMÁRIA (PK)                        NaN
PCANALISEPDV            CODFUNCCAIXA  NUMBER(8,0)                                                                      CÓDIGO DO FUNCIONÁRIO .    CHAVE PRIMÁRIA (PK)                        NaN
PCANALISEPDV           CODFUNCSUPERV  NUMBER(8,0)                                                                        CÓDIGO DO SUPERVISOR.            OPERACIONAL                        NaN
PCANALISEPDV           NUMSEQENTRADA NUMBER(10,0)                                                                 NÚMERO DE SEQUÊNCIA ENTRADA.            OPERACIONAL                        NaN
PCANALISEPDV          GTVENDAINICIAL NUMBER(16,2)                                                                         GT INICIAL DA VENDA.            OPERACIONAL                        NaN
PCANALISEPDV            GTVENDAFINAL NUMBER(16,2)                                                                           GT FINAL DA VENDA.            OPERACIONAL                        NaN
PCANALISEPDV         GTCANCELINICIAL NUMBER(16,2)                                                                  GT INICIAL DO CANCELAMENTO.            OPERACIONAL                        NaN
PCANALISEPDV           GTCANCELFINAL NUMBER(16,2)                                                                    GT FINAL DO CANCELAMENTO.            OPERACIONAL                        NaN
PCANALISEPDV           GTDESCINICIAL NUMBER(16,2)                                                                      GT INICIAL DO DESCONTO.            OPERACIONAL                        NaN
PCANALISEPDV             GTDESCFINAL NUMBER(16,2)                                                                        GT FINAL DO DESCONTO.            OPERACIONAL                        NaN
PCANALISEPDV             DTHRENTRADA         DATE                                                                      DATA E HORA DA ENTRADA.            OPERACIONAL                        NaN
PCANALISEPDV               DTHRSAIDA         DATE                                                                        DATA E HORA DA SAÍDA.            OPERACIONAL                        NaN
PCANALISEPDV          QTDETEMPOPAUSA NUMBER(10,0)                                                                   QTDE DE PAUSA DO OPERADOR.            OPERACIONAL                        NaN
PCANALISEPDV      QTDETEMPOVENDAITEM NUMBER(10,0)                                                                    QTDE DE TEMPO VENDA ITEM.            OPERACIONAL                        NaN
PCANALISEPDV     QTDETEMPOTOTALVENDA NUMBER(10,0)                                                                QTDE DE TEMPO TOTAL DE VENDA.            OPERACIONAL                        NaN
PCANALISEPDV            QTDECLIENTES NUMBER(10,0)                                                                            QTDE DE CLIENTES.            OPERACIONAL                        NaN
PCANALISEPDV           QTDEITEMVENDA NUMBER(13,3)                                                                       QTDE DE ITEM NA VENDA.            OPERACIONAL                        NaN
PCANALISEPDV  QTDEITEMVENDADIFERENCA NUMBER(13,3)                                                        QTDE DE DIFERENÇA NOS ITENS DA VENDA.            OPERACIONAL                        NaN
PCANALISEPDV              VALORVENDA NUMBER(13,2)                                                                              VALOR DA VENDA.            OPERACIONAL                        NaN
PCANALISEPDV     VALORVENDADIFERENCA NUMBER(13,2)                                                                 VALOR DE DIFERENCA NA VENDA.            OPERACIONAL                        NaN
PCANALISEPDV   VALORFINALIZDIFERENCA NUMBER(13,2)                                                          VALOR DE DIFERENCA NA FINALIZADORA.            OPERACIONAL                        NaN
PCANALISEPDV          QTDEITEMCANCEL NUMBER(13,3)                                                                      QTDE DE ITEM CANCELADO.            OPERACIONAL                        NaN
PCANALISEPDV             VALORCANCEL NUMBER(16,3)                                                                       VALOR DO CANCELAMENTO.            OPERACIONAL                        NaN
PCANALISEPDV               VALORDESC NUMBER(13,2)                                                                           VALOR DE DESCONTO.            OPERACIONAL                        NaN
PCANALISEPDV            VALORENCARGO NUMBER(13,2)                                                                            VALOR DE ENCARGO.            OPERACIONAL                        NaN
PCANALISEPDV             QTDESANGRIA  NUMBER(5,0)                                                                             QTDE DA SANGRIA.            OPERACIONAL                        NaN
PCANALISEPDV            VALORSANGRIA NUMBER(13,2)                                                                            VALOR DA SANGRIA.            OPERACIONAL                        NaN
PCANALISEPDV        VALORSANGRIAAUTO NUMBER(13,2)                                                                    VALOR SANGRIA AUTOMATICO.            OPERACIONAL                        NaN
PCANALISEPDV   VALORSANGRIADIFERENCA NUMBER(13,2)                                                                  VALOR DIFERENCA NA SANGRIA.            OPERACIONAL                        NaN
PCANALISEPDV  QTDESANGRIARECEBTOBANC NUMBER(10,0)                                                           QTDE SANGRIA RECEBIMENTO BANCARIO.            OPERACIONAL                        NaN
PCANALISEPDV VALORSANGRIARECEBTOBANC NUMBER(13,2)                                                          VALOR SANGRIA RECEBIMENTO BANCARIO.            OPERACIONAL                        NaN
PCANALISEPDV   VALORENTRADANUMERARIO NUMBER(13,2)                                                                  VALOR DE RETIRADA DO CAIXA.            OPERACIONAL                        NaN
PCANALISEPDV         QTDELINHASCUPOM NUMBER(10,0)                                                                      QTDE DE LINHA NO CUPOM.            OPERACIONAL                        NaN
PCANALISEPDV     QTDEVOLUMESPRODUTOS NUMBER(10,0)                                                                 QTDE DE VOLUMES DE PRODUTOS.            OPERACIONAL                        NaN
PCANALISEPDV      QTDEABERTURAGAVETA  NUMBER(5,0)                                                              QTDE VEZES QUE ABRIU A GAVETA .            OPERACIONAL                        NaN
PCANALISEPDV        QTDECUPONSCANCEL NUMBER(10,0)                                                                   QTDE DE CUPONS CANCELADOS.            OPERACIONAL                        NaN
PCANALISEPDV         VALORFUNDOTROCO NUMBER(13,2)                                                                     VALOR DE FUNDO DE CAIXA.            OPERACIONAL                        NaN
PCANALISEPDV    QTDETEMPOCAIXAABERTO NUMBER(10,0)                                                      Tempo total em que o caixa ficou aberto            OPERACIONAL                        NaN
PCANALISEPDV        QTDETEMPOINATIVO NUMBER(10,0)                                                     Tempo total em que o caixa ficou inativo            OPERACIONAL                        NaN
PCANALISEPDV          QTDESUPRIMENTO  NUMBER(5,0)                Quantidade de suprimentos realizados durante o tempo que o caixa ficou aberto            OPERACIONAL                        NaN
PCANALISEPDV         VALORSUPRIMENTO NUMBER(13,2) Valor total dos suprimentos que foram realizados durante o tempo em que o caixa ficou aberto            OPERACIONAL                        NaN
PCANALISEPDV               HRINICIAL  VARCHAR2(8)                                                                         Hora inicial análise            OPERACIONAL                        NaN
PCANALISEPDV                 HRFINAL  VARCHAR2(8)                                                                           Hora final análise            OPERACIONAL                        NaN
PCANALISEPDV               EXPORTADO  VARCHAR2(1)                                                       Identifica se o registro foi exportado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*