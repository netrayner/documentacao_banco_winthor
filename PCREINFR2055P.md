# 📊 Tabela: PCREINFR2055P

### Estrutura de Colunas e Restrições

       Tabela         Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2055P             ID NUMBER(22,0)                              Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2055P     IDPROCESSO  NUMBER(8,0)                           Código do processo            OPERACIONAL                        NaN
PCREINFR2055P      R2055I_ID  NUMBER(8,0) Chave estrangeira com a tabela PCREINFR2055I CHAVE ESTRANGEIRA (FK)              PCREINFR2055I
PCREINFR2055P   TIPOPROCESSO  NUMBER(8,0)                             Tipo do processo            OPERACIONAL                        NaN
PCREINFR2055P    NUMPROCESSO VARCHAR2(21)                           Número do processo            OPERACIONAL                        NaN
PCREINFR2055P    VLRPROCESSO NUMBER(12,2)                            Valor do processo            OPERACIONAL                        NaN
PCREINFR2055P VLRCONTRIBPREV NUMBER(12,2)           Valor da contribuição previdencial            OPERACIONAL                        NaN
PCREINFR2055P      VLRGILRAT NUMBER(12,2)                              Valor do GILRAT            OPERACIONAL                        NaN
PCREINFR2055P       VLRSENAR NUMBER(12,2)                               Valor do SENAR            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*