# 📊 Tabela: PCORCAMENTOCONTABIL

### Estrutura de Colunas e Restrições

             Tabela         Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORCAMENTOCONTABIL            ANO  NUMBER(4,0)                  Ano do orçamento    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAMENTOCONTABIL      CODFILIAL  VARCHAR2(2)     Código da filial do orçamento    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAMENTOCONTABIL CODREDUZIDO_PC VARCHAR2(12) Código reduzido da conta contabil    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAMENTOCONTABIL  CODPLANOCONTA  NUMBER(5,0)          Código da conta contabil    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAMENTOCONTABIL    VLRORCMES01 NUMBER(14,2)       Valor orçado mês de Janeiro            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES02 NUMBER(14,2)     Valor orçado mês de Fevereiro            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES03 NUMBER(14,2)         Valor orçado mês de Março            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES04 NUMBER(14,2)         Valor orçado mês de Abril            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES05 NUMBER(14,2)          Valor orçado mês de Maio            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES06 NUMBER(14,2)         Valor orçado mês de Junho            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES07 NUMBER(14,2)         Valor orçado mês de Julho            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES08 NUMBER(14,2)        Valor orçado mês de Agosto            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES09 NUMBER(14,2)      Valor orçado mês de Setembro            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES10 NUMBER(14,2)       Valor orçado mês de Outubro            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES11 NUMBER(14,2)      Valor orçado mês de Novembro            OPERACIONAL                        NaN
PCORCAMENTOCONTABIL    VLRORCMES12 NUMBER(14,2)      Valor orçado mês de Dezembro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*