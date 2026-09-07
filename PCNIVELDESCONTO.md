# 📊 Tabela: PCNIVELDESCONTO

### Estrutura de Colunas e Restrições

         Tabela             Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNIVELDESCONTO          CODFILIAL  VARCHAR2(2)                  Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCNIVELDESCONTO        PERCDESCRCA NUMBER(18,6)        Percentual de desconto RCA            OPERACIONAL                        NaN
PCNIVELDESCONTO PERCDESCSUPERVISOR NUMBER(18,6) Percentual de desconto Supervisor            OPERACIONAL                        NaN
PCNIVELDESCONTO    PERCDESCGERENTE NUMBER(18,6)    Percentual de desconto Gerente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*