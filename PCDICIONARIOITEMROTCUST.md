# 📊 Tabela: PCDICIONARIOITEMROTCUST

### Estrutura de Colunas e Restrições

                 Tabela               Coluna  Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDICIONARIOITEMROTCUST            CODROTINA   NUMBER(4,0)                                                Nome do campo    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOITEMROTCUST            NOMECAMPO VARCHAR2(100)                                               Nome da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOITEMROTCUST           NOMEOBJETO VARCHAR2(100)                                               Campo editável    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOITEMROTCUST             EDITAVEL       CHAR(1)                                            Campo obrigatório            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST          OBRIGATORIO       CHAR(1)                                             Máscara do campo            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST              MASCARA  VARCHAR2(30)                                        Ordenação no cadastro            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST             ORDEMCAD        NUMBER                                        Ordenação na pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST             ORDEMPSQ        NUMBER                                          Visível na pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST       USARNAPESQUISA       CHAR(1)                             Visível no resultado da pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST        EXIBIRRESPESQ       CHAR(1)         Pesquisa: Campo complementar a pesquisa de registros            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST          PSQAUXILIAR VARCHAR2(100)       Pesquisa: Campos que serão exibido no grid da pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST             PSQCAMPO VARCHAR2(200)                            Pesquisa: Filtro fixo da pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST            PSQFILTRO VARCHAR2(200)      Pesquisa: Descrição de retorno do resultado da pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST  PSQRETORNODESCRICAO VARCHAR2(200)                            Pesquisa: Tabela base da pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST            PSQOBJETO VARCHAR2(100)                                 Seção ou agrupador de campos            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST                SECAO VARCHAR2(200)                                    Valor default do registro            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST         VALORDEFAULT  VARCHAR2(30)                                          Vísivel no cadastro            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST              VISIVEL       CHAR(1)                  Código da rotina que da manutenção no campo            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST         CODROTINACAD   NUMBER(4,0)                      Se o campo gera ou não log de alteração            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST              GERALOG       CHAR(1) Formatação do campo: U: Caixa alta, N: Livre, L: Caixa baixa            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST             CHARCASE       CHAR(1)         Pesquisa: Código de retorno do resultado da pesquisa            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST     PSQRETORNOCODIGO VARCHAR2(200)                                               Ajuda do campo            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST                AJUDA VARCHAR2(255)                                                          NaN            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST          EXECUTAACAO   NUMBER(2,0)             Executação a ação parametrizada para este campo.            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST           DTCADASTRO          DATE                                             Data de Cadastro            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST CODCONTROLE_EDITAVEL   NUMBER(6,0)                                                          NaN            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST  PSQRETIRACARACTERES       CHAR(1)                                                          NaN            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST            AUTOGERAR VARCHAR2(150)                                   Descricao coluna AUTOGERAR            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST         CRIPTOGRAFAR   VARCHAR2(1)                            Criptografar informação no banco.            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST         PSQFILTRO131 VARCHAR2(500)                CONTEM SCRIPT DE ACESSO A DADOS DA ROTINA 133            OPERACIONAL                        NaN
PCDICIONARIOITEMROTCUST            CODROTULO  VARCHAR2(40)                                             Código do Rótulo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*