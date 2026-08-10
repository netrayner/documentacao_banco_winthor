# 📊 Tabela: PCSUPPLILOGENVIO

### Estrutura de Colunas e Restrições

          Tabela     Coluna   Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPPLILOGENVIO     CODCLI   NUMBER(22,0)                   Código do cliente            OPERACIONAL                        NaN
PCSUPPLILOGENVIO DTHORAERRO           DATE            Data de gravação do erro            OPERACIONAL                        NaN
PCSUPPLILOGENVIO      ERROS VARCHAR2(4000) Erros gerados no envio dos arquivos            OPERACIONAL                        NaN
PCSUPPLILOGENVIO         ID   NUMBER(22,0)                     Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*