# 📊 Tabela: PCDOCARRECADACAO

### Estrutura de Colunas e Restrições

          Tabela           Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCARRECADACAO        CODMODELO   NUMBER(2,0)               Código do modelo.            OPERACIONAL                        NaN
PCDOCARRECADACAO               UF   VARCHAR2(2)                 Uf beneficiada.            OPERACIONAL                        NaN
PCDOCARRECADACAO           NUMDOC  VARCHAR2(20)            Número do documento.            OPERACIONAL                        NaN
PCDOCARRECADACAO   AUTENTBANCARIA VARCHAR2(100)        Autentificação bancária.            OPERACIONAL                        NaN
PCDOCARRECADACAO VLTOTARRECADACAO  NUMBER(16,2)     Valor total da arrecadação.            OPERACIONAL                        NaN
PCDOCARRECADACAO     DTVENCIMENTO          DATE             Data do vencimento.            OPERACIONAL                        NaN
PCDOCARRECADACAO      DTPAGAMENTO          DATE              Data do pagamento.            OPERACIONAL                        NaN
PCDOCARRECADACAO           CODDOC   NUMBER(6,0)            Código do documento.    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCARRECADACAO      NUMTRANSENT  NUMBER(10,0) Número da transação de entrada.            OPERACIONAL                        NaN
PCDOCARRECADACAO          CODCONT  NUMBER(10,0)                Código da conta.            OPERACIONAL                        NaN
PCDOCARRECADACAO      TIPOIMPGNRE   NUMBER(2,0)               Tipo Imposto GNRE            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*