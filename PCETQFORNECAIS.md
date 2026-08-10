# 📊 Tabela: PCETQFORNECAIS

### Estrutura de Colunas e Restrições

        Tabela      Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCETQFORNECAIS IDETQFORNEC        NUMBER  Identificador eitqueta fornecedor CHAVE ESTRANGEIRA (FK)                PCETQFORNEC
PCETQFORNECAIS          AI  VARCHAR2(40) Identificadoe de aplicação GS1 128            OPERACIONAL                        NaN
PCETQFORNECAIS      INDICE        NUMBER                             Indice            OPERACIONAL                        NaN
PCETQFORNECAIS       VALOR VARCHAR2(100)                              Valor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*