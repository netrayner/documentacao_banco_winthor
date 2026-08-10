# 📊 Tabela: PCDICIONARIOCHECKLIST

### Estrutura de Colunas e Restrições

               Tabela        Coluna  Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDICIONARIOCHECKLIST  CODCHECKLIST   NUMBER(6,0)                                          Código do checklist    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOCHECKLIST    NOMEOBJETO VARCHAR2(100)                         Nome da tabela relacionada ao rótulo    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOCHECKLIST     SEQUENCIA   NUMBER(6,0)                           Sequência de execução do checklist            OPERACIONAL                        NaN
PCDICIONARIOCHECKLIST        TITULO VARCHAR2(150)                                          Título do checklist            OPERACIONAL                        NaN
PCDICIONARIOCHECKLIST  CODROTINACAD   NUMBER(4,0) Código da rotina de necessário para complementar o checklist            OPERACIONAL                        NaN
PCDICIONARIOCHECKLIST PROCESSAMENTO   VARCHAR2(1)                   Informar se o checklist e de processamento            OPERACIONAL                        NaN
PCDICIONARIOCHECKLIST         ATIVO   VARCHAR2(1)                           Informar se o checklist esta ativo            OPERACIONAL                        NaN
PCDICIONARIOCHECKLIST  SQLVALIDACAO          CLOB                                          Script de validação            OPERACIONAL                        NaN
PCDICIONARIOCHECKLIST    SQLGERACAO          CLOB                              Script de geração de informação            OPERACIONAL                        NaN
PCDICIONARIOCHECKLIST    DTCADASTRO          DATE                                Data de cadastro do checklist            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*