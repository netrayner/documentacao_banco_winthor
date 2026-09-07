# 📊 Tabela: PCFLUPESQRAPIDA

### Estrutura de Colunas e Restrições

         Tabela              Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFLUPESQRAPIDA         CODPESQUISA  VARCHAR2(25)              Código da pesquisa    CHAVE PRIMÁRIA (PK)                        NaN
PCFLUPESQRAPIDA          ID_EXTERNO  VARCHAR2(25)                  Id do Identity            OPERACIONAL                        NaN
PCFLUPESQRAPIDA NOME_EXIBICAO_PT_BR VARCHAR2(130) Nome para exibição em português            OPERACIONAL                        NaN
PCFLUPESQRAPIDA NOME_EXIBICAO_EN_US VARCHAR2(130)    Nome para exibição em inglês            OPERACIONAL                        NaN
PCFLUPESQRAPIDA          NOME_PT_BR VARCHAR2(130)               Nome em português            OPERACIONAL                        NaN
PCFLUPESQRAPIDA          NOME_EN_US VARCHAR2(130)                  Nome em inglês            OPERACIONAL                        NaN
PCFLUPESQRAPIDA     DESCRICAO_PT_BR VARCHAR2(255)          Descrição em português            OPERACIONAL                        NaN
PCFLUPESQRAPIDA     DESCRICAO_EN_US VARCHAR2(255)             Descrição em inglês            OPERACIONAL                        NaN
PCFLUPESQRAPIDA                 URL VARCHAR2(255)             URL base do serviço            OPERACIONAL                        NaN
PCFLUPESQRAPIDA            URLMODEL VARCHAR2(255)                   URL do modelo            OPERACIONAL                        NaN
PCFLUPESQRAPIDA             URLDATA VARCHAR2(255)                   URL dos dados            OPERACIONAL                        NaN
PCFLUPESQRAPIDA     URLAUTOCOMPLETE VARCHAR2(255)  URL para dados de autocomplete            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*