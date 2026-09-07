# 📊 Tabela: PCALCADACONTAGERENCIALI

### Estrutura de Colunas e Restrições

                 Tabela             Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCALCADACONTAGERENCIALI          CODFILIAL  VARCHAR2(2)                 Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGERENCIALI           CODCONTA NUMBER(10,0)        Código da conta gerencial    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGERENCIALI           CODAUTOR  NUMBER(8,0)  Código do autorizante principal    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGERENCIALI CODAUTORSECUNDARIO  NUMBER(8,0) Código do autorizante secundário    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGERENCIALI      CODUSUARIOINC  NUMBER(8,0)    Código do usuário que incluiu            OPERACIONAL                        NaN
PCALCADACONTAGERENCIALI         DTINCLUSAO         DATE   Data de inclusão do lançamento            OPERACIONAL                        NaN
PCALCADACONTAGERENCIALI            VLIMITE NUMBER(22,6)                  Valor do limite    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*