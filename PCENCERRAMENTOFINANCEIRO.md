# 📊 Tabela: PCENCERRAMENTOFINANCEIRO

### Estrutura de Colunas e Restrições

                  Tabela    Coluna  Tipo/Tamanho   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCENCERRAMENTOFINANCEIRO CODFILIAL   VARCHAR2(2)      Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCENCERRAMENTOFINANCEIRO       ANO   NUMBER(4,0)       Ano do bloqueio    CHAVE PRIMÁRIA (PK)                        NaN
PCENCERRAMENTOFINANCEIRO       MES   NUMBER(2,0)       Mês do bloqueio    CHAVE PRIMÁRIA (PK)                        NaN
PCENCERRAMENTOFINANCEIRO       DIA   NUMBER(2,0)       Dia do bloqueio    CHAVE PRIMÁRIA (PK)                        NaN
PCENCERRAMENTOFINANCEIRO HISTORICO VARCHAR2(200) Histórico do bloqueio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*