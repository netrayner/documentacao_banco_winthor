# 📊 Tabela: PCLOGALTNUMEROSERIE

### Estrutura de Colunas e Restrições

             Tabela           Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGALTNUMEROSERIE        CODFILIAL  VARCHAR2(2)                            Código da Filial            OPERACIONAL                        NaN
PCLOGALTNUMEROSERIE          CODPROD  NUMBER(6,0)                           Código do produto            OPERACIONAL                        NaN
PCLOGALTNUMEROSERIE NUMSERIEANTERIOR VARCHAR2(60)                    Número de série anterior            OPERACIONAL                        NaN
PCLOGALTNUMEROSERIE    NUMSERIEATUAL VARCHAR2(60)                       Número de série atual            OPERACIONAL                        NaN
PCLOGALTNUMEROSERIE          DATAALT         DATE                    Data e hora de alteração            OPERACIONAL                        NaN
PCLOGALTNUMEROSERIE       CODFUNCALT  NUMBER(8,0)          Funcionário que alterou o registro            OPERACIONAL                        NaN
PCLOGALTNUMEROSERIE        ROTINAALT VARCHAR2(20)           Rotina responsável pela alteração            OPERACIONAL                        NaN
PCLOGALTNUMEROSERIE       ESTACAOALT VARCHAR2(40) Estação que efetuou a alteração do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*