# 📊 Tabela: PCOBSOP

### Estrutura de Colunas e Restrições

 Tabela      Coluna  Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOBSOP       NUMOP   NUMBER(8,0)                                                             Número da OP.            OPERACIONAL                        NaN
PCOBSOP         OBS  VARCHAR2(40)                                                        Observações da OP.            OPERACIONAL                        NaN
PCOBSOP  ROTINALANC  VARCHAR2(48)                                       Rotina responsável pelo lançamento.            OPERACIONAL                        NaN
PCOBSOP CODFUNCLANC   NUMBER(8,0)                      Código do funcionário responsável lançamento da OBS.            OPERACIONAL                        NaN
PCOBSOP    DATALANC          DATE                                         Data e Hora do Lançamento da OBS.            OPERACIONAL                        NaN
PCOBSOP    OPERACAO VARCHAR2(100) Gravar o tipo de operação do cancelamento, se foi da OP ou do Apontamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*