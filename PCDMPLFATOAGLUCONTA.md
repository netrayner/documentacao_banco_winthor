# 📊 Tabela: PCDMPLFATOAGLUCONTA

### Estrutura de Colunas e Restrições

             Tabela             Coluna  Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDMPLFATOAGLUCONTA NUMFATOAGLUTINACAO  NUMBER(20,0) Sequencial Combinação Fato Contábil x Aglutinação    CHAVE PRIMÁRIA (PK)      PCDMPLFATOAGLUTINACAO
PCDMPLFATOAGLUCONTA     CODREDUZIDO_PC  VARCHAR2(12)                                      Código Conta    CHAVE PRIMÁRIA (PK)                        NaN
PCDMPLFATOAGLUCONTA          DESCRICAO VARCHAR2(100)                                         Descrição            OPERACIONAL                        NaN
PCDMPLFATOAGLUCONTA       NATUREZALANC   VARCHAR2(1)                               Natureza Lançamento            OPERACIONAL                        NaN
PCDMPLFATOAGLUCONTA              VALOR  NUMBER(18,2)                               Valor do lançamento            OPERACIONAL                        NaN
PCDMPLFATOAGLUCONTA                MES   NUMBER(2,0)                    Mês onde ocorreu o lançamento.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*