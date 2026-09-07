# 📊 Tabela: PCMALHAAGENDAMENTO

### Estrutura de Colunas e Restrições

            Tabela              Coluna Tipo/Tamanho                                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMALHAAGENDAMENTO CODMALHAAGENDAMENTO  NUMBER(8,0)                                                                   Código de identificação do agendamento    CHAVE PRIMÁRIA (PK)                        NaN
PCMALHAAGENDAMENTO            CODMALHA  NUMBER(8,0)                                                                         Código de identificação da malha CHAVE ESTRANGEIRA (FK)                    PCMALHA
PCMALHAAGENDAMENTO          DATAINICIO         DATE                                                                      Data de início da execução da malha            OPERACIONAL                        NaN
PCMALHAAGENDAMENTO           DATAFINAL         DATE                                                                               Data de expiração da malha            OPERACIONAL                        NaN
PCMALHAAGENDAMENTO                CRON VARCHAR2(20) Expressão responsável por organizar quando será a execução da malha - baseada no Cron Expressions Oracle            OPERACIONAL                        NaN
PCMALHAAGENDAMENTO    SITUACAOEXECUCAO  VARCHAR2(1)                                                               Situação da última execução do agendamento            OPERACIONAL                        NaN
PCMALHAAGENDAMENTO      EXECUCAOMANUAL  VARCHAR2(1)                                                              Identificador da execução manual do cliente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*