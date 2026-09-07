# 📊 Tabela: PCAGENDAMENTOECOMMERCE

### Estrutura de Colunas e Restrições

                Tabela        Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDAMENTOECOMMERCE            ID  NUMBER(10,0)                     Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAMENTOECOMMERCE          CRON  VARCHAR2(40) Define regra do intervalor - Função do Java            OPERACIONAL                        NaN
PCAGENDAMENTOECOMMERCE    TIPOAGENDA VARCHAR2(250)                           Tipo de agendamento            OPERACIONAL                        NaN
PCAGENDAMENTOECOMMERCE TIPOINTERVALO VARCHAR2(250)                             Tipo de intervalo            OPERACIONAL                        NaN
PCAGENDAMENTOECOMMERCE     INTERVALO  NUMBER(10,0)                            Valor do intervalo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*