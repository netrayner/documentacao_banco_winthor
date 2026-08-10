# 📊 Tabela: PCWTASNAPSHOTSTATE

### Estrutura de Colunas e Restrições

            Tabela      Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWTASNAPSHOTSTATE  SNAPSHOTID  NUMBER(12,0) Identificador da Atualização CHAVE ESTRANGEIRA (FK)              PCWTASNAPSHOT
PCWTASNAPSHOTSTATE        NOME  VARCHAR2(40)               Nome do Pacote            OPERACIONAL                        NaN
PCWTASNAPSHOTSTATE      VERSAO  VARCHAR2(20)             Versão do Pacote            OPERACIONAL                        NaN
PCWTASNAPSHOTSTATE REPOSITORIO VARCHAR2(255)        Repositório do Pacote            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*