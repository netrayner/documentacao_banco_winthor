# 📊 Tabela: PCSITUACAOCHEQUES

### Estrutura de Colunas e Restrições

           Tabela                Coluna   Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSITUACAOCHEQUES              NUMBANCO    NUMBER(4,0)                  Número do banco    CHAVE PRIMÁRIA (PK)                        NaN
PCSITUACAOCHEQUES            NUMAGENCIA    NUMBER(4,0)                Número da agência    CHAVE PRIMÁRIA (PK)                        NaN
PCSITUACAOCHEQUES             NUMCHEQUE    NUMBER(8,0)                 Número do cheque    CHAVE PRIMÁRIA (PK)                        NaN
PCSITUACAOCHEQUES              NUMCONTA   NUMBER(10,0)                  Número da conta    CHAVE PRIMÁRIA (PK)                        NaN
PCSITUACAOCHEQUES              DVCHEQUE    NUMBER(1,0)                     DV do Cheque            OPERACIONAL                        NaN
PCSITUACAOCHEQUES                 VALOR   NUMBER(10,2)                  Valor do cheque            OPERACIONAL                        NaN
PCSITUACAOCHEQUES               CPFCNPJ   VARCHAR2(18)             CPF / CNPJ do cheque    CHAVE PRIMÁRIA (PK)                        NaN
PCSITUACAOCHEQUES                    UF    VARCHAR2(2)                     UF do cheque            OPERACIONAL                        NaN
PCSITUACAOCHEQUES              SITUACAO    VARCHAR2(2)               Situação do cheque            OPERACIONAL                        NaN
PCSITUACAOCHEQUES         FUNCLIBERACAO    NUMBER(8,0) Funcionário que liberou o cheque            OPERACIONAL                        NaN
PCSITUACAOCHEQUES             NUMPEDIDO   NUMBER(10,0)                 Número do pedido            OPERACIONAL                        NaN
PCSITUACAOCHEQUES ID_PCSERASA_CONSULTAS   NUMBER(10,0)  ID da tabela PCSERASA_CONSULTAS            OPERACIONAL                        NaN
PCSITUACAOCHEQUES                CODCLI    NUMBER(6,0)                Código do cliente            OPERACIONAL                        NaN
PCSITUACAOCHEQUES                DTVENC           DATE               Data de vencimento            OPERACIONAL                        NaN
PCSITUACAOCHEQUES       CHEQUEUTILIZADO    VARCHAR2(1)                 Cheque utilizado            OPERACIONAL                        NaN
PCSITUACAOCHEQUES            OBSERVACAO VARCHAR2(1000)            Observação do cheque.            OPERACIONAL                        NaN
PCSITUACAOCHEQUES               NUMORCA   NUMBER(10,0)              NÚMERO DO ORÇAMENTO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*