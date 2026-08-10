# 📊 Tabela: PCTRIBUTEXCECAO

### Estrutura de Colunas e Restrições

         Tabela          Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBUTEXCECAO           CODST   NUMBER(4,0)               Código da tributação de origem    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTEXCECAO    CODSTEXCECAO   NUMBER(4,0)              Código da tributação da exceção    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTEXCECAO        CODREGRA   NUMBER(6,0)                   Código da regra de exceção    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTEXCECAO      DTCADASTRO          DATE                             Data de cadastro            OPERACIONAL                        NaN
PCTRIBUTEXCECAO   CODUSUARIOINC   NUMBER(8,0)               Código o usuário que cadastrou            OPERACIONAL                        NaN
PCTRIBUTEXCECAO     DTALTERACAO          DATE                            Data de alteração            OPERACIONAL                        NaN
PCTRIBUTEXCECAO   CODUSUARIOALT   NUMBER(8,0)                Código do usuário que alterou            OPERACIONAL                        NaN
PCTRIBUTEXCECAO       DESCRICAO VARCHAR2(400)                         Descrição da Exceção            OPERACIONAL                        NaN
PCTRIBUTEXCECAO ORDEMPRIORIDADE   NUMBER(4,0) Ordem de Prioridade de Aplicação da Exceção             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*