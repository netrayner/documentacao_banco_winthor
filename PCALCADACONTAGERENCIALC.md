# 📊 Tabela: PCALCADACONTAGERENCIALC

### Estrutura de Colunas e Restrições

                 Tabela        Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCALCADACONTAGERENCIALC     CODFILIAL  VARCHAR2(2)                Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGERENCIALC      CODCONTA NUMBER(10,0)       Código da conta gerencial    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGERENCIALC      CODAUTOR  NUMBER(8,0) Código do autorizante principal    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGERENCIALC      VLLIMITE NUMBER(22,6)      Valor de limite autorizado    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGERENCIALC CODUSUARIOINC  NUMBER(8,0)   Código do usuário que incluiu            OPERACIONAL                        NaN
PCALCADACONTAGERENCIALC    DTINCLUSAO         DATE  Data de inclusão do lançamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*