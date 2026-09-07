# 📊 Tabela: PCCARREGA_PRODUTO

### Estrutura de Colunas e Restrições

           Tabela             Coluna  Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARREGA_PRODUTO   OBJETOREFERENCIA VARCHAR2(200)           Nome do processo executado            OPERACIONAL                        NaN
PCCARREGA_PRODUTO ULTIMAEXECUCAO_BKP  TIMESTAMP(6)                                  NaN            OPERACIONAL                        NaN
PCCARREGA_PRODUTO        PROCESSANDO   VARCHAR2(1)                   Status da execução            OPERACIONAL                        NaN
PCCARREGA_PRODUTO     ULTIMAEXECUCAO  TIMESTAMP(6) Ultima execução do processo na carga            OPERACIONAL                        NaN
PCCARREGA_PRODUTO ULTIMAEXECUCAO_NEW  TIMESTAMP(6)                                  NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*