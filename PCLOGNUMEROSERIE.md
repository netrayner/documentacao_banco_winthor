# 📊 Tabela: PCLOGNUMEROSERIE

### Estrutura de Colunas e Restrições

          Tabela       Coluna Tipo/Tamanho   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGNUMEROSERIE    CODFILIAL  VARCHAR2(2)      CODIGO DA FILIAL            OPERACIONAL                        NaN
PCLOGNUMEROSERIE      CODPROD  NUMBER(6,0)     CODIGO DO PRODUTO            OPERACIONAL                        NaN
PCLOGNUMEROSERIE         DATA         DATE      Data de cadastro            OPERACIONAL                        NaN
PCLOGNUMEROSERIE      NUMLOTE VARCHAR2(15)        NUMERO DO LOTE            OPERACIONAL                        NaN
PCLOGNUMEROSERIE     NUMSERIE VARCHAR2(60)       NUMERO DE SERIE            OPERACIONAL                        NaN
PCLOGNUMEROSERIE     BLOQUEIO  VARCHAR2(1)        BLOQUEIO ATUAL            OPERACIONAL                        NaN
PCLOGNUMEROSERIE  BLOQUEIOANT  VARCHAR2(1)     BLOQUEIO ANTERIOR            OPERACIONAL                        NaN
PCLOGNUMEROSERIE       AVARIA  VARCHAR2(1)          Avaria atual            OPERACIONAL                        NaN
PCLOGNUMEROSERIE    AVARIAANT  VARCHAR2(1)       Avaria anterior            OPERACIONAL                        NaN
PCLOGNUMEROSERIE    RESERVADA  VARCHAR2(1)         Reserva atual            OPERACIONAL                        NaN
PCLOGNUMEROSERIE RESERVADAANT  VARCHAR2(1)      Reserva anterior            OPERACIONAL                        NaN
PCLOGNUMEROSERIE    ROTINACAD VARCHAR2(80)    Rotina de cadastro            OPERACIONAL                        NaN
PCLOGNUMEROSERIE      USUARIO VARCHAR2(80) Usuário de cadastro\t            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*