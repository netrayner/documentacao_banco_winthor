# 📊 Tabela: PCMOVROLOPREFAT

### Estrutura de Colunas e Restrições

         Tabela                 Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVROLOPREFAT                 CODCOR NUMBER(10,0)                           Código Cor            OPERACIONAL                        NaN
PCMOVROLOPREFAT              CODFILIAL  VARCHAR2(2)                        Código Filial            OPERACIONAL                        NaN
PCMOVROLOPREFAT                CODFUNC  NUMBER(6,0)                   Código Funcionário            OPERACIONAL                        NaN
PCMOVROLOPREFAT                CODOPER  VARCHAR2(2)                      Código Operação            OPERACIONAL                        NaN
PCMOVROLOPREFAT                CODPROD  NUMBER(6,0)                       Código Produto            OPERACIONAL                        NaN
PCMOVROLOPREFAT              DTMOVROLO         DATE                    Data Movimentação            OPERACIONAL                        NaN
PCMOVROLOPREFAT                 DTVENC         DATE Indica a data de vencimento do lote.            OPERACIONAL                        NaN
PCMOVROLOPREFAT                NUMLOTE VARCHAR2(15)             Indica o número do lote.            OPERACIONAL                        NaN
PCMOVROLOPREFAT                 NUMPED NUMBER(10,0)                     Número do Pedido            OPERACIONAL                        NaN
PCMOVROLOPREFAT                NUMROLO VARCHAR2(10)                       Número do Rolo            OPERACIONAL                        NaN
PCMOVROLOPREFAT                 NUMSEQ NUMBER(20,0)                    Número Sequencial            OPERACIONAL                        NaN
PCMOVROLOPREFAT            NUMTRANSENT NUMBER(10,0)          Número Transação de Entrada            OPERACIONAL                        NaN
PCMOVROLOPREFAT          NUMTRANSVENDA NUMBER(10,0)            Número Transação de Saída            OPERACIONAL                        NaN
PCMOVROLOPREFAT                     QT NUMBER(10,4)                           Quantidade            OPERACIONAL                        NaN
PCMOVROLOPREFAT DATACONSOLIDACAOPREFAT         DATE    Data Consolidação Pré Faturamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*