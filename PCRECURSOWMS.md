# 📊 Tabela: PCRECURSOWMS

### Estrutura de Colunas e Restrições

      Tabela         Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECURSOWMS     CODRECURSO  NUMBER(8,0)                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRECURSOWMS      DESCRICAO VARCHAR2(60)                            NaN            OPERACIONAL                        NaN
PCRECURSOWMS    CODAUXILIAR VARCHAR2(30)                            NaN            OPERACIONAL                        NaN
PCRECURSOWMS    TIPORECURSO  VARCHAR2(1)                            NaN            OPERACIONAL                        NaN
PCRECURSOWMS      VALORHORA NUMBER(12,6)                            NaN            OPERACIONAL                        NaN
PCRECURSOWMS RECURSOPROPRIO  VARCHAR2(1)                            NaN            OPERACIONAL                        NaN
PCRECURSOWMS      CODFILIAL  VARCHAR2(3)              Filial do serviço            OPERACIONAL                        NaN
PCRECURSOWMS          ATIVO  VARCHAR2(1) Indica se o serviço está ativo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*