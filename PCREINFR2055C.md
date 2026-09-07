# 📊 Tabela: PCREINFR2055C

### Estrutura de Colunas e Restrições

       Tabela             Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2055C                 ID   NUMBER(8,0)                         Identificador do cabeçalho    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2055C            GRUPOID   NUMBER(8,0)                                  Grupo de empresas            OPERACIONAL                        NaN
PCREINFR2055C                MES   NUMBER(8,0)                 Mês em que o registro foi efetuado            OPERACIONAL                        NaN
PCREINFR2055C                ANO   NUMBER(8,0)                 Ano em que o registro foi efetuado            OPERACIONAL                        NaN
PCREINFR2055C          CODFILIAL   VARCHAR2(2) Codigo da filial ao qual o registro está associado            OPERACIONAL                        NaN
PCREINFR2055C      TIPOINSCRICAO   VARCHAR2(1)           Tipo de inscricao ultilizada no registro            OPERACIONAL                        NaN
PCREINFR2055C             RECIBO VARCHAR2(150)               Recibo de retorno da receita federal            OPERACIONAL                        NaN
PCREINFR2055C        DTALTERACAO          DATE       Data em que foi realizada a última alteração            OPERACIONAL                        NaN
PCREINFR2055C             ID_XML VARCHAR2(100)                                 Id do XML de envio            OPERACIONAL                        NaN
PCREINFR2055C RECUPERACAO_RECIBO  VARCHAR2(10)     Informação se o recibo foi obtido por consulta            OPERACIONAL                        NaN
PCREINFR2055C          CODFORNEC   NUMBER(8,0)                               Código do Fornecedor            OPERACIONAL                        NaN
PCREINFR2055C     INDAQPRODRURAL   VARCHAR2(1)          Indicativo de Aquisição do Produtor Rural            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*