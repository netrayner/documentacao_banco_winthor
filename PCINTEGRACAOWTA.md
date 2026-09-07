# 📊 Tabela: PCINTEGRACAOWTA

### Estrutura de Colunas e Restrições

         Tabela            Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOWTA                ID        NUMBER                        Identificador da integração    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOWTA    ULTIMAEXECUCAO          DATE              Data da última execução da integração            OPERACIONAL                        NaN
PCINTEGRACAOWTA         DESCRICAO VARCHAR2(255)                            Descrição da integração            OPERACIONAL                        NaN
PCINTEGRACAOWTA           SERVICO  VARCHAR2(80)             Identificador do serviço da integração            OPERACIONAL                        NaN
PCINTEGRACAOWTA            VERSAO  VARCHAR2(20)                               Versão da integração            OPERACIONAL                        NaN
PCINTEGRACAOWTA        CODIGOFILA  VARCHAR2(80)                   Identificador da fila do serviço            OPERACIONAL                        NaN
PCINTEGRACAOWTA CODIGORETORNOFILA  VARCHAR2(80)        Identificador da fila de retorno do serviço            OPERACIONAL                        NaN
PCINTEGRACAOWTA            STATUS   NUMBER(1,0)                  Indicador do status da integração            OPERACIONAL                        NaN
PCINTEGRACAOWTA              NOME VARCHAR2(255)                                 Nome da integração            OPERACIONAL                        NaN
PCINTEGRACAOWTA             JOBID VARCHAR2(255)             Identificador do agendamento no Quartz            OPERACIONAL                        NaN
PCINTEGRACAOWTA        TIMEZONEID  NUMBER(10,0) Identificador único do Timezone para o agendamento            OPERACIONAL                        NaN
PCINTEGRACAOWTA      CODIGOFILIAL  VARCHAR2(80)                            Código filial vinculada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*