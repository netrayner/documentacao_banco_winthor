# 📊 Tabela: PCREINFR2060C

### Estrutura de Colunas e Restrições

       Tabela             Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2060C                 ID   NUMBER(8,0)                         Identificador do cabeçalho    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2060C            GRUPOID   NUMBER(8,0)                                  Grupo de empresas            OPERACIONAL                        NaN
PCREINFR2060C                MES   NUMBER(2,0)                 Mês em que o registro foi efetuado            OPERACIONAL                        NaN
PCREINFR2060C                ANO   NUMBER(4,0)                 Ano em que o registro foi efetuado            OPERACIONAL                        NaN
PCREINFR2060C      TIPOINSCRICAO   VARCHAR2(1)           Tipo de inscricao ultilizada no registro            OPERACIONAL                        NaN
PCREINFR2060C             RECIBO VARCHAR2(150)               Recibo de retorno da receita federal            OPERACIONAL                        NaN
PCREINFR2060C        DTALTERACAO          DATE       Data em que foi realizada a última alteração            OPERACIONAL                        NaN
PCREINFR2060C          CODFILIAL   VARCHAR2(2) Codigo da filial ao qual o registro está associado            OPERACIONAL                        NaN
PCREINFR2060C             ID_XML VARCHAR2(100)                                 Id do XML de envio            OPERACIONAL                        NaN
PCREINFR2060C RECUPERACAO_RECIBO  VARCHAR2(10)    Informaç.ão se o recibo foi obtido por consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*