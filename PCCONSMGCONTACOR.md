# 📊 Tabela: PCCONSMGCONTACOR

### Estrutura de Colunas e Restrições

          Tabela          Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONSMGCONTACOR              ID   NUMBER(6,0)                   Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSMGCONTACOR        IDORIGEM  VARCHAR2(20)         Chave da tabela de origem            OPERACIONAL                        NaN
PCCONSMGCONTACOR       CODFORNEC   NUMBER(6,0)              Código do fornecedor            OPERACIONAL                        NaN
PCCONSMGCONTACOR       CODFILIAL   VARCHAR2(2)                  Código da filial            OPERACIONAL                        NaN
PCCONSMGCONTACOR        CODCONTA  NUMBER(10,0)                   Código da conta            OPERACIONAL                        NaN
PCCONSMGCONTACOR          DTLANC          DATE                Data de lançamento            OPERACIONAL                        NaN
PCCONSMGCONTACOR       HISTORICO VARCHAR2(200)                         Histórico            OPERACIONAL                        NaN
PCCONSMGCONTACOR             ANO   VARCHAR2(4)                 Ano de lançamento            OPERACIONAL                        NaN
PCCONSMGCONTACOR             MES   VARCHAR2(2)                 Mês de lançamento            OPERACIONAL                        NaN
PCCONSMGCONTACOR    TOTALDEBCRED  NUMBER(18,6)       Total de débitos e créditos            OPERACIONAL                        NaN
PCCONSMGCONTACOR  VALORANOANTDEB  NUMBER(18,6)  Valor de débitos do ano anterior            OPERACIONAL                        NaN
PCCONSMGCONTACOR VALORANOANTCRED  NUMBER(18,6) Valor de créditos do ano anterior            OPERACIONAL                        NaN
PCCONSMGCONTACOR     VALORPCLANC  NUMBER(18,6)        Valor total de lançamentos            OPERACIONAL                        NaN
PCCONSMGCONTACOR VALORPCMOVCRFOR  NUMBER(18,6)             Valor total de verbas            OPERACIONAL                        NaN
PCCONSMGCONTACOR     SALDOANOANT  NUMBER(18,6)                Saldo ano anterior            OPERACIONAL                        NaN
PCCONSMGCONTACOR    DATAAPURACAO          DATE                  Data de apuração            OPERACIONAL                        NaN
PCCONSMGCONTACOR      CODUSUARIO   NUMBER(6,0)                 Código do usuário            OPERACIONAL                        NaN
PCCONSMGCONTACOR         USUARIO VARCHAR2(100)                   Nome do usuário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*