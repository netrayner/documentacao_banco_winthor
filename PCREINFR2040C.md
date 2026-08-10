# 📊 Tabela: PCREINFR2040C

### Estrutura de Colunas e Restrições

       Tabela             Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2040C                 ID   NUMBER(8,0)                                   Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2040C            GRUPOID   NUMBER(8,0)                          Identificador do grupo            OPERACIONAL                        NaN
PCREINFR2040C                MES   NUMBER(8,0)                               Mês de referência            OPERACIONAL                        NaN
PCREINFR2040C                ANO   NUMBER(8,0)                               Ano de referência            OPERACIONAL                        NaN
PCREINFR2040C        CODPARCEIRO   NUMBER(8,0)                              Código do parceiro            OPERACIONAL                        NaN
PCREINFR2040C          CODFILIAL   VARCHAR2(2)                                Codigo da filial            OPERACIONAL                        NaN
PCREINFR2040C             RECIBO VARCHAR2(150)                                Número do recibo            OPERACIONAL                        NaN
PCREINFR2040C        DTALTERACAO          DATE                               Data de alteração            OPERACIONAL                        NaN
PCREINFR2040C             ID_XML VARCHAR2(100)                              Id do XML de envio            OPERACIONAL                        NaN
PCREINFR2040C RECUPERACAO_RECIBO  VARCHAR2(10) Informaç.ão se o recibo foi obtido por consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*