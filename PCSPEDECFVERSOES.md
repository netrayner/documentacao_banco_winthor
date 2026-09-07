# 📊 Tabela: PCSPEDECFVERSOES

### Estrutura de Colunas e Restrições

          Tabela   Coluna Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFVERSOES REGISTRO VARCHAR2(10)    Registro do SPED ECF que pertence esta conta, como "M300", "M350", "N600"    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFVERSOES   VERSAO       NUMBER                      Versão do plano conforme os arquivos da Receita Federal    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFVERSOES    REGRA      CHAR(1) Indica se é regra ou plano do PAV da Receita Federal: S = regra ou N = plano    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFVERSOES DTVERSAO         DATE                           Data de cadastro da versão do registro do SPED ECF            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*