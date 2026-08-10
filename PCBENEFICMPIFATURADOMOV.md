# 📊 Tabela: PCBENEFICMPIFATURADOMOV

### Estrutura de Colunas e Restrições

                 Tabela                  Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICMPIFATURADOMOV             NUMTRANSENT NUMBER(10,0)                  Transação de entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICMPIFATURADOMOV               CODFORNEC NUMBER(10,0)                  Código do fornecedor CHAVE ESTRANGEIRA (FK)                   PCFORNEC
PCBENEFICMPIFATURADOMOV               CODFILIAL  VARCHAR2(2)                      Código da filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCBENEFICMPIFATURADOMOV               QTRETORNO NUMBER(18,6) Quantidade retornada da beneficiadora            OPERACIONAL                        NaN
PCBENEFICMPIFATURADOMOV                 QTSOBRA NUMBER(18,6)  Quantidade de sobra na beneficiadora            OPERACIONAL                        NaN
PCBENEFICMPIFATURADOMOV          QTRETORNOSOBRA NUMBER(18,6)         Quantidade de sobra retornada            OPERACIONAL                        NaN
PCBENEFICMPIFATURADOMOV          QTRETORNOPERDA NUMBER(18,6)         Quantidade de perda retornada            OPERACIONAL                        NaN
PCBENEFICMPIFATURADOMOV QTRETORNOSOBRADEVOLVIDA NUMBER(18,6)         Quantidade de sobra devolvida            OPERACIONAL                        NaN
PCBENEFICMPIFATURADOMOV              CODUSUARIO NUMBER(10,0)          Matricula usuario da entrada            OPERACIONAL                        NaN
PCBENEFICMPIFATURADOMOV       CODBENEFAGRUAPADO NUMBER(10,0)    Código agrupador de itens faturado    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*