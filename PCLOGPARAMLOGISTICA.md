# 📊 Tabela: PCLOGPARAMLOGISTICA

### Estrutura de Colunas e Restrições

             Tabela        Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPARAMLOGISTICA        ROTINA  VARCHAR2(30) Rotina a que se refere o parâmetro.            OPERACIONAL                        NaN
PCLOGPARAMLOGISTICA          DATA          DATE    Data de utilização do parâmetro.            OPERACIONAL                        NaN
PCLOGPARAMLOGISTICA NUMTRANSVENDA  NUMBER(10,0)                  Transação de saída            OPERACIONAL                        NaN
PCLOGPARAMLOGISTICA   NUMTRANSENT  NUMBER(10,0)                Transação de entrada            OPERACIONAL                        NaN
PCLOGPARAMLOGISTICA     PARAMETRO VARCHAR2(100)                   Nome do parâmetro            OPERACIONAL                        NaN
PCLOGPARAMLOGISTICA         VALOR VARCHAR2(100)                  Valor do parâmetro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*