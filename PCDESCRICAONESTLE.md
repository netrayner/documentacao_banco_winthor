# 📊 Tabela: PCDESCRICAONESTLE

### Estrutura de Colunas e Restrições

           Tabela         Coluna  Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESCRICAONESTLE   CODCATEGORIA   NUMBER(4,0)                             Código da categoria.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCRICAONESTLE CODLINHANESTLE   NUMBER(4,0)                          Código da linha Nestlé.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCRICAONESTLE      CODNESTLE  VARCHAR2(15)    Código de produtos terceiros, segmentos, etc.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCRICAONESTLE      DESCRICAO VARCHAR2(100) Descrição de produtos terceiros, segmentos, etc.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*