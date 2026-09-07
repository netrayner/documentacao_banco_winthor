# 📊 Tabela: PCMONITORBANCO

### Estrutura de Colunas e Restrições

        Tabela         Coluna  Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMONITORBANCO     CODMONITOR  NUMBER(10,0)                              Identificador único    CHAVE PRIMÁRIA (PK)                        NaN
PCMONITORBANCO      DESCRICAO VARCHAR2(250)      Descrição de identificação do monitoramento            OPERACIONAL                        NaN
PCMONITORBANCO           DATA          DATE                  Data do início do monitoramento            OPERACIONAL                        NaN
PCMONITORBANCO CODFUNCMONITOR   NUMBER(8,0) Código do funcionário que inciou o monitoramento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*