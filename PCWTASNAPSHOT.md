# 📊 Tabela: PCWTASNAPSHOT

### Estrutura de Colunas e Restrições

       Tabela             Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWTASNAPSHOT                 ID NUMBER(12,0)         Identificador da Atualização    CHAVE PRIMÁRIA (PK)                        NaN
PCWTASNAPSHOT        DATACRIACAO TIMESTAMP(6)         Data de Execução do Snapshot            OPERACIONAL                        NaN
PCWTASNAPSHOT          EXECUTADO      CHAR(1) Se a restauração foi aplicada ou não            OPERACIONAL                        NaN
PCWTASNAPSHOT USUARIOATUALIZACAO VARCHAR2(50)   Usuário que executou a atualização            OPERACIONAL                        NaN
PCWTASNAPSHOT USUARIORESTAURACAO VARCHAR2(50)   Usuário que executou a restauração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*