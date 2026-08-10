# 📊 Tabela: PCINTEGRACAOLOGEXCLUSAODADOS

### Estrutura de Colunas e Restrições

                      Tabela             Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOLOGEXCLUSAODADOS            CRONTAB VARCHAR2(20)            Armezena cron da tabela            OPERACIONAL                        NaN
PCINTEGRACAOLOGEXCLUSAODADOS LOG_DADOSEXCLUIDOS         CLOB Armazena o log dos dados excluídos            OPERACIONAL                        NaN
PCINTEGRACAOLOGEXCLUSAODADOS      DATA_EXECUCAO         DATE        Armazena a data de execução            OPERACIONAL                        NaN
PCINTEGRACAOLOGEXCLUSAODADOS               DIAS NUMBER(10,0)     Armezana os dias para exclusão            OPERACIONAL                        NaN
PCINTEGRACAOLOGEXCLUSAODADOS          TIPO_DADO VARCHAR2(20)           Armazena o tipo de dados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*