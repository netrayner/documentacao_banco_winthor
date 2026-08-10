# 📊 Tabela: PCBENEFICESTOQUE

### Estrutura de Colunas e Restrições

          Tabela            Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICESTOQUE         CODFILIAL  VARCHAR2(2)                                 Código da filial    CHAVE PRIMÁRIA (PK)                   PCFILIAL
PCBENEFICESTOQUE         CODFORNEC NUMBER(10,0)                             Código do fornecedor    CHAVE PRIMÁRIA (PK)                   PCFORNEC
PCBENEFICESTOQUE           CODPROD NUMBER(10,0)                                Código do produto    CHAVE PRIMÁRIA (PK)                   PCPRODUT
PCBENEFICESTOQUE QTDEPOSSETERCEIRO NUMBER(18,6) Quantidade de materia prima em posse de terceiro            OPERACIONAL                        NaN
PCBENEFICESTOQUE       QTDESOBRAMP NUMBER(18,6)             Quantidade de sobra de materia prima            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*