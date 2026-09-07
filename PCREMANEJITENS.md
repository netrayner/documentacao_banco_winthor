# 📊 Tabela: PCREMANEJITENS

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho                                                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREMANEJITENS CODREMANEJI NUMBER(10,0) Código que identifica a combinação: nº pedido, cod. Filial origem, cod. Filial destino e nº remessa remanejamento.    CHAVE PRIMÁRIA (PK)                 PCREMANEJD
PCREMANEJITENS     CODPROD  NUMBER(6,0)                                                                                                 Código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCREMANEJITENS          QT NUMBER(14,4)                                                                                             Quantidade remanejada.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*