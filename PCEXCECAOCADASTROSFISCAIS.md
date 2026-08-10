# 📊 Tabela: PCEXCECAOCADASTROSFISCAIS

### Estrutura de Colunas e Restrições

                   Tabela                   Coluna  Tipo/Tamanho                                                                                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXCECAOCADASTROSFISCAIS               CODEXCECAO   NUMBER(6,0)                                                                                                               Código identificador do registro(sequence)    CHAVE PRIMÁRIA (PK)                        NaN
PCEXCECAOCADASTROSFISCAIS                    TIPO1   VARCHAR2(2) Identificador do primeiro tipo de exceção(pode ser um ou um conjunto de caracteres, que a rotina que fizer o uso deste registro entenda seu significado)            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS                   VALOR1  VARCHAR2(10)                                                                                                                                Valor da primeira exceção            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS                    TIPO2   VARCHAR2(2)  Identificador do segundo tipo de exceção(pode ser um ou um conjunto de caracteres, que a rotina que fizer o uso deste registro entenda seu significado)            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS                   VALOR2  VARCHAR2(10)                                                                                                                                 Valor da segunda exceção            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS                    TIPO3   VARCHAR2(2) Identificador do terceiro tipo de exceção(pode ser um ou um conjunto de caracteres, que a rotina que fizer o uso deste registro entenda seu significado)            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS                   VALOR3  VARCHAR2(10)                                                                                                                                Valor da terceira exceção            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS                    TIPO4   VARCHAR2(2)   Identificador do quarto tipo de exceção(pode ser um ou um conjunto de caracteres, que a rotina que fizer o uso deste registro entenda seu significado)            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS                   VALOR4  VARCHAR2(10)                                                                                                                                  Valor da quarta exceção            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS         CODCADASTROPRINC  VARCHAR2(10)                                                                                                          Código do cadastro principal que possui exceção            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS       CODCADASTROEXCECAO  VARCHAR2(10)                                                             Código de exceção do cadastro, que será utilizado caso atenda as regras da exceção principal            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS                   ROTINA  VARCHAR2(20)                                                                                                               Rotina que pertence os registros da tabela            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS CODBENEFICIOFISCALCOMPLE VARCHAR2(100)                                                                                                                  Código de beneficio fiscal complementar            OPERACIONAL                        NaN
PCEXCECAOCADASTROSFISCAIS                DTALTERC5  TIMESTAMP(6)                                                                                                                                        Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*