# 📊 Tabela: PCENCERRAMENTO

### Estrutura de Colunas e Restrições

        Tabela           Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCENCERRAMENTO        CODFILIAL  VARCHAR2(2)                               NaN CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCENCERRAMENTO  CODENCERRAMENTO NUMBER(38,0)                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCENCERRAMENTO              ANO  NUMBER(4,0)                               NaN            OPERACIONAL                        NaN
PCENCERRAMENTO      DATAINICIAL         DATE                               NaN            OPERACIONAL                        NaN
PCENCERRAMENTO        DATAFINAL         DATE                               NaN            OPERACIONAL                        NaN
PCENCERRAMENTO SITUACAOESPECIAL  VARCHAR2(1) Situação especial do encerramento            OPERACIONAL                        NaN
PCENCERRAMENTO CODCONFEXERCICIO  NUMBER(8,0)               Código do Exercício            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*