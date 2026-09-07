# 📊 Tabela: PCCARDAPIO

### Estrutura de Colunas e Restrições

    Tabela      Coluna Tipo/Tamanho  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARDAPIO CODCARDAPIO  NUMBER(6,0)      Codigo Cardapio    CHAVE PRIMÁRIA (PK)                        NaN
PCCARDAPIO   DESCRICAO VARCHAR2(60) Descição do Cardapio            OPERACIONAL                        NaN
PCCARDAPIO   CODFILIAL  VARCHAR2(2)        Codigo Filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCCARDAPIO       ATIVO  VARCHAR2(1)                Ativo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*