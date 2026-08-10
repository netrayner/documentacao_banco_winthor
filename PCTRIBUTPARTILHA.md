# 📊 Tabela: PCTRIBUTPARTILHA

### Estrutura de Colunas e Restrições

          Tabela        Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBUTPARTILHA         CODST  NUMBER(4,0)                     Código da figura tributária    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTPARTILHA            UF  VARCHAR2(2)             UF do estado de destino da partilha    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBUTPARTILHA CODSTPARTILHA  NUMBER(4,0) Figura tributária do estado destino da partilha            OPERACIONAL                        NaN
PCTRIBUTPARTILHA    DTMXSALTER         DATE                                             NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*