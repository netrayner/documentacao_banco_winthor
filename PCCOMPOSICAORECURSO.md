# 📊 Tabela: PCCOMPOSICAORECURSO

### Estrutura de Colunas e Restrições

             Tabela        Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMPOSICAORECURSO     CODFILIAL  VARCHAR2(2)        Refere-se ao código da filial da composição.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAORECURSO     IDRECURSO NUMBER(10,0)         Refere-se ao código do recurso de produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAORECURSO CODPRODMASTER  NUMBER(6,0)                  Código do produto a ser produzido.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAORECURSO        METODO  VARCHAR2(4)          Método de formulação do produto formulado.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAORECURSO     QTRECURSO NUMBER(18,6)        Quantidade de recurso utilizado na produção.            OPERACIONAL                        NaN
PCCOMPOSICAORECURSO  UTILIZAETAPA  VARCHAR2(1) Define se o recurso será contabilizado na produção.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*