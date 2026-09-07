# 📊 Tabela: PCLOGEVENTO

### Estrutura de Colunas e Restrições

     Tabela         Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGEVENTO             ID  NUMBER(10,0)             idenficador incremental    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGEVENTO    CODEXECUCAO  VARCHAR2(80)            código único de execução            OPERACIONAL                        NaN
PCLOGEVENTO      CODMODULO  VARCHAR2(64) identificador do módulo de execução            OPERACIONAL                        NaN
PCLOGEVENTO      CODFILIAL   VARCHAR2(3)         codigo da filial processada            OPERACIONAL                        NaN
PCLOGEVENTO       CODOPCAO  VARCHAR2(32)          código da opção processada            OPERACIONAL                        NaN
PCLOGEVENTO         STATUS  VARCHAR2(32)                  Status de execução            OPERACIONAL                        NaN
PCLOGEVENTO           TIPO  VARCHAR2(32)                    tipo da execução            OPERACIONAL                        NaN
PCLOGEVENTO      TENTATIVA   NUMBER(2,0)     número da tentativa de execução            OPERACIONAL                        NaN
PCLOGEVENTO        DATALOG  TIMESTAMP(6)                      data do evento            OPERACIONAL                        NaN
PCLOGEVENTO         MOTIVO VARCHAR2(256)          motivo de erro da execução            OPERACIONAL                        NaN
PCLOGEVENTO DADOSORIGINAIS          CLOB            dados iniciais do evento            OPERACIONAL                        NaN
PCLOGEVENTO  DADOSTRATADOS          CLOB         dados processados do evento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*