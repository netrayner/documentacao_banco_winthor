# 📊 Tabela: PCLFPISREG0111

### Estrutura de Colunas e Restrições

        Tabela           Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLFPISREG0111        CODFILIAL  VARCHAR2(2)                                                Código da Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFPISREG0111          DATAINI         DATE                             Data Inicial do Período Selecionado.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFPISREG0111          DATAFIM         DATE                               Data Final do Período Selecionado.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFPISREG0111 RECBRUNCUMTRIBMI NUMBER(15,6)       Receita Bruta não Cumulativa Tributada no Mercado Interno.            OPERACIONAL                        NaN
PCLFPISREG0111   RECBRUNCUMNTMI NUMBER(15,6) Receita Bruta Não-Cumulativa ¿ Não Tributada no Mercado Interno.            OPERACIONAL                        NaN
PCLFPISREG0111    RECBRUNCUMEXP NUMBER(15,6)                       Receita Bruta Não-Cumulativa - Exportação.            OPERACIONAL                        NaN
PCLFPISREG0111        RECBRUCUM NUMBER(15,6)                                        Receita Bruta Cumulativa.            OPERACIONAL                        NaN
PCLFPISREG0111      RECBRUTOTAL NUMBER(15,6)                                             Receita Bruta Total.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*