# 📊 Tabela: PCMETAC

### Estrutura de Colunas e Restrições

 Tabela             Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETAC             CODIGO   NUMBER(8,0)                 Indica o código da meta mensal.    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAC           DTINICIO          DATE         Indica a data de início da meta mensal.            OPERACIONAL                        NaN
PCMETAC              DTFIM          DATE             Indica a data final da meta mensal.            OPERACIONAL                        NaN
PCMETAC          DESCRICAO  VARCHAR2(40)              Indica a descrição da meta mensal.            OPERACIONAL                        NaN
PCMETAC      NUMDIASSEMANA   NUMBER(1,0)              Indica o número de dias na semana.            OPERACIONAL                        NaN
PCMETAC        METODOLOGIA VARCHAR2(500)  Indica a metodologia de aplicação de campanha.            OPERACIONAL                        NaN
PCMETAC TIPOCALCEFETIVACAO   VARCHAR2(1) Indica o tipo de cálculo de efetivação da meta.            OPERACIONAL                        NaN
PCMETAC           TIPOMETA   VARCHAR2(2)      Diferencia cada registro pelo tipo de meta            OPERACIONAL                        NaN
PCMETAC         DTMXSALTER          DATE                                             NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*