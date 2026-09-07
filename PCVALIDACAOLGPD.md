# 📊 Tabela: PCVALIDACAOLGPD

### Estrutura de Colunas e Restrições

         Tabela       Coluna  Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVALIDACAOLGPD CODVALIDACAO   NUMBER(8,0)                                  Identificador único    CHAVE PRIMÁRIA (PK)                        NaN
PCVALIDACAOLGPD    CODTABELA   NUMBER(8,0)          Código que referência a tabela PCTABELALGPD CHAVE ESTRANGEIRA (FK)               PCTABELALGPD
PCVALIDACAOLGPD    DESCRICAO VARCHAR2(200)                               Descrição da validação            OPERACIONAL                        NaN
PCVALIDACAOLGPD          SQL          CLOB                       SQL responsável pela validação            OPERACIONAL                        NaN
PCVALIDACAOLGPD         HASH  VARCHAR2(32)             Hash para garantir a fidelidade do dados            OPERACIONAL                        NaN
PCVALIDACAOLGPD    MATRICULA   NUMBER(8,0) Código da matrícula do usuário que gravou o registro            OPERACIONAL                        NaN
PCVALIDACAOLGPD     DATAHORA          DATE                  Data e hora da gravação do registro            OPERACIONAL                        NaN
PCVALIDACAOLGPD     MENSAGEM          CLOB    Mensagem apresentada na validação da anonimização            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*