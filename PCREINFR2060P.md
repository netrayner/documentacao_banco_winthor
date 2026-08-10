# 📊 Tabela: PCREINFR2060P

### Estrutura de Colunas e Restrições

       Tabela      Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2060P          ID NUMBER(22,0)                              Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2060P  IDPROCESSO  NUMBER(8,0)                           Código do processo            OPERACIONAL                        NaN
PCREINFR2060P   R2060I_ID  NUMBER(8,0) Chave estrangeira com a tabela PCREINFR2060I            OPERACIONAL                        NaN
PCREINFR2060P TIPPROCESSO  NUMBER(8,0)                             Tipo do processo            OPERACIONAL                        NaN
PCREINFR2060P NUMPROCESSO VARCHAR2(21)                           Número do processo            OPERACIONAL                        NaN
PCREINFR2060P VLRPROCESSO NUMBER(12,2)                            Valor do processo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*