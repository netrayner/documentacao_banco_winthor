# 📊 Tabela: PCESTEIRAWMS

### Estrutura de Colunas e Restrições

      Tabela       Coluna  Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTEIRAWMS       CODIGO   NUMBER(6,0)                                               Código da Esteira.    CHAVE PRIMÁRIA (PK)                        NaN
PCESTEIRAWMS    DESCRICAO VARCHAR2(100)                                             Descrição da Esteira            OPERACIONAL                        NaN
PCESTEIRAWMS         ROTA   NUMBER(4,0)                                                  Rota da Esteira            OPERACIONAL                        NaN
PCESTEIRAWMS   DTULTALTER          DATE                 Data da última alteração do registro da esteira.            OPERACIONAL                        NaN
PCESTEIRAWMS CODFUNCALTER   NUMBER(8,0) Código do usuário que fez a última alteração do reg. da esteira.            OPERACIONAL                        NaN
PCESTEIRAWMS   DTEXCLUSAO          DATE                                     Data de Exclusão do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*