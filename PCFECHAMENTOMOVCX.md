# 📊 Tabela: PCFECHAMENTOMOVCX

### Estrutura de Colunas e Restrições

           Tabela             Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFECHAMENTOMOVCX          CODFILIAL  VARCHAR2(2)                  Codigo da Filial            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX           NUMCAIXA  NUMBER(4,0)                   Numero do Caixa            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX          CODFUNCCX  NUMBER(8,0)       Codigo do Operador de Caixa            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX      DTMOVIMENTOCX         DATE                 Data do movimento            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX         DTABERTURA         DATE     Data de abertura do movimento            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX       HORAABERTURA  NUMBER(2,0)     Hora de abertura do movimento            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX     MINUTOABERTURA  NUMBER(2,0)   Minuto de abertura do movimento            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX       DTFECHAMENTO         DATE   Data de fechamento do movimento            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX     HORAFECHAMENTO  NUMBER(2,0)   Hora do fechamento do movimento            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX   MINUTOFECHAMENTO  NUMBER(2,0) Minuto do fechamento do movimento            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX NUMFECHAMENTOMOVCX NUMBER(10,0)  Num. Do fechamento por movimento            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX    NUMMOVIMENTOPDV NUMBER(10,0)        NUMERO DE MOVIMENTO DO DPV            OPERACIONAL                        NaN
PCFECHAMENTOMOVCX          EXPORTADO  VARCHAR2(1)                               NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*