# 📊 Tabela: PCEMBALAGEMECOMMERCE

### Estrutura de Colunas e Restrições

              Tabela                Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMBALAGEMECOMMERCE                    ID  NUMBER(10,0)         Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBALAGEMECOMMERCE                  NOME VARCHAR2(255)                 Nome da embalagem            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE        DESCRICAOCURTA VARCHAR2(255)          DescriÃ§Ã£o da embalagem            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE                 ORDEM   NUMBER(3,0)                Ordem da embalagem            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE           POSSUIGRADE   NUMBER(1,0)           Informa se possui grade            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE           CATEGORIAID  NUMBER(10,0)            Categoria da embalagem            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE               CODPROD   NUMBER(6,0)     Produdo associado a embalagem            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE                 ATIVO   NUMBER(1,0) Indica se a embalagem estÃ¡ ativa            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE                 BONUS  NUMBER(10,0)                Bonus da embalagem            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE          DEFINICAO1ID  NUMBER(10,0) Primeira definiÃ§Ã£o da embalagem            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE          DEFINICAO2ID  NUMBER(10,0)  Segunda definiÃ§Ã£o da embalagem            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE DATAULTIMAATUALIZACAO          DATE               Data de alteraÃ§Ã£o            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE                   URL VARCHAR2(255)                  URL da embalagem            OPERACIONAL                        NaN
PCEMBALAGEMECOMMERCE    PERCACRESCIMOPRECO  NUMBER(18,6)  Percentual de acrescimo no preço            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*