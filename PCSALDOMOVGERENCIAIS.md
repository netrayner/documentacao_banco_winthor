# 📊 Tabela: PCSALDOMOVGERENCIAIS

### Estrutura de Colunas e Restrições

              Tabela    Coluna Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDOMOVGERENCIAIS        ID VARCHAR2(20)        Indica qual o tipo de movimentação esta inserida na linha.            OPERACIONAL                        NaN
PCSALDOMOVGERENCIAIS     DTMOV         DATE                          Indica a data da movimentação do estoque            OPERACIONAL                        NaN
PCSALDOMOVGERENCIAIS CODFILIAL  VARCHAR2(2)            Indica a filial informada na analise das movimentações            OPERACIONAL                        NaN
PCSALDOMOVGERENCIAIS   CODPROD  NUMBER(6,0) Indica o código do produto informado na analise das movimentações            OPERACIONAL                        NaN
PCSALDOMOVGERENCIAIS     SALDO NUMBER(20,6)                 Indica a quantidade movimentada na data analisada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*