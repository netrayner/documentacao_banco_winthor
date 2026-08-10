# 📊 Tabela: PCGMMETA

### Estrutura de Colunas e Restrições

  Tabela          Coluna Tipo/Tamanho                                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMMETA          CODIGO NUMBER(10,0)                                                                                                   Código da meta    CHAVE PRIMÁRIA (PK)                        NaN
PCGMMETA    CODPARAMMETA NUMBER(10,0)                                                                                 Código da parametrização da meta CHAVE ESTRANGEIRA (FK)              PCGMPARAMMETA
PCGMMETA CODENTIDADEMETA VARCHAR2(10)                                                                                   Código da entidade colaborador            OPERACIONAL                        NaN
PCGMMETA        SITUACAO  VARCHAR2(2) Situação da meta ('L' Liberada, 'I' Iniciada, 'PE' Pendente, 'PS' Pendente Superior, 'A' Aprovada, 'R' Reanálise            OPERACIONAL                        NaN
PCGMMETA      DATAEDICAO         DATE                                                                                           Data da edição da meta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*