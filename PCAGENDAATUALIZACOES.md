# 📊 Tabela: PCAGENDAATUALIZACOES

### Estrutura de Colunas e Restrições

              Tabela        Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDAATUALIZACOES     CODROTINA  VARCHAR2(4) Código da rotina para agendamento automático.    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAATUALIZACOES   DATAINICIAL         DATE       Data inicial do agendamento automático.            OPERACIONAL                        NaN
PCAGENDAATUALIZACOES     DATAFINAL         DATE            Data final agendamento automático.            OPERACIONAL                        NaN
PCAGENDAATUALIZACOES PERIODICIDADE  NUMBER(4,0) Periodicidade de dias agendamento automático.    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAATUALIZACOES    HORAINICIO  VARCHAR2(8)     Hora de início da atualização automática.            OPERACIONAL                        NaN
PCAGENDAATUALIZACOES FECHADIAATUAL  VARCHAR2(1)                       Fechamento no dia atual            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*