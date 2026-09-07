# 📊 Tabela: PCPEDIDOMOTDESB

### Estrutura de Colunas e Restrições

         Tabela    Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIDOMOTDESB    NUMPED  NUMBER(10,0)                             Número do pedido            OPERACIONAL                        NaN
PCPEDIDOMOTDESB      ACAO   VARCHAR2(1)                Ação que esta sendo realizada            OPERACIONAL                        NaN
PCPEDIDOMOTDESB MATRICULA   NUMBER(8,0) Matricula do usuário que esta fazendo a ação            OPERACIONAL                        NaN
PCPEDIDOMOTDESB    DTACAO          DATE                          Data e hora da ação            OPERACIONAL                        NaN
PCPEDIDOMOTDESB ROTINACAD  VARCHAR2(13)                        Rotina que fez a ação            OPERACIONAL                        NaN
PCPEDIDOMOTDESB    MOTIVO VARCHAR2(200)                           Motivo do bloqueio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*