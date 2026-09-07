# 📊 Tabela: PCCONFORDENACAOOSWMS

### Estrutura de Colunas e Restrições

              Tabela                  Coluna  Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFORDENACAOOSWMS            CODORDENACAO   NUMBER(4,0)                                      Código da ordenação    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFORDENACAOOSWMS                   CODOS   NUMBER(4,0)                                   Código do tipo da o.s.            OPERACIONAL                        NaN
PCCONFORDENACAOOSWMS                TIPO_DOC   VARCHAR2(2)                        Tipo do documento - o.s./etiqueta            OPERACIONAL                        NaN
PCCONFORDENACAOOSWMS                OPERACAO   VARCHAR2(1)                         Tipo da operação - entrada/saída            OPERACIONAL                        NaN
PCCONFORDENACAOOSWMS             AGRUPAMENTO   VARCHAR2(2)                            Agrupamento definito - vários            OPERACIONAL                        NaN
PCCONFORDENACAOOSWMS                 ORDERBY VARCHAR2(250)                                  Cláusula order by final            OPERACIONAL                        NaN
PCCONFORDENACAOOSWMS           ORDERBY_ITENS VARCHAR2(250)                                Ordenação dos itens da OS            OPERACIONAL                        NaN
PCCONFORDENACAOOSWMS TIPO_CONF_ORDERBY_ITENS       CHAR(2) Tipo de configuração utilizada para ordernação dos itens            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*