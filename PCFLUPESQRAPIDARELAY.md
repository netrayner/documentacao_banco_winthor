# 📊 Tabela: PCFLUPESQRAPIDARELAY

### Estrutura de Colunas e Restrições

              Tabela            Coluna  Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFLUPESQRAPIDARELAY          CODRELAY  VARCHAR2(25)           Código do relay    CHAVE PRIMÁRIA (PK)                        NaN
PCFLUPESQRAPIDARELAY CODPESQUISARAPIDA  VARCHAR2(25) Código da pesquisa rápida CHAVE ESTRANGEIRA (FK)            PCFLUPESQRAPIDA
PCFLUPESQRAPIDARELAY             LABEL VARCHAR2(130)    Classificador do relay            OPERACIONAL                        NaN
PCFLUPESQRAPIDARELAY        RELAYSTATE VARCHAR2(255)       Parametros de relay            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*