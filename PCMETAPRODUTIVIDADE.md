# 📊 Tabela: PCMETAPRODUTIVIDADE

### Estrutura de Colunas e Restrições

             Tabela               Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETAPRODUTIVIDADE CODMETAPRODUTIVIDADE  NUMBER(6,0)              Cod. Meta de produtividade    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAPRODUTIVIDADE            CODFILIAL  VARCHAR2(2)          Cód. Filial da meta cadastrada            OPERACIONAL                        NaN
PCMETAPRODUTIVIDADE                  MES  VARCHAR2(2)               Mês de referencia da meta            OPERACIONAL                        NaN
PCMETAPRODUTIVIDADE                  ANO  VARCHAR2(4)               Ano de referencia da meta            OPERACIONAL                        NaN
PCMETAPRODUTIVIDADE       DTCANCELAMENTO         DATE             Dt. De cancelamento da meta            OPERACIONAL                        NaN
PCMETAPRODUTIVIDADE  CODFUNCCANCELAMENTO  NUMBER(8,0) Cód. Do funcionario que cancelou a meta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*