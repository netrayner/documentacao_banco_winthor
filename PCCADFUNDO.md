# 📊 Tabela: PCCADFUNDO

### Estrutura de Colunas e Restrições

    Tabela          Coluna  Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCADFUNDO        CODFUNDO   NUMBER(6,0) gerado pela nova rotina para identificar o fundo            OPERACIONAL                        NaN
PCCADFUNDO CODFILIALPADRAO   VARCHAR2(2)     Código da filial padrão cadastrada na rotina            OPERACIONAL                        NaN
PCCADFUNDO       CODFILIAL   VARCHAR2(2)      Código das filiais que fazem parte do fundo            OPERACIONAL                        NaN
PCCADFUNDO            NOME VARCHAR2(100)                     Nome cadastrado para o fundo            OPERACIONAL                        NaN
PCCADFUNDO        CODCONTA  NUMBER(10,0) Campo para cadastro daconta do fundo MultiFilial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*