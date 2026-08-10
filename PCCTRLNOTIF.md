# 📊 Tabela: PCCTRLNOTIF

### Estrutura de Colunas e Restrições

     Tabela           Coluna   Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCTRLNOTIF               ID   NUMBER(20,0)         Identificador da notificação    CHAVE PRIMÁRIA (PK)                        NaN
PCCTRLNOTIF      DATACRIACAO           DATE       Data de criação da notificação            OPERACIONAL                        NaN
PCCTRLNOTIF        CABECALHO  VARCHAR2(100)             Cabeçalho da notificação            OPERACIONAL                        NaN
PCCTRLNOTIF            CORPO VARCHAR2(2048)               Fuso horário da tarefa            OPERACIONAL                        NaN
PCCTRLNOTIF  TIPONOTIFICACAO    NUMBER(2,0) Identificador do tipo de notificação            OPERACIONAL                        NaN
PCCTRLNOTIF NIVELNOTIFICACAO    NUMBER(2,0)   Nível de severidade da notificação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*