# 📊 Tabela: PCGRUPOMYFROTA

### Estrutura de Colunas e Restrições

        Tabela    Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGRUPOMYFROTA  CODGRUPO   VARCHAR2(3)              Código do grupo de lançamento.            OPERACIONAL                        NaN
PCGRUPOMYFROTA DESCGRUPO VARCHAR2(100)                          Decrição do Grupo.            OPERACIONAL                        NaN
PCGRUPOMYFROTA  CODCONTA  NUMBER(10,0)    Código da conta gerencial do lançamento.            OPERACIONAL                        NaN
PCGRUPOMYFROTA CODFILIAL   VARCHAR2(2)             Código da Filial do lançamento.            OPERACIONAL                        NaN
PCGRUPOMYFROTA  NUMBANCO  NUMBER(14,2) Número do Banco de movimentação financeira.            OPERACIONAL                        NaN
PCGRUPOMYFROTA  CODMOEDA   VARCHAR2(4)           Moeda de movimentação financeira.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*