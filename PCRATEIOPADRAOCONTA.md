# 📊 Tabela: PCRATEIOPADRAOCONTA

### Estrutura de Colunas e Restrições

             Tabela         Coluna   Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRATEIOPADRAOCONTA CODRATEIOCONTA   NUMBER(10,0)                 Código do rateio da conta    CHAVE PRIMÁRIA (PK)                        NaN
PCRATEIOPADRAOCONTA      DESCRICAO   VARCHAR2(80)              Descrição do rateio da conta            OPERACIONAL                        NaN
PCRATEIOPADRAOCONTA          ATIVO    VARCHAR2(1) Campo para destiguir se rateio está ativo            OPERACIONAL                        NaN
PCRATEIOPADRAOCONTA            OBS VARCHAR2(2000)                 Observação sobre o rateio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*