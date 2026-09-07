# 📊 Tabela: PCTIPOCONFIGURACAO

### Estrutura de Colunas e Restrições

            Tabela               Coluna  Tipo/Tamanho                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPOCONFIGURACAO  CODTIPOCONFIGURACAO   NUMBER(5,0)                                                              Chave do tipo de configuração    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPOCONFIGURACAO     TIPOCONFIGURACAO  VARCHAR2(50) String que representa o dado de tipo de configuração de forma mais resumida e programatica            OPERACIONAL                        NaN
PCTIPOCONFIGURACAO DESCTIPOCONFIGURACAO VARCHAR2(100)                                                   String que  representa o dado humanizado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*