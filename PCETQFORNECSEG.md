# 📊 Tabela: PCETQFORNECSEG

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCETQFORNECSEG    VARIAVEL  VARCHAR2(1)            Possui tamanho variável            OPERACIONAL                        NaN
PCETQFORNECSEG          AI VARCHAR2(40) Identificador de aplicação Gs1 128    CHAVE PRIMÁRIA (PK)                        NaN
PCETQFORNECSEG      INICIO       NUMBER                 Início do segmento            OPERACIONAL                        NaN
PCETQFORNECSEG         FIM       NUMBER                    Fim do segmento            OPERACIONAL                        NaN
PCETQFORNECSEG    DECIMAIS       NUMBER          Quantidade casas decimais            OPERACIONAL                        NaN
PCETQFORNECSEG IDETQFORNEC       NUMBER             Identificador etiqueta    CHAVE PRIMÁRIA (PK)                PCETQFORNEC

---
*Documentação gerada automaticamente.*