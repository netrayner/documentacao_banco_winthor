# 📊 Tabela: PCTRIBUTACAO_FILTRO_PRODUTO

### Estrutura de Colunas e Restrições

                     Tabela            Coluna Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBUTACAO_FILTRO_PRODUTO CODIGO_TRIBUTACAO NUMBER(10,0)          Código da tributação que vem da tabela PCTRIBUTACAO            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_PRODUTO           EXCECAO  VARCHAR2(1) Define se o filtro se tata de uma exceção Sim (S) ou Não (N)            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_PRODUTO           CODPROD  NUMBER(6,0)               Responsável por armazenar o código do produto             OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_PRODUTO         DTCRIACAO         DATE                       Data de criação do registro na tabela.            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_PRODUTO        DTULTALTER         DATE              Data da última alteração do registro na tabela.            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_PRODUTO      DTINATIVACAO         DATE                              Data de inativação do registro.            OPERACIONAL                        NaN
PCTRIBUTACAO_FILTRO_PRODUTO        DTEXCLUSAO         DATE                              Data de exclusão do lançamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*