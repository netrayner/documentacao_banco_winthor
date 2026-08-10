# 📊 Tabela: PCCOMISSAOMOT

### Estrutura de Colunas e Restrições

       Tabela            Coluna Tipo/Tamanho                                                                                                                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSAOMOT          CODFAIXA  NUMBER(8,0)                         Número sequencial gerado automaticamente para identificar unicamente as faixas. |Campo do tipo numérico, de tamanho 8, sem casas decimais, obrigatória.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAOMOT              TIPO  VARCHAR2(2)                                                                            Identifica se a faixa será por Valor ou Peso do carregamento. |Campo do tipo caracter, de tamanho 2.            OPERACIONAL                        NaN
PCCOMISSAOMOT      FAIXAINICIAL NUMBER(18,6) Faixa inicial para indicar qual o percentual será usadono cálculo da comissão do motorista, freteiro ou ajudante. |Campo do tipo numérico, de tamanho 18, com 6 casas decimais.            OPERACIONAL                        NaN
PCCOMISSAOMOT        FAIXAFINAL NUMBER(18,6)   Faixa final para indicar qual o percentual será usadono cálculo da comissão do motorista, freteiro ou ajudante. |Campo do tipo numérico, de tamanho 18, com 6 casas decimais.            OPERACIONAL                        NaN
PCCOMISSAOMOT           PERCMOT  NUMBER(6,2)                        Percentual de comissão, por faixa, a ser aplicado  no cálculo da comissão para o motorista. |Campo do tipo numérico, de tamanho 6, com 2 casas decimais.            OPERACIONAL                        NaN
PCCOMISSAOMOT          PERCTERC  NUMBER(6,2)               Percentual de comissão, por faixa, a ser aplicado  no cálculo da comissão para o motorista freteiro. |Campo do tipo numérico, de tamanho 6, com 2 casas decimais.            OPERACIONAL                        NaN
PCCOMISSAOMOT          PERCAJUD  NUMBER(6,2)                         Percentual de comissão, por faixa, a ser aplicado  no cálculo da comissão para o ajudante. |Campo do tipo numérico, de tamanho 6, com 2 casas decimais.            OPERACIONAL                        NaN
PCCOMISSAOMOT  PERMOTTRANSBORDO  NUMBER(8,2)                                                                                                                              Indica o percentual comissão motorista transbordo.            OPERACIONAL                        NaN
PCCOMISSAOMOT PERAJUDTRANSBORDO  NUMBER(8,2)                                                                                                                                Indica o percentual comissão motorista ajudante.            OPERACIONAL                        NaN
PCCOMISSAOMOT         PERCAJUD2  NUMBER(6,2)                                                                                                                                            Percentual de comissão do ajudante 2            OPERACIONAL                        NaN
PCCOMISSAOMOT         PERCAJUD3  NUMBER(6,2)                                                                                                                                            Percentual de comissão do ajudante 3            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*