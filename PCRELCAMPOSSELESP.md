# 📊 Tabela: PCRELCAMPOSSELESP

### Estrutura de Colunas e Restrições

           Tabela       Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRELCAMPOSSELESP CODRELATORIO   NUMBER(4,0)                         CÓDIGO DO RELATORIO            OPERACIONAL                        NaN
PCRELCAMPOSSELESP     CODCAMPO   NUMBER(6,0)                             CÓDIGO DO CAMPO    CHAVE PRIMÁRIA (PK)                        NaN
PCRELCAMPOSSELESP    NOMECAMPO VARCHAR2(100)                     NOME DO CAMPO DA TABELA            OPERACIONAL                        NaN
PCRELCAMPOSSELESP       FUNCAO   VARCHAR2(5)            FUNÇÃO DE AGRUPAMENTO DOS CAMPOS            OPERACIONAL                        NaN
PCRELCAMPOSSELESP        ORDEM   NUMBER(4,0) ORDEM DOS CAMPOS QUE IRÃO SAIR NO RELATORIO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*