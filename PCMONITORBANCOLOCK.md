# 📊 Tabela: PCMONITORBANCOLOCK

### Estrutura de Colunas e Restrições

            Tabela       Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMONITORBANCOLOCK   CODMONITOR  NUMBER(10,0)              Identificador do monitaramento            OPERACIONAL                        NaN
PCMONITORBANCOLOCK  LOCK_NUMBER  NUMBER(10,0)                  Número da sessão bloqueada            OPERACIONAL                        NaN
PCMONITORBANCOLOCK          SID VARCHAR2(100)           Código de identificação da sessão            OPERACIONAL                        NaN
PCMONITORBANCOLOCK SID_BLOCKING VARCHAR2(100) Código de identificação da sessão bloqueada            OPERACIONAL                        NaN
PCMONITORBANCOLOCK    LOCK_TIME          DATE               Data e hora do LOCK da sessão            OPERACIONAL                        NaN
PCMONITORBANCOLOCK RELEASE_TIME          DATE  Data e hora da liberação da LOCK da sessão            OPERACIONAL                        NaN
PCMONITORBANCOLOCK    CODSESSAO  NUMBER(10,0)                     Identificador da sessão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*