# 📊 Tabela: PCESTENDERECOI

### Estrutura de Colunas e Restrições

        Tabela       Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTENDERECOI    CODROTINA  NUMBER(6,0)                  Código da rotina            OPERACIONAL                        NaN
PCESTENDERECOI       CODUMA NUMBER(16,0)                     Código U.M.A.            OPERACIONAL                        NaN
PCESTENDERECOI    DTENTRADA         DATE                   Data de entrada            OPERACIONAL                        NaN
PCESTENDERECOI      CODPROD NUMBER(16,0)                 Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCESTENDERECOI  CODENDERECO NUMBER(16,0)                Código do endereço    CHAVE PRIMÁRIA (PK)                        NaN
PCESTENDERECOI      NUMLOTE VARCHAR2(20)                    Número do lote    CHAVE PRIMÁRIA (PK)                        NaN
PCESTENDERECOI        DTVAL         DATE                  Data de validade    CHAVE PRIMÁRIA (PK)                        NaN
PCESTENDERECOI           QT NUMBER(20,8)                        Quantidade            OPERACIONAL                        NaN
PCESTENDERECOI CODROTINAALT  NUMBER(6,0)     Código da rotina de alteração            OPERACIONAL                        NaN
PCESTENDERECOI        DTALT         DATE                 Data de alteração            OPERACIONAL                        NaN
PCESTENDERECOI   CODFUNCALT  NUMBER(8,0) Código do funcionário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*