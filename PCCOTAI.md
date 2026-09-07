# 📊 Tabela: PCCOTAI

### Estrutura de Colunas e Restrições

 Tabela          Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTAI     NUMPESQUISA  NUMBER(10,0)                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAI       CODCONCOR   VARCHAR2(4)                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAI         CODPROD   NUMBER(6,0)                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAI           PUNIT  NUMBER(18,6)                                           NaN            OPERACIONAL                        NaN
PCCOTAI        DATALANC          DATE                                           NaN            OPERACIONAL                        NaN
PCCOTAI         PTABELA  NUMBER(18,6)                                           NaN            OPERACIONAL                        NaN
PCCOTAI     CODFUNCLANC   NUMBER(8,0)                                           NaN            OPERACIONAL                        NaN
PCCOTAI        CUSTOFIN  NUMBER(18,6)                                           NaN            OPERACIONAL                        NaN
PCCOTAI       CUSTOREAL  NUMBER(18,6)                                           NaN            OPERACIONAL                        NaN
PCCOTAI       DESCRICAO  VARCHAR2(40)                                           NaN            OPERACIONAL                        NaN
PCCOTAI     CUSTOULTENT  NUMBER(18,6)                                           NaN            OPERACIONAL                        NaN
PCCOTAI PVENDAEMBALAGEM  NUMBER(18,6) Preço de venda atual da embalagem do produto.            OPERACIONAL                        NaN
PCCOTAI   PVENDAPRODUTO  NUMBER(18,6)              Preço de venda atual do produto.            OPERACIONAL                        NaN
PCCOTAI     CODAUXILIAR  NUMBER(16,0)  Código auxiliar da embalagem que foi cotada.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAI       CODFILIAL   VARCHAR2(2) Código da filial que foi realizado a cotação.            OPERACIONAL                        NaN
PCCOTAI       PUNITATAC  NUMBER(18,6)                   Preço de atacado na cotação            OPERACIONAL                        NaN
PCCOTAI   PVENDAATACADO  NUMBER(18,6) Valor para gravar o preço de venda do atacado            OPERACIONAL                        NaN
PCCOTAI      OBSDECISAO VARCHAR2(100)           Observação sobre tomada de decisão.            OPERACIONAL                        NaN
PCCOTAI        PDECISAO  NUMBER(18,6)                   Preço de tomada de decisão.            OPERACIONAL                        NaN
PCCOTAI        EMOFERTA   VARCHAR2(1)                                     Em Oferta            OPERACIONAL                        NaN
PCCOTAI  GATILHOATACADO  VARCHAR2(50)                               Gatilho Atacado            OPERACIONAL                        NaN
PCCOTAI    VALORGATILHO  NUMBER(18,6)                                 Valor Gatilho            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*