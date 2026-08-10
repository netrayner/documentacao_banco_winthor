# 📊 Tabela: PCACERTOMANIF

### Estrutura de Colunas e Restrições

       Tabela          Coluna Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCACERTOMANIF         CODPROD  NUMBER(6,0)                  Defiine o Código do Produto do Acerto            OPERACIONAL                        NaN
PCACERTOMANIF            QT13 NUMBER(20,6)          Define a quantidade do produto do pedido TV13            OPERACIONAL                        NaN
PCACERTOMANIF            QT14 NUMBER(20,6)          Define a quantidade do produto do pedido TV14            OPERACIONAL                        NaN
PCACERTOMANIF     QTDERRUBADO NUMBER(20,6)             Define a quantidade derrubada na devolução            OPERACIONAL                        NaN
PCACERTOMANIF        QTAVARIA NUMBER(20,6)              Define a quantidade avariada na devolução            OPERACIONAL                        NaN
PCACERTOMANIF QTSEPARADAMANIF NUMBER(20,6)              Define a quantidade separada do Manifesto            OPERACIONAL                        NaN
PCACERTOMANIF          NUMCAR  NUMBER(8,0)                        Define o número do Carregamento            OPERACIONAL                        NaN
PCACERTOMANIF           PUNIT NUMBER(18,6)                     Define o preço unitário do Produto            OPERACIONAL                        NaN
PCACERTOMANIF     CODFUNCLANC  NUMBER(8,0) Define o código do funcionário responsável pelo acerto            OPERACIONAL                        NaN
PCACERTOMANIF            DATA         DATE                                Define a data do Acerto            OPERACIONAL                        NaN
PCACERTOMANIF       CODFILIAL  VARCHAR2(2)                              Define o código da Filial            OPERACIONAL                        NaN
PCACERTOMANIF       VALORVALE NUMBER(18,6)                      Define o valor do vale para o RCA            OPERACIONAL                        NaN
PCACERTOMANIF   DERRUBOUCARGA  VARCHAR2(1)                   Define se derrubou carga(Sim ou Não)            OPERACIONAL                        NaN
PCACERTOMANIF     QTDEVOLVIDA NUMBER(20,6)                          Define a quantidade devolvida            OPERACIONAL                        NaN
PCACERTOMANIF         FECHADA  VARCHAR2(1)                      Define se o acerto já foi fechado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*