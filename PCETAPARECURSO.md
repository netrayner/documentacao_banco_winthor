# 📊 Tabela: PCETAPARECURSO

### Estrutura de Colunas e Restrições

        Tabela         Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCETAPARECURSO         METODO  VARCHAR2(4) Método de produção do produto master.    CHAVE PRIMÁRIA (PK)                        NaN
PCETAPARECURSO  CODPRODMASTER  NUMBER(6,0) Código do produto master da produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCETAPARECURSO      IDRECURSO NUMBER(10,0)        Código do recurso da produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCETAPARECURSO       CODETAPA  NUMBER(6,0)          Código da etapa da produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCETAPARECURSO      CODFILIAL  VARCHAR2(2)                     Código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCETAPARECURSO SEQUENCIAETAPA  NUMBER(4,0)       Sequencia da etapa na produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCETAPARECURSO  TEMPOPREVISTO NUMBER(18,6)   Tempo previsto de duração da etapa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*