# 📊 Tabela: PCETAPAPRODUCAO

### Estrutura de Colunas e Restrições

         Tabela      Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCETAPAPRODUCAO    CODETAPA  NUMBER(6,0)          código da etapa da produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCETAPAPRODUCAO   DESCRICAO VARCHAR2(40)       Descrição da etapa de produção.            OPERACIONAL                        NaN
PCETAPAPRODUCAO      STATUS  VARCHAR2(1)          Status da etapa de produção.            OPERACIONAL                        NaN
PCETAPAPRODUCAO OBRIGATORIA  VARCHAR2(1) Obrigatoriedade da etapa de produção.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*