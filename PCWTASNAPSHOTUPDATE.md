# 📊 Tabela: PCWTASNAPSHOTUPDATE

### Estrutura de Colunas e Restrições

             Tabela      Coluna  Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWTASNAPSHOTUPDATE  SNAPSHOTID  NUMBER(12,0)  Identificador da Atualização CHAVE ESTRANGEIRA (FK)              PCWTASNAPSHOT
PCWTASNAPSHOTUPDATE        NOME  VARCHAR2(40)                Nome do Pacote            OPERACIONAL                        NaN
PCWTASNAPSHOTUPDATE      VERSAO  VARCHAR2(20)              Versão do Pacote            OPERACIONAL                        NaN
PCWTASNAPSHOTUPDATE REPOSITORIO VARCHAR2(255)         Repositório do Pacote            OPERACIONAL                        NaN
PCWTASNAPSHOTUPDATE        ACAO  VARCHAR2(20) Ação realizada na atualização            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*