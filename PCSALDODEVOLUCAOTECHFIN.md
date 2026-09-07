# 📊 Tabela: PCSALDODEVOLUCAOTECHFIN

### Estrutura de Colunas e Restrições

                 Tabela         Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDODEVOLUCAOTECHFIN      CODFILIAL  VARCHAR2(2)                          Codigo da Filial            OPERACIONAL                        NaN
PCSALDODEVOLUCAOTECHFIN  NUMTRANSVENDA NUMBER(10,0)              Numero da Transação de Saída            OPERACIONAL                        NaN
PCSALDODEVOLUCAOTECHFIN          PREST  VARCHAR2(2)                       Número da prestação            OPERACIONAL                        NaN
PCSALDODEVOLUCAOTECHFIN VALORDEVOLUCAO NUMBER(12,2)                        Valor da Devolução            OPERACIONAL                        NaN
PCSALDODEVOLUCAOTECHFIN    DTDEVOLUCAO TIMESTAMP(6) Data e Hora do processamento da Devolução            OPERACIONAL                        NaN
PCSALDODEVOLUCAOTECHFIN    NUMTRANSENT NUMBER(10,0)            Número da Transação de Entrada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*