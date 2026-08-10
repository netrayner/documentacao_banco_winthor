# 📊 Tabela: PCDICIONARIO

### Estrutura de Colunas e Restrições

      Tabela              Coluna   Tipo/Tamanho                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDICIONARIO          NOMEOBJETO  VARCHAR2(100)                                                                                                      Nome da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIO           DESCRICAO  VARCHAR2(150)                                                                                                 Descrição da tabela            OPERACIONAL                        NaN
PCDICIONARIO SQLOBTEMREGEXCLUIDO  VARCHAR2(100) SQL usado na pesquisa para obter os registros excluídos. Se vazio indica que os registros são excluídos fisicamente            OPERACIONAL                        NaN
PCDICIONARIO      DATALANCAMENTO           DATE                                                                                                                 NaN            OPERACIONAL                        NaN
PCDICIONARIO         SQLEXCLUSAO VARCHAR2(1000)                                                                                                                 NaN            OPERACIONAL                        NaN
PCDICIONARIO          DTCADASTRO           DATE                                                                                                    Data de cadastro            OPERACIONAL                        NaN
PCDICIONARIO   SQLOBTEMACESSO131  VARCHAR2(500)                                                                       CONTEM SCRIPT DE ACESSO A DADOS DA ROTINA 131            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*