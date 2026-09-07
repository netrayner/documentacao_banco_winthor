# 📊 Tabela: PCDESDLANCOPERACAO

### Estrutura de Colunas e Restrições

            Tabela        Coluna  Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESDLANCOPERACAO        RECNUM   NUMBER(8,0)                       Numero do lançamento que originou desdobramento    CHAVE PRIMÁRIA (PK)                        NaN
PCDESDLANCOPERACAO CODROTINADESD VARCHAR2(100)                              Codigo da rotina que fez o desdobramento            OPERACIONAL                        NaN
PCDESDLANCOPERACAO  OPERACAODESD  VARCHAR2(50) Tipo da operação de desdobramento: NORMAL / ESTORNO / ESTORNOIGNORADO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*