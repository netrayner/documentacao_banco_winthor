# 📊 Tabela: PCORCLANCENTROCUSTO

### Estrutura de Colunas e Restrições

             Tabela            Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORCLANCENTROCUSTO               ANO  NUMBER(4,0)                  Ano do orçamento do centro de custo.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCLANCENTROCUSTO               MES  NUMBER(2,0)                  Mês do orçamento do centro de custo.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCLANCENTROCUSTO         CODFILIAL  VARCHAR2(2)     Código da filial do orçamento do centro de custo.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCLANCENTROCUSTO          CODCONTA NUMBER(10,0)      Código da conta do orçamento do centro de custo.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCLANCENTROCUSTO CODIGOCENTROCUSTO VARCHAR2(40)               Código do centro de custo do orçamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCLANCENTROCUSTO             VALOR NUMBER(14,2)                Valor do orçamento do centro de custo.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCLANCENTROCUSTO        PERCRATEIO NUMBER(18,6) Percentual do rateio do orçamento do centro de custo.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*