# 📊 Tabela: PCFLUPESQRAPIDASELECT

### Estrutura de Colunas e Restrições

               Tabela            Coluna  Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFLUPESQRAPIDASELECT         CODSELECT  VARCHAR2(25)        Código do selector    CHAVE PRIMÁRIA (PK)                        NaN
PCFLUPESQRAPIDASELECT CODPESQUISARAPIDA  VARCHAR2(25) Código da pesquisa rápida CHAVE ESTRANGEIRA (FK)            PCFLUPESQRAPIDA
PCFLUPESQRAPIDASELECT             LABEL VARCHAR2(130) Classificador do selector            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*