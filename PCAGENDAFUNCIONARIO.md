# 📊 Tabela: PCAGENDAFUNCIONARIO

### Estrutura de Colunas e Restrições

             Tabela       Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDAFUNCIONARIO    MATRICULA  NUMBER(8,0)                  Matrícula do Funcionário.    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFUNCIONARIO        NUMOS  NUMBER(6,0) Ordem de Serviço para execução do serviço.    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFUNCIONARIO NUMOSSERVICO  NUMBER(6,0)                                        NaN    CHAVE PRIMÁRIA (PK)            PCORDEMSERVICOI
PCAGENDAFUNCIONARIO   CODSERVICO  NUMBER(6,0)                         Código do Serviço.    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFUNCIONARIO         DATA         DATE               Data de execução do serviço.    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFUNCIONARIO   HORAINICIO  NUMBER(2,0)     Hora de inicio da execução do serviço.    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFUNCIONARIO MINUTOINICIO  NUMBER(2,0)   Minuto de inicio da execução do serviço.    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFUNCIONARIO      HORAFIM  NUMBER(2,0)         Hora final da execução do serviço.            OPERACIONAL                        NaN
PCAGENDAFUNCIONARIO    MINUTOFIM  NUMBER(2,0)       Minuto final da execução do serviço.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*