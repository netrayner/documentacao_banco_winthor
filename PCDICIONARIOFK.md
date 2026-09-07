# 📊 Tabela: PCDICIONARIOFK

### Estrutura de Colunas e Restrições

        Tabela          Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDICIONARIOFK   NOMEOBJETOPAI VARCHAR2(100)                     Nome da tabela principal    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOFK NOMEOBJETOFILHO VARCHAR2(100)                    Nome da tabela secundária    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOFK DESCRICAOFILTRO VARCHAR2(100) Descrição da categoria na montagem do filtro            OPERACIONAL                        NaN
PCDICIONARIOFK    CODROTINACAD   NUMBER(4,0)                           Código de cadastro            OPERACIONAL                        NaN
PCDICIONARIOFK      DTCADASTRO          DATE                             Data de cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*