# 📊 Tabela: PCLAYOUTIMPI

### Estrutura de Colunas e Restrições

      Tabela             Coluna  Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTIMPI       CODLAYOUTIMP  NUMBER(10,0)                                                           Campo para identificar os layouts.            OPERACIONAL                        NaN
PCLAYOUTIMPI              ORDEM   NUMBER(6,0)                                      Campo para armazenar a ordem da string a ser importada.            OPERACIONAL                        NaN
PCLAYOUTIMPI            TAMANHO   NUMBER(6,0)                                    Campo para armazenar o tamanho da string a ser importada.            OPERACIONAL                        NaN
PCLAYOUTIMPI             TABELA  VARCHAR2(40)                                       Campo para armazenar o nome da tabela a ser utilizada.            OPERACIONAL                        NaN
PCLAYOUTIMPI              CAMPO  VARCHAR2(40)                                        Campo para armazenar o nome do campo a ser utilizado.            OPERACIONAL                        NaN
PCLAYOUTIMPI IDENTIFICADORSECAO   VARCHAR2(5)                              Campo para armazenar o separador a ser utilizado na importação.            OPERACIONAL                        NaN
PCLAYOUTIMPI     MASCARALEITURA VARCHAR2(500)                                      Campo para máscara a ser utilizada na leitura do campo.            OPERACIONAL                        NaN
PCLAYOUTIMPI          TIPOVALOR   VARCHAR2(1)                              Campo para indicar o tipo do valor. D-Data, T-Texto e N-Número.            OPERACIONAL                        NaN
PCLAYOUTIMPI           CRITERIO          CLOB Campo para armazenar a expressão para ser utilizada como critério de importação do registro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*