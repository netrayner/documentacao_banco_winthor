# 📊 Tabela: PCVERBACONTRATOF

### Estrutura de Colunas e Restrições

          Tabela        Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVERBACONTRATOF   NUMCONTRATO NUMBER(12,0)                       Número do contrato.    CHAVE PRIMÁRIA (PK)           PCVERBACONTRATOC
PCVERBACONTRATOF     CODFILIAL  VARCHAR2(2)                         Código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCVERBACONTRATOF    DTINCLUSAO         DATE  Data de inclusão do contrato no sistema.            OPERACIONAL                        NaN
PCVERBACONTRATOF    DTEXCLUSAO         DATE                Data exclusão do contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOF CODUSUARIOINC  NUMBER(6,0) Código do usuário que incluiu o contrato.            OPERACIONAL                        NaN
PCVERBACONTRATOF CODUSUARIOEXC  NUMBER(6,0) Código do usuário que excluiu o contrato.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*