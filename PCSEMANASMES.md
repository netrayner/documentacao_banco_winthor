# 📊 Tabela: PCSEMANASMES

### Estrutura de Colunas e Restrições

      Tabela     Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSEMANASMES  NUMSEMANA  NUMBER(1,0)      Indica o número da semana.    CHAVE PRIMÁRIA (PK)                        NaN
PCSEMANASMES        MES  NUMBER(2,0)                   Indica o mês.    CHAVE PRIMÁRIA (PK)                        NaN
PCSEMANASMES        ANO  NUMBER(4,0)                   Indica o ano.    CHAVE PRIMÁRIA (PK)                        NaN
PCSEMANASMES DIAINICIAL  NUMBER(2,0) Indica o dia inicial da semana.            OPERACIONAL                        NaN
PCSEMANASMES   DIAFINAL  NUMBER(2,0)   Indica o dia final da semana.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*