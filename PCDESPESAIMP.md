# 📊 Tabela: PCDESPESAIMP

### Estrutura de Colunas e Restrições

      Tabela      Coluna Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESPESAIMP  CODDESPESA NUMBER(10,0)                               Código da Despesa de Importação.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESPESAIMP   DESCRICAO VARCHAR2(40)                            Descrição da Despesa de Importação.            OPERACIONAL                        NaN
PCDESPESAIMP CODSISCOMEX NUMBER(10,0)                      Código SISCOMEX da Despesa de Importação.            OPERACIONAL                        NaN
PCDESPESAIMP TIPODESPESA  NUMBER(3,0)                                 Tipo da Despesa de Importação.            OPERACIONAL                        NaN
PCDESPESAIMP  TIPORATEIO  NUMBER(3,0) Forma de Proporcionalizaç ão do custo da Despesa de Importação            OPERACIONAL                        NaN
PCDESPESAIMP    CODCONTA NUMBER(10,0)            Código da Conta Gerencial da Despesa de Importação.            OPERACIONAL                        NaN
PCDESPESAIMP       VALOR NUMBER(12,6)                           Valor fixo da despesa de importação.            OPERACIONAL                        NaN
PCDESPESAIMP   PERCVALOR NUMBER(12,6)                Percentual fixo para definir o valor da despesa            OPERACIONAL                        NaN
PCDESPESAIMP      GERACP  VARCHAR2(1)                 Informa se a despesa deve gerar contas a pagar            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*