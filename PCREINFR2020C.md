# 📊 Tabela: PCREINFR2020C

### Estrutura de Colunas e Restrições

       Tabela             Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2020C                 ID   NUMBER(8,0)                                   Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2020C            GRUPOID   NUMBER(8,0)                          Identificador do grupo            OPERACIONAL                        NaN
PCREINFR2020C                MES   NUMBER(8,0)                               Mês de referência            OPERACIONAL                        NaN
PCREINFR2020C                ANO   NUMBER(8,0)                               Ano de referência            OPERACIONAL                        NaN
PCREINFR2020C         CODCLIENTE   NUMBER(8,0)                               Código do cliente            OPERACIONAL                        NaN
PCREINFR2020C          CODFILIAL   VARCHAR2(2)                                Código da filial            OPERACIONAL                        NaN
PCREINFR2020C             RECIBO VARCHAR2(150)                                Número do recibo            OPERACIONAL                        NaN
PCREINFR2020C        DTALTERACAO          DATE                               Data de alteração            OPERACIONAL                        NaN
PCREINFR2020C             ID_XML VARCHAR2(100)                              Id do XML de envio            OPERACIONAL                        NaN
PCREINFR2020C RECUPERACAO_RECIBO  VARCHAR2(10) Informaç.ão se o recibo foi obtido por consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*