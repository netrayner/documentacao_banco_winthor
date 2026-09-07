# 📊 Tabela: PCAUTORCLIENTE

### Estrutura de Colunas e Restrições

        Tabela          Coluna  Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTORCLIENTE          CODCLI   NUMBER(6,0)                        Código cliente PC    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTORCLIENTE     DEVEVALIDAR   VARCHAR2(1) Flag para verificar se assina o registro            OPERACIONAL                        NaN
PCAUTORCLIENTE            HASH VARCHAR2(100)                     Hash das informações            OPERACIONAL                        NaN
PCAUTORCLIENTE DATAATUALIZACAO          DATE          Data da atualização do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*