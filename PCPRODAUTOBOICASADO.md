# 📊 Tabela: PCPRODAUTOBOICASADO

### Estrutura de Colunas e Restrições

             Tabela            Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODAUTOBOICASADO   NUMTRANSENTORIG NUMBER(10,0)                                   Numtransent da nota de entrada            OPERACIONAL                        NaN
PCPRODAUTOBOICASADO       CODCONTORIG NUMBER(10,0)                                 Cód. Contábil da nota de entrada            OPERACIONAL                        NaN
PCPRODAUTOBOICASADO   NUMTRANSENTDEST NUMBER(10,0)                                  Numtransent da nota de produção            OPERACIONAL                        NaN
PCPRODAUTOBOICASADO       CODCONTDEST NUMBER(10,0)                                Cód. Contábil da nota de produção            OPERACIONAL                        NaN
PCPRODAUTOBOICASADO              DATA         DATE                                                 Data da produção            OPERACIONAL                        NaN
PCPRODAUTOBOICASADO NUMTRANSVENDAORIG NUMBER(10,0) número da transação de venda que gerou a movimentação de estoque            OPERACIONAL                        NaN
PCPRODAUTOBOICASADO NUMTRANSVENDADEST NUMBER(10,0)   número da transação de venda para onde foi destinado o estoque            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*