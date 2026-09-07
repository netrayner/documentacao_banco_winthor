# 📊 Tabela: PCAGENDADORCONFIGURACAO

### Estrutura de Colunas e Restrições

                 Tabela                   Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDADORCONFIGURACAO CODAGENDADORCONFIGURACAO NUMBER(10,0)                             Identificador da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDADORCONFIGURACAO        CODAGENDADORMALHA NUMBER(10,0)                       Código da malha de agendamento            OPERACIONAL                        NaN
PCAGENDADORCONFIGURACAO                     CRON VARCHAR2(20)                        Configuração de periodicidade            OPERACIONAL                        NaN
PCAGENDADORCONFIGURACAO                 SITUACAO  VARCHAR2(1)              Situação da configuração do agendamento            OPERACIONAL                        NaN
PCAGENDADORCONFIGURACAO           EXECUCAOMANUAL  VARCHAR2(1) Configuração para executar manualmente o agendamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*