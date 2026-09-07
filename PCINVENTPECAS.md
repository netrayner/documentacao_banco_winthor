# 📊 Tabela: PCINVENTPECAS

### Estrutura de Colunas e Restrições

       Tabela    Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINVENTPECAS NUMINVENT  NUMBER(8,0)            Numero de inventario    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTPECAS      DATA         DATE              Data do inventario            OPERACIONAL                        NaN
PCINVENTPECAS CODFILIAL  VARCHAR2(2) Codigo da filial ldo inventario    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTPECAS   CODPROD  NUMBER(6,0)               Codigo do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTPECAS    IDPECA  NUMBER(9,0)           Identificação da peça    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTPECAS      PESO NUMBER(14,8)          Peso do produto pesado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*