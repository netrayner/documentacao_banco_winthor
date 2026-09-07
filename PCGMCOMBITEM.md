# 📊 Tabela: PCGMCOMBITEM

### Estrutura de Colunas e Restrições

      Tabela Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMCOMBITEM CODIGO NUMBER(10,0)           Código da combinação da meta    CHAVE PRIMÁRIA (PK)             PCGMCOMBINACAO
PCGMCOMBITEM FILTRO  VARCHAR2(7)  Sigla do tipo de filtro da combinação    CHAVE PRIMÁRIA (PK)                        NaN
PCGMCOMBITEM   ITEM VARCHAR2(50) Item da combinação, entidade do filtro    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*