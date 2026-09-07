# 📊 Tabela: PCHIERARQUIAAPROVACAO

### Estrutura de Colunas e Restrições

               Tabela         Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHIERARQUIAAPROVACAO  CODHIERARQUIA NUMBER(10,0)                                   Código Chave Primária da hierarquia    CHAVE PRIMÁRIA (PK)                        NaN
PCHIERARQUIAAPROVACAO   TIPOOPERACAO  VARCHAR2(1)           Tipo da operação(A = Adiantamento, P = Prestação de contas)            OPERACIONAL                        NaN
PCHIERARQUIAAPROVACAO TIPOHIERARQUIA  VARCHAR2(1) Tipo da hierarquia(F = Filial, C = Centro de custo, P = Participante)            OPERACIONAL                        NaN
PCHIERARQUIAAPROVACAO      CODFILIAL  VARCHAR2(2)                                                      Código da Filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCHIERARQUIAAPROVACAO  CODAPROVADOR1  NUMBER(8,0)                                          Código do aprovador número 1 CHAVE ESTRANGEIRA (FK)                     PCEMPR
PCHIERARQUIAAPROVACAO CODSUBSTITUTO1  NUMBER(8,0)                                         Código do substituto número 1 CHAVE ESTRANGEIRA (FK)                     PCEMPR
PCHIERARQUIAAPROVACAO  DTINICIALSUB1         DATE                                   Data inicial do substituto número 1            OPERACIONAL                        NaN
PCHIERARQUIAAPROVACAO    DTFINALSUB1         DATE                                     Data final do substituto número 1            OPERACIONAL                        NaN
PCHIERARQUIAAPROVACAO  CODAPROVADOR2  NUMBER(8,0)                                          Código do aprovador número 2 CHAVE ESTRANGEIRA (FK)                     PCEMPR
PCHIERARQUIAAPROVACAO CODSUBSTITUTO2  NUMBER(8,0)                                         Código do substituto número 2 CHAVE ESTRANGEIRA (FK)                     PCEMPR
PCHIERARQUIAAPROVACAO  DTINICIALSUB2         DATE                                   Data inicial do substituto número 2            OPERACIONAL                        NaN
PCHIERARQUIAAPROVACAO    DTFINALSUB2         DATE                                     Data final do substituto número 2            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*