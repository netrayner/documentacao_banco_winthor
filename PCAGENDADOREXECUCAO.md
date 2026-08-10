# 📊 Tabela: PCAGENDADOREXECUCAO

### Estrutura de Colunas e Restrições

             Tabela                    Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDADOREXECUCAO CODAGENDADORMALHAEXECUCAO NUMBER(10,0)         Identificador da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDADOREXECUCAO         CODAGENDADORMALHA NUMBER(10,0) Código da malha a ser executada CHAVE ESTRANGEIRA (FK)           PCAGENDADORMALHA
PCAGENDADOREXECUCAO                 CODFILIAL VARCHAR2(10)                Código da filial            OPERACIONAL                        NaN
PCAGENDADOREXECUCAO                  TIMEZONE NUMBER(10,0)            Timezone da execução            OPERACIONAL                        NaN
PCAGENDADOREXECUCAO       DATAPROXIMAEXECUCAO TIMESTAMP(6) Data e hora da próxima execução            OPERACIONAL                        NaN
PCAGENDADOREXECUCAO                DATAINICIO TIMESTAMP(6)      Data de início da execução            OPERACIONAL                        NaN
PCAGENDADOREXECUCAO                   DATAFIM TIMESTAMP(6)   Data e hora final da execução            OPERACIONAL                        NaN
PCAGENDADOREXECUCAO          SITUACAOEXECUCAO  VARCHAR2(1)            Situação da execução            OPERACIONAL                        NaN
PCAGENDADOREXECUCAO                       LOG         CLOB                 Log da execução            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*