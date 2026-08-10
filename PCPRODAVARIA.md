# 📊 Tabela: PCPRODAVARIA

### Estrutura de Colunas e Restrições

      Tabela          Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODAVARIA       CODFILIAL   VARCHAR2(2)                  Cód. da filial            OPERACIONAL                        NaN
PCPRODAVARIA         CODPROD   NUMBER(6,0)                       Cód. Prod            OPERACIONAL                        NaN
PCPRODAVARIA       CODFORNEC   NUMBER(6,0)                 Cód. Fornecedor            OPERACIONAL                        NaN
PCPRODAVARIA            DATA          DATE                  Data da avaria            OPERACIONAL                        NaN
PCPRODAVARIA CODMOTIVOAVARIA   NUMBER(4,0)              Cód. Motivo avaria            OPERACIONAL                        NaN
PCPRODAVARIA              QT  NUMBER(20,6)                    Qt. Avariada            OPERACIONAL                        NaN
PCPRODAVARIA         NUMLOTE  VARCHAR2(40)                  Numero de lote            OPERACIONAL                        NaN
PCPRODAVARIA             OBS VARCHAR2(200)                      Observação            OPERACIONAL                        NaN
PCPRODAVARIA   NUMTRANSVENDA  NUMBER(10,0)              Transação de saída            OPERACIONAL                        NaN
PCPRODAVARIA        CODGRUPO   NUMBER(6,0)            Cód. Grupo de avaria            OPERACIONAL                        NaN
PCPRODAVARIA        NUMVERBA   NUMBER(6,0)                 Número da verba            OPERACIONAL                        NaN
PCPRODAVARIA     CODFUNCLANC   NUMBER(8,0)                 Cód. Funcinario            OPERACIONAL                        NaN
PCPRODAVARIA      ROTINALANC  VARCHAR2(40)            Rotina de lançamento            OPERACIONAL                        NaN
PCPRODAVARIA         ESTACAO  VARCHAR2(30)   Estação que efetivou a avaria            OPERACIONAL                        NaN
PCPRODAVARIA      QTORIGINAL  NUMBER(20,6) Quantidade original de entrada.            OPERACIONAL                        NaN
PCPRODAVARIA       CODAVARIA   NUMBER(8,0)     Código da entrada de avaria            OPERACIONAL                        NaN
PCPRODAVARIA     CODDEPOSITO  NUMBER(10,0)              Código do Depósito            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*