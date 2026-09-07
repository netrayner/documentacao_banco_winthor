# 📊 Tabela: PCERRORLOGCONSINCO

### Estrutura de Colunas e Restrições

            Tabela        Coluna   Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCERRORLOGCONSINCO    ERROR_CODE   NUMBER(20,0)                                       Código do erro            OPERACIONAL                        NaN
PCERRORLOGCONSINCO ERROR_MESSAGE VARCHAR2(4000)                                    Descrição do erro            OPERACIONAL                        NaN
PCERRORLOGCONSINCO     BACKTRACE           CLOB Rastreia o erro até a linha em que ele foi levantado            OPERACIONAL                        NaN
PCERRORLOGCONSINCO     CALLSTACK           CLOB                                       Pilha de erros            OPERACIONAL                        NaN
PCERRORLOGCONSINCO    CREATED_ON           DATE                                      Data da criação            OPERACIONAL                        NaN
PCERRORLOGCONSINCO    CREATED_BY   VARCHAR2(50)                                       Origem do erro            OPERACIONAL                        NaN
PCERRORLOGCONSINCO   ID_PROCESSO    NUMBER(4,0)               Identificar do processo que gerou erro            OPERACIONAL                        NaN
PCERRORLOGCONSINCO     TIPO_ERRO    VARCHAR2(1)                  Tipo do erro. A- Alerta ou E - Erro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*