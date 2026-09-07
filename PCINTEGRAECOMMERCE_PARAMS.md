# 📊 Tabela: PCINTEGRAECOMMERCE_PARAMS

### Estrutura de Colunas e Restrições

                   Tabela    Coluna  Tipo/Tamanho                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRAECOMMERCE_PARAMS        ID  NUMBER(10,0)                                  Identificador da chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRAECOMMERCE_PARAMS    CODIGO  NUMBER(20,0)                                                       Código identificador            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_PARAMS CODLAYOUT   NUMBER(6,0)             Código do layout referente a tabela PCINTEGRAECOMMERCE_LAYOUTI CHAVE ESTRANGEIRA (FK) PCINTEGRAECOMMERCE_LAYOUTC
PCINTEGRAECOMMERCE_PARAMS CODFILIAL   VARCHAR2(2)                        Código da Filial se null corresponde a filial GERAL            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_PARAMS      TIPO  VARCHAR2(25)          Tipo de configurações disponíveis. (CREEDENCIAS, CONFIGURAÇÕES)\t            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_PARAMS NOMECAMPO  VARCHAR2(50) Nome do campo a ser utilizado na integração (ex: userrcode, id de loja...)            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_PARAMS     VALOR VARCHAR2(200)                              Valor do campo a ser utilizado na integração.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*