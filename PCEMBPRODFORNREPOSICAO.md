# 📊 Tabela: PCEMBPRODFORNREPOSICAO

### Estrutura de Colunas e Restrições

                Tabela        Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMBPRODFORNREPOSICAO     CODFILIAL  VARCHAR2(2)               Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBPRODFORNREPOSICAO       CODPROD  NUMBER(6,0)              Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBPRODFORNREPOSICAO     CODFORNEC  NUMBER(6,0)           Código do Fornecedor    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBPRODFORNREPOSICAO      QTUNITCX  NUMBER(8,2)     Qtde. de unidades na caixa            OPERACIONAL                        NaN
PCEMBPRODFORNREPOSICAO PERCARREDONDA  NUMBER(5,2) Percentual para Arredondamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*