# 📊 Tabela: PCOCORCHPROPRIO

### Estrutura de Colunas e Restrições

         Tabela         Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOCORCHPROPRIO  NUMOCORRENCIA  NUMBER(10,0)         Número da Ocorrência    CHAVE PRIMÁRIA (PK)                        NaN
PCOCORCHPROPRIO  CODOCORRENCIA   NUMBER(2,0)         Código da Ocorrência            OPERACIONAL                        NaN
PCOCORCHPROPRIO      DESCRICAO VARCHAR2(200)      Descrição da Ocorrência            OPERACIONAL                        NaN
PCOCORCHPROPRIO           DATA          DATE           Data da Ocorrência            OPERACIONAL                        NaN
PCOCORCHPROPRIO       NUMCAIXA   NUMBER(4,0)              Número do Caixa            OPERACIONAL                        NaN
PCOCORCHPROPRIO      CODFUNCCX   NUMBER(8,0)  Código do Operador de Caixa            OPERACIONAL                        NaN
PCOCORCHPROPRIO  NUMTRANSVENDA  NUMBER(10,0) Número da Transação de Venda            OPERACIONAL                        NaN
PCOCORCHPROPRIO CODFUNCAUTORIZ   NUMBER(8,0) Código do Fiscal Autorizador            OPERACIONAL                        NaN
PCOCORCHPROPRIO      DTAUTORIZ          DATE          Data da Autorização            OPERACIONAL                        NaN
PCOCORCHPROPRIO      NUMCHEQUE  NUMBER(10,0)             Número do Cheque            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*