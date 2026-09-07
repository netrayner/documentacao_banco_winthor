# 📊 Tabela: PCCONFIGCLASSECLIMED

### Estrutura de Colunas e Restrições

              Tabela             Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGCLASSECLIMED          CODCONFIG   NUMBER(2,0)                          Código    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGCLASSECLIMED  DESCRICAORESUMIDA  VARCHAR2(40)              Descrição resumida            OPERACIONAL                        NaN
PCCONFIGCLASSECLIMED DESCRICAODETALHADA VARCHAR2(250)             Descrição detalhada            OPERACIONAL                        NaN
PCCONFIGCLASSECLIMED        SELECIONADA   VARCHAR2(1)                     Selecionada            OPERACIONAL                        NaN
PCCONFIGCLASSECLIMED   ABATERDEVOLUCOES   VARCHAR2(1) Define se irá abater devoluções            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*