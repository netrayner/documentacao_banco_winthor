# 📊 Tabela: PCTABESCRSPED

### Estrutura de Colunas e Restrições

       Tabela        Coluna   Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTABESCRSPED     SEQUENCIA   NUMBER(10,0)                                Sequência da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCTABESCRSPED        TABELA   VARCHAR2(20)                           Número da tabela no SPED            OPERACIONAL                        NaN
PCTABESCRSPED   DATAINIESCR           DATE Data Inicial da Escrituração conforme leiaute SPED            OPERACIONAL                        NaN
PCTABESCRSPED   DATAFINESCR           DATE   Data Final da Escrituração conforme leiaute SPED            OPERACIONAL                        NaN
PCTABESCRSPED     CODNATREC    VARCHAR2(3)    Código da Natureza da Receita da tabela no SPED            OPERACIONAL                        NaN
PCTABESCRSPED       CODPROD    NUMBER(6,0)                                  Código do Produto            OPERACIONAL                        NaN
PCTABESCRSPED  DESCRPRODUTO VARCHAR2(1000)                               Descrição do Produto            OPERACIONAL                        NaN
PCTABESCRSPED           NCM   VARCHAR2(20)               NCM - Nomenclatura Comum do Mercosul            OPERACIONAL                        NaN
PCTABESCRSPED     EMBALAGEM   VARCHAR2(50)                             Descrição da embalagem            OPERACIONAL                        NaN
PCTABESCRSPED        VOLUME  VARCHAR2(100)                                Descrição do volume            OPERACIONAL                        NaN
PCTABESCRSPED VOLUMEINICIAL   NUMBER(18,6)                   Valor numérico do Volume inicial            OPERACIONAL                        NaN
PCTABESCRSPED   VOLUMEFINAL   NUMBER(18,6)                     Valor numérico do Volume final            OPERACIONAL                        NaN
PCTABESCRSPED  TIPOREGISTRO    VARCHAR2(5) Tipo do Registro para ser filtrado caso necessário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*