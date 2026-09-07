# 📊 Tabela: PCCOTAFV

### Estrutura de Colunas e Restrições

  Tabela             Coluna  Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTAFV            CODPROD   NUMBER(8,0)                        Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAFV             NUMSEQ  NUMBER(20,0)                    Sequencial do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAFV            CODCONC  VARCHAR2(40)                    Codigo do Concorrente    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAFV             CGCCLI  VARCHAR2(18)                           CGC do cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAFV            CODUSUR   NUMBER(8,0)                            Codigo do rca    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAFV               DATA          DATE                                     Data    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAFV             CODCLI   NUMBER(8,0)                        Codigo do cliente            OPERACIONAL                        NaN
PCCOTAFV      OBSERVACAO_PC VARCHAR2(300)           Mensagem de retorno da package            OPERACIONAL                        NaN
PCCOTAFV          IMPORTADO   NUMBER(1,0)           Flag de controle de importação            OPERACIONAL                        NaN
PCCOTAFV              PUNIT  NUMBER(18,6)                             Preço cotado            OPERACIONAL                        NaN
PCCOTAFV          NUMREGIAO   NUMBER(4,0)                         Numero da regiao            OPERACIONAL                        NaN
PCCOTAFV          CODFILIAL   VARCHAR2(2)                         Codigo da Filial            OPERACIONAL                        NaN
PCCOTAFV            PTABELA  NUMBER(18,6)        Preço de tabela do produto cotado            OPERACIONAL                        NaN
PCCOTAFV           CODPLPAG   NUMBER(4,0)             Codigo do plano de pagamento            OPERACIONAL                        NaN
PCCOTAFV           CUSTOFIN  NUMBER(18,6)                         Custo Financeiro            OPERACIONAL                        NaN
PCCOTAFV          CUSTOREAL  NUMBER(18,6)                               Custo Real            OPERACIONAL                        NaN
PCCOTAFV              PRAZO   NUMBER(4,0)                                    Prazo            OPERACIONAL                        NaN
PCCOTAFV            DATADOC          DATE                           Data Documento            OPERACIONAL                        NaN
PCCOTAFV          PRECOCON1  NUMBER(10,2)                      Preço concorrente 1            OPERACIONAL                        NaN
PCCOTAFV          PRECOCON2  NUMBER(10,2)                      Preço concorrente 2            OPERACIONAL                        NaN
PCCOTAFV          PRECOCON3  NUMBER(10,2)                      Preço concorrente 3            OPERACIONAL                        NaN
PCCOTAFV          PRECOCON4  NUMBER(10,2)                      Preço concorrente 4            OPERACIONAL                        NaN
PCCOTAFV          PRECOCON5  NUMBER(10,2)                      Preço concorrente 5            OPERACIONAL                        NaN
PCCOTAFV                OBS  VARCHAR2(30)                               observação            OPERACIONAL                        NaN
PCCOTAFV               OBS2 VARCHAR2(500)                             Observação 2            OPERACIONAL                        NaN
PCCOTAFV            ESTOQUE   VARCHAR2(1)             Flag de indicação de estoque            OPERACIONAL                        NaN
PCCOTAFV        CODAUXILIAR  NUMBER(20,0)                          Codigo Auxiliar            OPERACIONAL                        NaN
PCCOTAFV              LISTA   NUMBER(6,0)                                    Lista            OPERACIONAL                        NaN
PCCOTAFV PERCMAXDESCMERCADO   NUMBER(7,4) Percentual Maximo de desconto do Mercado            OPERACIONAL                        NaN
PCCOTAFV        CODPRODCONC   NUMBER(6,0)         Codigo do produto no concorrente            OPERACIONAL                        NaN
PCCOTAFV         DTINCLUSAO          DATE              Data de inclusão da Cotação            OPERACIONAL                        NaN
PCCOTAFV        DTALTERACAO          DATE             Data de Alteração da Cotação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*