# 📊 Tabela: PCTRIBUTACAO_FILTRO_NCM

### Estrutura de Colunas e Restrições

                 Tabela            Coluna Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBUTACAO_FILTRO_NCM CODIGO_TRIBUTACAO NUMBER(10,0)          Código da tributação que vem da tabela PCTRIBUTACAO            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_NCM           EXCECAO  VARCHAR2(1) Define se o filtro se tata de uma exceção Sim (S) ou Não (N)            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_NCM               NCM VARCHAR2(15)                                     Informação do código ncm            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_NCM         DTCRIACAO         DATE                       Data de criação do registro na tabela.            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_NCM        DTULTALTER         DATE              Data da última alteração do registro na tabela.            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_NCM      DTINATIVACAO         DATE                              Data de inativação do registro.            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_NCM        DTEXCLUSAO         DATE                              Data de exclusão do lançamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*