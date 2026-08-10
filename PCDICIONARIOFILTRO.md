# 📊 Tabela: PCDICIONARIOFILTRO

### Estrutura de Colunas e Restrições

            Tabela          Coluna  Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDICIONARIOFILTRO       CODROTINA  NUMBER(22,0)    Código da rotina que utiliza o filtro            OPERACIONAL                        NaN
PCDICIONARIOFILTRO   NOMEOBJETOPAI VARCHAR2(100)                       Nome da tabela pai    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOFILTRO NOMEOBJETOFILHO VARCHAR2(100)                     Nome da tabela filho    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOFILTRO  NOMECAMPOFILHO VARCHAR2(100) Nome do campo filho utilizando no filtro    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOFILTRO      DTCADASTRO          DATE                         Data de cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*