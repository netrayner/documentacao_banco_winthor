# 📊 Tabela: PCEXECUCAOAGENDAMENTO

### Estrutura de Colunas e Restrições

               Tabela           Coluna  Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXECUCAOAGENDAMENTO       EXECUCAOID  VARCHAR2(80)                               Identificador da execução    CHAVE PRIMÁRIA (PK)                        NaN
PCEXECUCAOAGENDAMENTO           CODJOB VARCHAR2(120)                                    Identificador do job            OPERACIONAL                        NaN
PCEXECUCAOAGENDAMENTO         CODGROUP VARCHAR2(120)                           Identificador do grupo do job            OPERACIONAL                        NaN
PCEXECUCAOAGENDAMENTO           STATUS  VARCHAR2(20)                                      Status da execução            OPERACIONAL                        NaN
PCEXECUCAOAGENDAMENTO         DTINICIO          DATE        Data e hora de início da execução do agendamento            OPERACIONAL                        NaN
PCEXECUCAOAGENDAMENTO            DTFIM          DATE            Data e hora final da execução do agendamento            OPERACIONAL                        NaN
PCEXECUCAOAGENDAMENTO          DETALHE          CLOB Maiores detalhes a respeito da execução do agendamento.            OPERACIONAL                        NaN
PCEXECUCAOAGENDAMENTO     DTINICIOFUSO          DATE                Hora de Início no Fuso Horário da Tarefa            OPERACIONAL                        NaN
PCEXECUCAOAGENDAMENTO        DTFIMFUSO          DATE                   Hora de Fim no Fuso Horário da Tarefa            OPERACIONAL                        NaN
PCEXECUCAOAGENDAMENTO TIMEZONESERVIDOR  VARCHAR2(80)                                Fuso Horário do Servidor            OPERACIONAL                        NaN
PCEXECUCAOAGENDAMENTO   TIMEZONETAREFA  VARCHAR2(80)                                  Fuso Horário da Tarefa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*