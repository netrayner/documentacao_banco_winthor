# 📊 Tabela: PCSALDOMOVCONTABEIS

### Estrutura de Colunas e Restrições

             Tabela    Coluna Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDOMOVCONTABEIS        ID VARCHAR2(20)        Indica qual o tipo de movimentação esta inserida na linha.            OPERACIONAL                        NaN
PCSALDOMOVCONTABEIS     DTMOV         DATE                          Indica a data da movimentação do estoque            OPERACIONAL                        NaN
PCSALDOMOVCONTABEIS CODFILIAL  VARCHAR2(2)            Indica a filial informada na analise das movimentações            OPERACIONAL                        NaN
PCSALDOMOVCONTABEIS   CODPROD  NUMBER(6,0) Indica o código do produto informado na analise das movimentações            OPERACIONAL                        NaN
PCSALDOMOVCONTABEIS     SALDO NUMBER(20,6)                 Indica a quantidade movimentada na data analisada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*