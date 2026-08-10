# 📊 Tabela: PCLOGINFOEQUIPAMENTO

### Estrutura de Colunas e Restrições

              Tabela      Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGINFOEQUIPAMENTO EQUIPAMENTO VARCHAR2(60)              Identificação do equipamento    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGINFOEQUIPAMENTO      SERVER  VARCHAR2(1) Identifica se o equipamento é um servidor    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGINFOEQUIPAMENTO        INFO         CLOB                Informações do equipamento            OPERACIONAL                        NaN
PCLOGINFOEQUIPAMENTO        DATA         DATE                               Data do log    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*