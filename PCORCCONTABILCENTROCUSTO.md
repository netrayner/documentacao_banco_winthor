# 📊 Tabela: PCORCCONTABILCENTROCUSTO

### Estrutura de Colunas e Restrições

                  Tabela            Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORCCONTABILCENTROCUSTO               ANO  NUMBER(4,0)                   Ano do orçamento    CHAVE PRIMÁRIA (PK)                        NaN
PCORCCONTABILCENTROCUSTO         CODFILIAL  VARCHAR2(2)      Código da filial do orçamento    CHAVE PRIMÁRIA (PK)                        NaN
PCORCCONTABILCENTROCUSTO    CODREDUZIDO_PC VARCHAR2(12)  Código reduzido da conta contabil    CHAVE PRIMÁRIA (PK)                        NaN
PCORCCONTABILCENTROCUSTO     CODPLANOCONTA  NUMBER(5,0)           Código da conta contabil    CHAVE PRIMÁRIA (PK)                        NaN
PCORCCONTABILCENTROCUSTO               MES  NUMBER(2,0)                      Mês do rateio    CHAVE PRIMÁRIA (PK)                        NaN
PCORCCONTABILCENTROCUSTO CODIGOCENTROCUSTO VARCHAR2(40) Código da conta de centro de custo    CHAVE PRIMÁRIA (PK)                        NaN
PCORCCONTABILCENTROCUSTO        PERCRATEIO  NUMBER(6,2)         Valor percentual do rateio            OPERACIONAL                        NaN
PCORCCONTABILCENTROCUSTO             VALOR NUMBER(14,2)                    Valor do rateio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*