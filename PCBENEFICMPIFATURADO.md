# 📊 Tabela: PCBENEFICMPIFATURADO

### Estrutura de Colunas e Restrições

              Tabela            Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICMPIFATURADO         CODFORNEC NUMBER(10,0)                  Código do fornecedor CHAVE ESTRANGEIRA (FK)                   PCFORNEC
PCBENEFICMPIFATURADO         CODFILIAL  VARCHAR2(2)                      Código da filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCBENEFICMPIFATURADO    QTMATERIAPRIMA NUMBER(18,6)    Quantidade materia prima utilizada            OPERACIONAL                        NaN
PCBENEFICMPIFATURADO  QTSOBRAUTILIZADA NUMBER(18,6)            Quantidade sobra utilizada            OPERACIONAL                        NaN
PCBENEFICMPIFATURADO         QTRETORNO NUMBER(18,6) Quantidade retornada da beneficiadora            OPERACIONAL                        NaN
PCBENEFICMPIFATURADO    QTRETORNOSOBRA NUMBER(18,6)         Quantidade de sobra retornada            OPERACIONAL                        NaN
PCBENEFICMPIFATURADO    QTRETORNOPERDA NUMBER(18,6)         Quantidade de perda retornada            OPERACIONAL                        NaN
PCBENEFICMPIFATURADO CODBENEFAGRUAPADO NUMBER(10,0)    Código agrupador de itens faturado    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*