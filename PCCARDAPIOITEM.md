# 📊 Tabela: PCCARDAPIOITEM

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARDAPIOITEM     CODITEM  NUMBER(6,0)        Codigo do Item    CHAVE PRIMÁRIA (PK)                        NaN
PCCARDAPIOITEM CODCARDAPIO  NUMBER(6,0)          Cod.Cardapio CHAVE ESTRANGEIRA (FK)                 PCCARDAPIO
PCCARDAPIOITEM    CODGRUPO  NUMBER(6,0)          Codigo Grupo CHAVE ESTRANGEIRA (FK)            PCCARDAPIOGRUPO
PCCARDAPIOITEM     CODPROD  NUMBER(6,0)           Cod.Produto CHAVE ESTRANGEIRA (FK)                   PCPRODUT
PCCARDAPIOITEM       ORDEM  NUMBER(4,0) Ordem de Apresentação            OPERACIONAL                        NaN
PCCARDAPIOITEM CODAUXILIAR NUMBER(20,0)  Cod.Barras Embalagem            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*