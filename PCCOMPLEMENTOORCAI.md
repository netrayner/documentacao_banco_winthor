# 📊 Tabela: PCCOMPLEMENTOORCAI

### Estrutura de Colunas e Restrições

            Tabela              Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMPLEMENTOORCAI             NUMORCA NUMBER(10,0)                 Número do Orçamento    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPLEMENTOORCAI      NUMSEQITEMORCA NUMBER(20,0)         Número de sequência do item    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPLEMENTOORCAI              NUMSEQ NUMBER(10,0)  Número de sequência do complemento    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPLEMENTOORCAI             CODCOMP  NUMBER(8,0)               Código do complemento            OPERACIONAL                        NaN
PCCOMPLEMENTOORCAI         CODAUXILIAR NUMBER(20,0)                     Código Auxiliar            OPERACIONAL                        NaN
PCCOMPLEMENTOORCAI              QTCOMP NUMBER(20,6)          Quantidade de complementos            OPERACIONAL                        NaN
PCCOMPLEMENTOORCAI         VLACRESCIMO  NUMBER(8,2)                  Valor do acréscimo            OPERACIONAL                        NaN
PCCOMPLEMENTOORCAI      TOTALACRESCIMO NUMBER(12,2)            Valor total do acréscimo            OPERACIONAL                        NaN
PCCOMPLEMENTOORCAI  IMPRIMERESTAURANTE  VARCHAR2(1) Imprime complemento no restaurante.            OPERACIONAL                        NaN
PCCOMPLEMENTOORCAI IMPRESSORESTAURANTE  VARCHAR2(1)                 STATUS DE IMPRESSAO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*