# 📊 Tabela: PCGMPARAMFILTROITEMNOVO

### Estrutura de Colunas e Restrições

                 Tabela    Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMPARAMFILTROITEMNOVO      ITEM VARCHAR2(50)                                      Item novo    CHAVE PRIMÁRIA (PK)                        NaN
PCGMPARAMFILTROITEMNOVO    CODIGO NUMBER(10,0) Código da combinação da parametrização da meta    CHAVE PRIMÁRIA (PK)            PCGMPARAMFILTRO
PCGMPARAMFILTROITEMNOVO    FILTRO  VARCHAR2(7)              Sigla do filtro da parametrização    CHAVE PRIMÁRIA (PK)            PCGMPARAMFILTRO
PCGMPARAMFILTROITEMNOVO GEROUMETA  VARCHAR2(1)                           Se gerou meta ou não            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*