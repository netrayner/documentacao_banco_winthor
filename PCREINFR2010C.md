# 📊 Tabela: PCREINFR2010C

### Estrutura de Colunas e Restrições

       Tabela             Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2010C                 ID   NUMBER(8,0)                                   Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2010C            GRUPOID   NUMBER(8,0)                          Identificador do grupo            OPERACIONAL                        NaN
PCREINFR2010C                MES   NUMBER(8,0)                               Mês de referência            OPERACIONAL                        NaN
PCREINFR2010C                ANO   NUMBER(8,0)                               Ano de referência            OPERACIONAL                        NaN
PCREINFR2010C          CODFORNEC   NUMBER(8,0)                            Código do fornecedor            OPERACIONAL                        NaN
PCREINFR2010C       TIPOPARCEIRO   VARCHAR2(1)                                Tipo do parceiro            OPERACIONAL                        NaN
PCREINFR2010C          CODFILIAL   VARCHAR2(2)                                Código da filial            OPERACIONAL                        NaN
PCREINFR2010C             RECIBO VARCHAR2(150)               Numero de identificação do recibo            OPERACIONAL                        NaN
PCREINFR2010C      CODCONSTCIVIL   NUMBER(2,0)                      Código de construção civil            OPERACIONAL                        NaN
PCREINFR2010C        DTALTERACAO          DATE                               Data da alteração            OPERACIONAL                        NaN
PCREINFR2010C             ID_XML VARCHAR2(100)                              Id do XML de envio            OPERACIONAL                        NaN
PCREINFR2010C RECUPERACAO_RECIBO  VARCHAR2(10) Informaç.ão se o recibo foi obtido por consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*