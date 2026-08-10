# 📊 Tabela: PCLOGCADASTRO

### Estrutura de Colunas e Restrições

       Tabela           Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCADASTRO VERSAOAPLICATIVO  VARCHAR2(15)      Versão do aplicativo utilizado na ação            OPERACIONAL                        NaN
PCLOGCADASTRO          ESTACAO  VARCHAR2(50)                   Estação utilizada na ação            OPERACIONAL                        NaN
PCLOGCADASTRO      USUARIOREDE  VARCHAR2(50)              Nome do usuário de rede logado            OPERACIONAL                        NaN
PCLOGCADASTRO       NOMEOBJETO VARCHAR2(130)              Tabela do registros modificado            OPERACIONAL                        NaN
PCLOGCADASTRO             ACAO       CHAR(1) Ação realizada: A - Alteração, X - Exclusão            OPERACIONAL                        NaN
PCLOGCADASTRO       ROWIDCAMPO  VARCHAR2(30)                  Rowid do registro alterado            OPERACIONAL                        NaN
PCLOGCADASTRO         VALOROLD          CLOB             Valor anterior a ação realizada            OPERACIONAL                        NaN
PCLOGCADASTRO MATRICULAUSUARIO  NUMBER(22,0)  Matricula do usuário responsável pela ação            OPERACIONAL                        NaN
PCLOGCADASTRO    NOMEAPLICACAO  VARCHAR2(30)                    Rotina utilizada na ação            OPERACIONAL                        NaN
PCLOGCADASTRO          DATALOG          DATE                      Data de geração do Log            OPERACIONAL                        NaN
PCLOGCADASTRO        CODROTINA  NUMBER(22,0)                            Código da rotina            OPERACIONAL                        NaN
PCLOGCADASTRO         VALORNEW          CLOB        Valor atual da alteração no cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*