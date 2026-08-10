# 📊 Tabela: PCCLASSIFICMERC

### Estrutura de Colunas e Restrições

         Tabela           Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLASSIFICMERC CODCLASSIFICMERC  NUMBER(6,0)                    Chave primaria para a tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCCLASSIFICMERC        CODFILIAL  VARCHAR2(2) Representa para qual filial sera válido a regra.            OPERACIONAL                        NaN
PCCLASSIFICMERC         CODDEPTO  NUMBER(6,0)          Departamento vinculado a classificacao.            OPERACIONAL                        NaN
PCCLASSIFICMERC           CODSEC  NUMBER(6,0)                 Seção vinculada a classificacao.            OPERACIONAL                        NaN
PCCLASSIFICMERC     CODCATEGORIA  NUMBER(6,0)             Categoria vinculada a classificacao.            OPERACIONAL                        NaN
PCCLASSIFICMERC  CODSUBCATEGORIA  NUMBER(6,0)         Sub Categoria vinculada a classificacao.            OPERACIONAL                        NaN
PCCLASSIFICMERC          CODPROD  NUMBER(6,0)               Produto vinculado a classificacao.            OPERACIONAL                        NaN
PCCLASSIFICMERC     MARGEMVAREJO  NUMBER(6,2)             Margem para sugerir preço de varejo.            OPERACIONAL                        NaN
PCCLASSIFICMERC       MARGEMATAC  NUMBER(6,2)            Margem para sugerir preço de atacado.            OPERACIONAL                        NaN
PCCLASSIFICMERC  MARGEMMINVAREJO  NUMBER(6,2)         Margem minima para sugerir preco varejo.            OPERACIONAL                        NaN
PCCLASSIFICMERC    MARGEMMINATAC  NUMBER(6,2)     Margem minima para sugerir preco de atacado.            OPERACIONAL                        NaN
PCCLASSIFICMERC            CODST  NUMBER(4,0)                   Codigo da Situacao tributaria.            OPERACIONAL                        NaN
PCCLASSIFICMERC     CODCOMPRADOR  NUMBER(8,0)                              Código do comprador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*