# 📊 Tabela: PCDICIONARIOFKITEM

### Estrutura de Colunas e Restrições

            Tabela          Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDICIONARIOFKITEM   NOMEOBJETOPAI VARCHAR2(100)           Nome da tabela principal    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOFKITEM    NOMECAMPOPAI VARCHAR2(100)  Nome do campo da tabela principal    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOFKITEM NOMEOBJETOFILHO VARCHAR2(100)          Nome da tabela secundária    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOFKITEM  NOMECAMPOFILHO VARCHAR2(100) Nome do campo da tabela secundária    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOFKITEM      DTCADASTRO          DATE                   Data de cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*