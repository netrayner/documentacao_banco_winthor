# 📊 Tabela: PCPRODCONVERSAO

### Estrutura de Colunas e Restrições

         Tabela        Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODCONVERSAO     CODFILIAL  VARCHAR2(2)                     Cód. Filial            OPERACIONAL                        NaN
PCPRODCONVERSAO   NUMTRANSENT NUMBER(10,0)            Transação de entrada            OPERACIONAL                        NaN
PCPRODCONVERSAO NUMTRANSVENDA NUMBER(10,0)              Transação de saída            OPERACIONAL                        NaN
PCPRODCONVERSAO       CODOPER  VARCHAR2(2)                Cód. De operação            OPERACIONAL                        NaN
PCPRODCONVERSAO       CODPROD  NUMBER(6,0)                 Cód. Do produto            OPERACIONAL                        NaN
PCPRODCONVERSAO            QT NUMBER(20,6)            Qt. A ser convertida            OPERACIONAL                        NaN
PCPRODCONVERSAO     MATRICULA  NUMBER(6,0)           Matrícula funcionário            OPERACIONAL                        NaN
PCPRODCONVERSAO    ROTINALANC VARCHAR2(40)            Rotina de lançamento            OPERACIONAL                        NaN
PCPRODCONVERSAO          DATA         DATE              Data do lançamento            OPERACIONAL                        NaN
PCPRODCONVERSAO       MAQUINA VARCHAR2(20) Maquina que originou lançamento            OPERACIONAL                        NaN
PCPRODCONVERSAO       USUARIO VARCHAR2(40)    Usuário que fez o lançamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*