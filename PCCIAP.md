# 📊 Tabela: PCCIAP

### Estrutura de Colunas e Restrições

Tabela             Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCIAP          CODFILIAL  VARCHAR2(2)      Cód.Filial da apuração.    CHAVE PRIMÁRIA (PK)                        NaN
PCCIAP                MES  NUMBER(2,0)             Mes de apuração.    CHAVE PRIMÁRIA (PK)                        NaN
PCCIAP                ANO  NUMBER(4,0)             Ano de Apuração.    CHAVE PRIMÁRIA (PK)                        NaN
PCCIAP VLSAIDASTRIBUTADAS NUMBER(16,2) Total das saídas tributadas.            OPERACIONAL                        NaN
PCCIAP      VLTOTALSAIDAS NUMBER(16,2)            Total das saidas.            OPERACIONAL                        NaN
PCCIAP          VLCREDITO NUMBER(16,2)            Valor do crédito.            OPERACIONAL                        NaN
PCCIAP      VLBASECREDITO NUMBER(16,2)     Valor base para calculo.            OPERACIONAL                        NaN
PCCIAP            APURADO  VARCHAR2(1)       Indica se foi apurado.            OPERACIONAL                        NaN
PCCIAP             FRACAO  VARCHAR2(6)             Valor da Fração.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*