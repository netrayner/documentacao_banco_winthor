# 📊 Tabela: PCDICIONARIOITEMROT

### Estrutura de Colunas e Restrições

             Tabela                  Coluna  Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDICIONARIOITEMROT               CODROTINA   NUMBER(4,0)                                                        Código da rotina    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOITEMROT               NOMECAMPO VARCHAR2(100)                                                           Nome do campo    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOITEMROT              NOMEOBJETO VARCHAR2(100)                                                          Nome da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOITEMROT                EDITAVEL       CHAR(1)                                                          Campo editável            OPERACIONAL                        NaN
PCDICIONARIOITEMROT                ORDEMCAD        NUMBER                                                   Ordenação no cadastro            OPERACIONAL                        NaN
PCDICIONARIOITEMROT                ORDEMPSQ        NUMBER                                                   Ordenação na pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROT             PSQAUXILIAR VARCHAR2(100) Pesquisa: campo de verificação para complementar a pesquisa de registro            OPERACIONAL                        NaN
PCDICIONARIOITEMROT                PSQCAMPO VARCHAR2(200)                    Pesquisa: Campo a serem exibidos na grid de pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROT               PSQFILTRO VARCHAR2(200)                          Pesquisa: Filtros aplicados na pesquisa, fixo.            OPERACIONAL                        NaN
PCDICIONARIOITEMROT     PSQRETORNODESCRICAO VARCHAR2(200)                                  Pesquisa: Descrição que será retornada            OPERACIONAL                        NaN
PCDICIONARIOITEMROT               PSQOBJETO VARCHAR2(100)                                       Pesquisa: Tabela base da pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROT                   SECAO VARCHAR2(200)                                             Seção ou agrupador de campo            OPERACIONAL                        NaN
PCDICIONARIOITEMROT            VALORDEFAULT  VARCHAR2(30)                                                  Valor default do campo            OPERACIONAL                        NaN
PCDICIONARIOITEMROT          USARNAPESQUISA       CHAR(1)                                               Campo vísivel na pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROT           EXIBIRRESPESQ       CHAR(1)                                  Campo vísivel no resultado da pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROT            CODROTINACAD   NUMBER(4,0)                    Código da rotina utilizada para cadastrar este campo            OPERACIONAL                        NaN
PCDICIONARIOITEMROT                 GERALOG       CHAR(1)                                              Se o campo gera log ou não            OPERACIONAL                        NaN
PCDICIONARIOITEMROT        PSQRETORNOCODIGO VARCHAR2(200)                         Pesquisa: Código que será retornado na pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROT    CODCONTROLE_EDITAVEL   NUMBER(6,0)                                                                     NaN            OPERACIONAL                        NaN
PCDICIONARIOITEMROT             OBRIGATORIO VARCHAR2(100)                                                       Campo obrigatório            OPERACIONAL                        NaN
PCDICIONARIOITEMROT                 VISIVEL VARCHAR2(100)                                               Campo vísivel no cadastro            OPERACIONAL                        NaN
PCDICIONARIOITEMROT              DTCADASTRO          DATE                                                        Data de cadastro            OPERACIONAL                        NaN
PCDICIONARIOITEMROT             EXECUTAACAO   NUMBER(2,0)                        Executação a ação parametrizada para este campo.            OPERACIONAL                        NaN
PCDICIONARIOITEMROT            PSQFILTRO131 VARCHAR2(500)                           CONTEM SCRIPT DE ACESSO A DADOS DA ROTINA 132            OPERACIONAL                        NaN
PCDICIONARIOITEMROT UTILIZACADASTRODINAMICO   VARCHAR2(1)           Define se utiliza o cadastro dinâmico ou a rotina de cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*