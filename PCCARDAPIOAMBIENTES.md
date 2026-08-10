# 📊 Tabela: PCCARDAPIOAMBIENTES

### Estrutura de Colunas e Restrições

             Tabela      Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARDAPIOAMBIENTES CODAMBIENTE  NUMBER(6,0)        Codigo Grupo    CHAVE PRIMÁRIA (PK)                        NaN
PCCARDAPIOAMBIENTES   DESCRICAO VARCHAR2(60)   Descição do Grupo            OPERACIONAL                        NaN
PCCARDAPIOAMBIENTES   CODFILIAL  VARCHAR2(2)        Cor do Grupo CHAVE ESTRANGEIRA (FK)                   PCFILIAL

---
*Documentação gerada automaticamente.*