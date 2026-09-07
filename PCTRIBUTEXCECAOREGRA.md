# 📊 Tabela: PCTRIBUTEXCECAOREGRA

### Estrutura de Colunas e Restrições

              Tabela        Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBUTEXCECAOREGRA      CODREGRA  NUMBER(6,0)                            Código da regra de exceção    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTEXCECAOREGRA          TIPO  VARCHAR2(2)          Tipo do objeto a ser validado para a exceção    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTEXCECAOREGRA       CODIGON  NUMBER(6,0)     Código do objeto a ser validado, quando numérico.            OPERACIONAL                        NaN
PCTRIBUTEXCECAOREGRA       CODIGOA  VARCHAR2(6) Código do objeto a ser validado, quando Alfanumérico.    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTEXCECAOREGRA    DTCADASTRO         DATE                                      Data de cadastro            OPERACIONAL                        NaN
PCTRIBUTEXCECAOREGRA CODUSUARIOINC  NUMBER(8,0)                        Código o usuário que cadastrou            OPERACIONAL                        NaN
PCTRIBUTEXCECAOREGRA   DTALTERACAO         DATE                                     Data de alteração            OPERACIONAL                        NaN
PCTRIBUTEXCECAOREGRA CODUSUARIOALT  NUMBER(8,0)                         Código do usuário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*