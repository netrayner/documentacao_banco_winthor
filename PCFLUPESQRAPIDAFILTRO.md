# 📊 Tabela: PCFLUPESQRAPIDAFILTRO

### Estrutura de Colunas e Restrições

               Tabela            Coluna  Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFLUPESQRAPIDAFILTRO         CODFILTRO  VARCHAR2(25)          Código do filtro    CHAVE PRIMÁRIA (PK)                        NaN
PCFLUPESQRAPIDAFILTRO CODPESQUISARAPIDA  VARCHAR2(25) Código da pesquisa rápida CHAVE ESTRANGEIRA (FK)            PCFLUPESQRAPIDA
PCFLUPESQRAPIDAFILTRO             LABEL VARCHAR2(130)   Classificador do filtro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*