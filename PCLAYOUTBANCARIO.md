# 📊 Tabela: PCLAYOUTBANCARIO

### Estrutura de Colunas e Restrições

          Tabela           Coluna  Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTBANCARIO           CODIGO  NUMBER(10,0) Codigo do layout bancario    CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTBANCARIO             NOME VARCHAR2(100)               Nome Layout            OPERACIONAL                        NaN
PCLAYOUTBANCARIO          TAMANHO  NUMBER(10,0)            Tamanho Layout            OPERACIONAL                        NaN
PCLAYOUTBANCARIO             TIPO  VARCHAR2(10)               Tipo Layout            OPERACIONAL                        NaN
PCLAYOUTBANCARIO       FINALIDADE  VARCHAR2(20)         Finalidade Layout            OPERACIONAL                        NaN
PCLAYOUTBANCARIO           STATUS  VARCHAR2(15)             Status layout            OPERACIONAL                        NaN
PCLAYOUTBANCARIO CODIGO_ESTRUTURA  NUMBER(10,0)         Codigo Estrututra CHAVE ESTRANGEIRA (FK)          PCESTRUTURALAYOUT
PCLAYOUTBANCARIO    CONFIGURACOES          CLOB     Configuraçãoes Layout            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*