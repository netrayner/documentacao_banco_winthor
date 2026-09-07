# 📊 Tabela: PCCOTACAOSESII

### Estrutura de Colunas e Restrições

        Tabela       Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTACAOSESII   CODCOTACAO NUMBER(10,0)           Código da cotação.    CHAVE PRIMÁRIA (PK)              PCCOTACAOSESI
PCCOTACAOSESII     CODBARRA NUMBER(14,0)    Código de barras do item.            OPERACIONAL                        NaN
PCCOTACAOSESII         QTDE NUMBER(10,3)        Qtde item na cotação.            OPERACIONAL                        NaN
PCCOTACAOSESII      CODPROD  NUMBER(6,0)           Codigo do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTACAOSESII VLREFERENCIA NUMBER(10,2) Valor de referência do item.            OPERACIONAL                        NaN
PCCOTACAOSESII    VLCOTACAO NUMBER(10,2)    Valor de cotação do item.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*