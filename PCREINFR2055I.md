# 📊 Tabela: PCREINFR2055I

### Estrutura de Colunas e Restrições

       Tabela             Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2055I                 ID   NUMBER(8,0)                                 Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2055I          R2055C_ID   NUMBER(8,0)                 Identificador R2055 cabeçalho CHAVE ESTRANGEIRA (FK)              PCREINFR2055C
PCREINFR2055I             STATUS VARCHAR2(100)                                        Status            OPERACIONAL                        NaN
PCREINFR2055I FORMATRIBPRODRURAL   VARCHAR2(1)    Forma de tributação para Produtores Rurais            OPERACIONAL                        NaN
PCREINFR2055I     INDAQPRODRURAL   VARCHAR2(1)     Indicativo da aquisição da produção rural            OPERACIONAL                        NaN
PCREINFR2055I        NUMTRANSENT  NUMBER(10,0)                   Numero de transação da nota            OPERACIONAL                        NaN
PCREINFR2055I       VLRTOTALNOTA  NUMBER(12,2)                           Valor total da nota            OPERACIONAL                        NaN
PCREINFR2055I VLRCONTRIBPREVDESC  NUMBER(12,2) Valor da contribuição previdencial descontada            OPERACIONAL                        NaN
PCREINFR2055I  VLRCONTRIBBENCONC  NUMBER(12,2)  Valor da contribuição do beneficio concedido            OPERACIONAL                        NaN
PCREINFR2055I    VLRCONTRIBSENAR  NUMBER(12,2)                      Valor contribuição SENAR            OPERACIONAL                        NaN
PCREINFR2055I        VLRPROCESSO  NUMBER(12,2)                             Valor do processo            OPERACIONAL                        NaN
PCREINFR2055I          CODFORNEC   NUMBER(8,0)                          Código do Fornecedor            OPERACIONAL                        NaN
PCREINFR2055I        RETIFICACAO   VARCHAR2(1)          Controle de processo em retificação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*