# 📊 Tabela: PCLANCADIANTFORNEC

### Estrutura de Colunas e Restrições

            Tabela             Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLANCADIANTFORNEC RECNUMADIANTAMENTO  NUMBER(8,0) ID da tabela PCLANC do lançamento de adiantamento            OPERACIONAL                        NaN
PCLANCADIANTFORNEC  NUMTRANSADIANTFOR  NUMBER(8,0)                     Número sequencial do NUMTRANS            OPERACIONAL                        NaN
PCLANCADIANTFORNEC        RECNUMPAGTO  NUMBER(8,0)       ID da tabela PCLANC do lançamento do título            OPERACIONAL                        NaN
PCLANCADIANTFORNEC              VALOR NUMBER(12,2)                     Valor utilizado no abatimento            OPERACIONAL                        NaN
PCLANCADIANTFORNEC             DTLANC         DATE                  Data do lançamento do abatimento            OPERACIONAL                        NaN
PCLANCADIANTFORNEC          DTESTORNO         DATE                     Data do estorno do lançamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*