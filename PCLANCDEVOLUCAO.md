# 📊 Tabela: PCLANCDEVOLUCAO

### Estrutura de Colunas e Restrições

         Tabela        Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLANCDEVOLUCAO        RECNUM  NUMBER(8,0)               Número do título            OPERACIONAL                        NaN
PCLANCDEVOLUCAO   NUMTRANSENT NUMBER(10,0) Número da transação de entrada            OPERACIONAL                        NaN
PCLANCDEVOLUCAO NUMTRANSVENDA NUMBER(10,0)   Número da transação de saída            OPERACIONAL                        NaN
PCLANCDEVOLUCAO         VALOR NUMBER(18,6)             Valor da devolução            OPERACIONAL                        NaN
PCLANCDEVOLUCAO    DTCADASTRO         DATE               Data do cadastro            OPERACIONAL                        NaN
PCLANCDEVOLUCAO     DTESTORNO         DATE                Data do estorno            OPERACIONAL                        NaN
PCLANCDEVOLUCAO     ROTINACAD  NUMBER(6,0)      Rotina que fez o cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*