# 📊 Tabela: PCSERVICOCLIENTE

### Estrutura de Colunas e Restrições

          Tabela                     Coluna  Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOCLIENTE                       CNPJ  VARCHAR2(50)                                      Cnpj do cliente            OPERACIONAL                        NaN
PCSERVICOCLIENTE                 CODSERVICO  NUMBER(10,0) Código do serviço utilizado para consulta do cliente CHAVE ESTRANGEIRA (FK)                  PCSERVICO
PCSERVICOCLIENTE            ESTIMATIVAPORTE  VARCHAR2(50)                                  Estimativa de porte            OPERACIONAL                        NaN
PCSERVICOCLIENTE ESTIMATIVAQTDEFUNCIONARIOS  VARCHAR2(50)             Estimativa de quantidade de funcionários            OPERACIONAL                        NaN
PCSERVICOCLIENTE             SCOREATIVIDADE  VARCHAR2(50)                                   Score da atividade            OPERACIONAL                        NaN
PCSERVICOCLIENTE ESTIMATIVAFAIXAFATURAMENTO  VARCHAR2(50)                   Estimativa de faixa de faturamento            OPERACIONAL                        NaN
PCSERVICOCLIENTE               NOMEFANTASIA VARCHAR2(255)                             Nome fantasia do cliente            OPERACIONAL                        NaN
PCSERVICOCLIENTE                RAZAOSOCIAL VARCHAR2(255)                              Razão social do cliente            OPERACIONAL                        NaN
PCSERVICOCLIENTE        CAPITALINVESTIMENTO VARCHAR2(255)                              Capital de investimento            OPERACIONAL                        NaN
PCSERVICOCLIENTE                 CODCLIENTE  NUMBER(10,0)                             Identificador do cliente    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*