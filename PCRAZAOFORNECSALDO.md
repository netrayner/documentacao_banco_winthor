# 📊 Tabela: PCRAZAOFORNECSALDO

### Estrutura de Colunas e Restrições

            Tabela         Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRAZAOFORNECSALDO            MES  NUMBER(2,0) Indica o mês gerador do razão auxiliar.    CHAVE PRIMÁRIA (PK)                        NaN
PCRAZAOFORNECSALDO            ANO  NUMBER(4,0) Indica o ano gerador do razão auxiliar.    CHAVE PRIMÁRIA (PK)                        NaN
PCRAZAOFORNECSALDO      CODFORNEC  NUMBER(6,0)          Indica o código do fornecedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCRAZAOFORNECSALDO VLSALDOINICIAL NUMBER(18,2)         Indica o valordo saldo inicial.            OPERACIONAL                        NaN
PCRAZAOFORNECSALDO     FORNECEDOR VARCHAR2(60)            Indica o nome do fornecedor.            OPERACIONAL                        NaN
PCRAZAOFORNECSALDO      CODFILIAL  VARCHAR2(2)              Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*