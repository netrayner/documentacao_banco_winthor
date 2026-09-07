# 📊 Tabela: PCSALDORCAFORNEC

### Estrutura de Colunas e Restrições

          Tabela           Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDORCAFORNEC           CODIGO   NUMBER(6,0)       Código saldo rca/fornecedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDORCAFORNEC          CODUSUR   NUMBER(4,0)                 Código do usuário.            OPERACIONAL                        NaN
PCSALDORCAFORNEC        CODFORNEC   NUMBER(6,0)              Código do fornecedor.            OPERACIONAL                        NaN
PCSALDORCAFORNEC            DTALT          DATE                 Data de alteração.            OPERACIONAL                        NaN
PCSALDORCAFORNEC        VLLIMCRED  NUMBER(10,2)        Valor do limite de crédito.            OPERACIONAL                        NaN
PCSALDORCAFORNEC DTINICIOVIGENCIA          DATE       Data de início da vingência.            OPERACIONAL                        NaN
PCSALDORCAFORNEC    DTFIMVIGENCIA          DATE           Data de fim da vigência.            OPERACIONAL                        NaN
PCSALDORCAFORNEC       CODFUNCCAD   NUMBER(8,0) Código do funcionário de cadastro.            OPERACIONAL                        NaN
PCSALDORCAFORNEC           MOTIVO VARCHAR2(100)                Motivo de cadastro.            OPERACIONAL                        NaN
PCSALDORCAFORNEC        DTCRIACAO          DATE                   Data da criação.            OPERACIONAL                        NaN
PCSALDORCAFORNEC  MOTIVOALTERACAO VARCHAR2(100)               Motivo da alteração.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*