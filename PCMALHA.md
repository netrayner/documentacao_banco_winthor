# 📊 Tabela: PCMALHA

### Estrutura de Colunas e Restrições

 Tabela               Coluna  Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMALHA             CODMALHA   NUMBER(6,0)                            Descricao coluna CODMALHA    CHAVE PRIMÁRIA (PK)                        NaN
PCMALHA            DESCRICAO VARCHAR2(100)                           Descricao coluna DESCRICAO            OPERACIONAL                        NaN
PCMALHA  TEMPOMAXIMOEXECUCAO  NUMBER(10,0)                 Descricao coluna TEMPOMAXIMOEXECUCAO            OPERACIONAL                        NaN
PCMALHA        CRIADOSISTEMA   VARCHAR2(1)                       Descricao coluna CRIADOSISTEMA            OPERACIONAL                        NaN
PCMALHA DATAPRIMEIRAEXECUCAO          DATE                Descricao coluna DATAPRIMEIRAEXECUCAO            OPERACIONAL                        NaN
PCMALHA   DATAULTIMAEXECUCAO          DATE                  Descricao coluna DATAULTIMAEXECUCAO            OPERACIONAL                        NaN
PCMALHA      LIMITEUTILIZADO   VARCHAR2(1) Informacao do qual limite a malha pode ser executada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*