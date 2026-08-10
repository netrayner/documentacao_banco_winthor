# 📊 Tabela: PCSALDTRANSITO

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDTRANSITO   CODFILIAL  VARCHAR2(2)              Codigo da filial            OPERACIONAL                        NaN
PCSALDTRANSITO QTDTRANSITO NUMBER(18,4) Saldo consolidado em transito            OPERACIONAL                        NaN
PCSALDTRANSITO     CODPROD NUMBER(10,0)             Codigo do produto            OPERACIONAL                        NaN
PCSALDTRANSITO  DTULTALTER         DATE      Data da ultima alteracao            OPERACIONAL                        NaN
PCSALDTRANSITO      CODCLI  NUMBER(9,0)             Codigo do cliente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*