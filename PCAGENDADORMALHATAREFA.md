# 📊 Tabela: PCAGENDADORMALHATAREFA

### Estrutura de Colunas e Restrições

                Tabela                  Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDADORMALHATAREFA CODAGENDADORMALHATAREFA NUMBER(10,0)           Identificador da taela    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDADORMALHATAREFA       CODAGENDADORMALHA NUMBER(10,0)   Código da malha de agendamento CHAVE ESTRANGEIRA (FK)           PCAGENDADORMALHA
PCAGENDADORMALHATAREFA      CODAGENDADORTAREFA NUMBER(10,0) Código da tarefa a ser executada CHAVE ESTRANGEIRA (FK)          PCAGENDADORTAREFA
PCAGENDADORMALHATAREFA                   PASSO  NUMBER(8,0)                Ordem de execução            OPERACIONAL                        NaN
PCAGENDADORMALHATAREFA                   DELAY  NUMBER(8,0)    Tempo de espera para execução            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*