# 📊 Tabela: PCPLANOCONTASPED

### Estrutura de Colunas e Restrições

          Tabela             Coluna   Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPLANOCONTASPED CODPLANOCONTA_SPED    NUMBER(7,0)               Indica o código do plano contas SPED.    CHAVE PRIMÁRIA (PK)                        NaN
PCPLANOCONTASPED      CODCONTA_SPED   VARCHAR2(20)                      Indica o código da conta SPED.            OPERACIONAL                        NaN
PCPLANOCONTASPED          DESCRICAO  VARCHAR2(200)                        Indica a descrição da conta.            OPERACIONAL                        NaN
PCPLANOCONTASPED        ORIENTACOES VARCHAR2(1000) Indica a especificação sobre a utilizaade da conta.            OPERACIONAL                        NaN
PCPLANOCONTASPED           DTINICIO           DATE                                       Data inicial.            OPERACIONAL                        NaN
PCPLANOCONTASPED              DTFIM           DATE                                         Data final.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*