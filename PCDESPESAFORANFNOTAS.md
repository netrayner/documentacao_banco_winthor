# 📊 Tabela: PCDESPESAFORANFNOTAS

### Estrutura de Colunas e Restrições

              Tabela      Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESPESAFORANFNOTAS  CODDESPESA  NUMBER(8,0)                               Código da despesa    CHAVE PRIMÁRIA (PK)            PCDESPESAFORANF
PCDESPESAFORANFNOTAS     NUMNOTA NUMBER(10,0)                       Numero da nota de entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCDESPESAFORANFNOTAS       SERIE  VARCHAR2(3)                        Serie da nota de entrada            OPERACIONAL                        NaN
PCDESPESAFORANFNOTAS CODFORNECNF  NUMBER(8,0)         Código do fornecedor da nota de entrada            OPERACIONAL                        NaN
PCDESPESAFORANFNOTAS   VLTOTALNF NUMBER(18,6)                  Valor total da nota de entrada            OPERACIONAL                        NaN
PCDESPESAFORANFNOTAS PESOTOTALNF NUMBER(18,6)                   Peso total da nota de entrada            OPERACIONAL                        NaN
PCDESPESAFORANFNOTAS PERCDESPESA NUMBER(18,4) Percentual da despesa a ser distribuida na nota            OPERACIONAL                        NaN
PCDESPESAFORANFNOTAS   VLDESPESA NUMBER(18,6)      Valor da despesa a ser distribuida na nota            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*