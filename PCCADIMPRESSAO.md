# 📊 Tabela: PCCADIMPRESSAO

### Estrutura de Colunas e Restrições

        Tabela            Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCADIMPRESSAO            CODIMP   NUMBER(6,0)                CÓD. CADASTRO DE IMPRESSAO            OPERACIONAL                        NaN
PCCADIMPRESSAO         CODFILIAL   VARCHAR2(2)                            CÓD. DA FILIAL            OPERACIONAL                        NaN
PCCADIMPRESSAO          CODDEPTO   NUMBER(6,0)                      CÓD. DO DEPARTAMENTO            OPERACIONAL                        NaN
PCCADIMPRESSAO            CODSEC   NUMBER(6,0)                                CÓD. SEÇÃO            OPERACIONAL                        NaN
PCCADIMPRESSAO      CODCATEGORIA   NUMBER(6,0)                            CÓD. CATEGORIA            OPERACIONAL                        NaN
PCCADIMPRESSAO   CODSUBCATEGORIA   NUMBER(6,0)                         CÓD. SUBCATEGORIA            OPERACIONAL                        NaN
PCCADIMPRESSAO           CODPROD   NUMBER(6,0)                              CÓD. PRODUTO            OPERACIONAL                        NaN
PCCADIMPRESSAO            STATUS   VARCHAR2(1)                          STATUS IMPRESSÃO            OPERACIONAL                        NaN
PCCADIMPRESSAO CODFUNCINATIVACAO   NUMBER(6,0)                     CÓD. FUNC. INATIVAÇÃO            OPERACIONAL                        NaN
PCCADIMPRESSAO      DTINATIVACAO          DATE                           DATA INATIVAÇÃO            OPERACIONAL                        NaN
PCCADIMPRESSAO  MOTIVOINATIVACAO  VARCHAR2(90)                         MOTIVO INATIVAÇÃO            OPERACIONAL                        NaN
PCCADIMPRESSAO       CODAUXILIAR  NUMBER(20,0)                            CÓD. EMBALAGEM            OPERACIONAL                        NaN
PCCADIMPRESSAO        IMPRESSORA VARCHAR2(150)                      DESCRIÇÃO IMPRESSORA            OPERACIONAL                        NaN
PCCADIMPRESSAO     IMPRESSORAANT VARCHAR2(150)                       Impressora Anterior            OPERACIONAL                        NaN
PCCADIMPRESSAO               RUA   NUMBER(4,0)      Rua para qual se define a impressão.            OPERACIONAL                        NaN
PCCADIMPRESSAO            MODULO   NUMBER(2,0)   Módulo para qual se define a impressão.            OPERACIONAL                        NaN
PCCADIMPRESSAO       CODDEPOSITO  NUMBER(10,0) Depósito para qual se define a impressão.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*