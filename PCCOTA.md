# 📊 Tabela: PCCOTA

### Estrutura de Colunas e Restrições

Tabela              Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTA          CODCOTACAO   NUMBER(8,0)                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTA             CODPROD   NUMBER(8,0)                                NaN            OPERACIONAL                        NaN
PCCOTA             CODCONC   VARCHAR2(4)                                NaN            OPERACIONAL                        NaN
PCCOTA              CODCLI   NUMBER(8,0)                                NaN            OPERACIONAL                        NaN
PCCOTA               PUNIT  NUMBER(18,6)                       Vlr unitário            OPERACIONAL                        NaN
PCCOTA                DATA          DATE                                NaN            OPERACIONAL                        NaN
PCCOTA             CODUSUR   NUMBER(8,0)                                NaN            OPERACIONAL                        NaN
PCCOTA           NUMREGIAO   NUMBER(4,0)                                NaN            OPERACIONAL                        NaN
PCCOTA           CODFILIAL   VARCHAR2(2)                                NaN            OPERACIONAL                        NaN
PCCOTA             PTABELA  NUMBER(18,6)                                NaN            OPERACIONAL                        NaN
PCCOTA            CODPLPAG   NUMBER(4,0)                                NaN            OPERACIONAL                        NaN
PCCOTA               FONTE   VARCHAR2(1)                                NaN            OPERACIONAL                        NaN
PCCOTA            CUSTOFIN  NUMBER(18,6)                                NaN            OPERACIONAL                        NaN
PCCOTA           CUSTOREAL  NUMBER(18,6)                                NaN            OPERACIONAL                        NaN
PCCOTA               PRAZO   NUMBER(4,0)                                NaN            OPERACIONAL                        NaN
PCCOTA             DATADOC          DATE                                NaN            OPERACIONAL                        NaN
PCCOTA           PRECOCON1  NUMBER(10,2)                                NaN            OPERACIONAL                        NaN
PCCOTA           PRECOCON2  NUMBER(10,2)                                NaN            OPERACIONAL                        NaN
PCCOTA           PRECOCON3  NUMBER(10,2)                                NaN            OPERACIONAL                        NaN
PCCOTA           PRECOCON4  NUMBER(10,2)                                NaN            OPERACIONAL                        NaN
PCCOTA           PRECOCON5  NUMBER(10,2)                                NaN            OPERACIONAL                        NaN
PCCOTA                 OBS  VARCHAR2(30)                                NaN            OPERACIONAL                        NaN
PCCOTA             ESTOQUE   VARCHAR2(1)                                NaN            OPERACIONAL                        NaN
PCCOTA         CODAUXILIAR  NUMBER(16,0)                                NaN            OPERACIONAL                        NaN
PCCOTA               LISTA   NUMBER(6,0)                                NaN            OPERACIONAL                        NaN
PCCOTA  PERCMAXDESCMERCADO   NUMBER(7,4) Percentual máximo desconto mercado            OPERACIONAL                        NaN
PCCOTA                OBS2 VARCHAR2(500)                       OBSEVAÇÃO 2.            OPERACIONAL                        NaN
PCCOTA         CODPRODCONC   NUMBER(6,0)       Gravar o produto concorrente            OPERACIONAL                        NaN
PCCOTA           PUNITATAC  NUMBER(18,6)        Preço de atacado na cotação            OPERACIONAL                        NaN
PCCOTA         NUMPESQUISA  NUMBER(10,0)                 Número da pesquisa            OPERACIONAL                        NaN
PCCOTA TIPOEMBALAGEMPEDIDO   VARCHAR2(1)         Tipo da embalagem do item.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*