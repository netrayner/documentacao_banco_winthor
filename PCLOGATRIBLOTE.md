# 📊 Tabela: PCLOGATRIBLOTE

### Estrutura de Colunas e Restrições

        Tabela    Coluna Tipo/Tamanho    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGATRIBLOTE CODFILIAL  VARCHAR2(2)       Código da Filial            OPERACIONAL                        NaN
PCLOGATRIBLOTE    NUMCAR  NUMBER(8,0) Número do carregamento            OPERACIONAL                        NaN
PCLOGATRIBLOTE    NUMPED NUMBER(10,0)       Número do Pedido            OPERACIONAL                        NaN
PCLOGATRIBLOTE   CODPROD  NUMBER(6,0)      Código do Produto            OPERACIONAL                        NaN
PCLOGATRIBLOTE        QT NUMBER(20,6)             Quantidade            OPERACIONAL                        NaN
PCLOGATRIBLOTE   NUMLOTE VARCHAR2(15)         Número do lote            OPERACIONAL                        NaN
PCLOGATRIBLOTE   MAQUINA VARCHAR2(80)                Máquina            OPERACIONAL                        NaN
PCLOGATRIBLOTE   USUARIO VARCHAR2(80)                Usuário            OPERACIONAL                        NaN
PCLOGATRIBLOTE      DATA         DATE                   Data            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*