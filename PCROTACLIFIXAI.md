# 📊 Tabela: PCROTACLIFIXAI

### Estrutura de Colunas e Restrições

        Tabela         Coluna  Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTACLIFIXAI    CODROTAFIXA   NUMBER(8,0)          Código da rota faixa cliente            OPERACIONAL                        NaN
PCROTACLIFIXAI         CODCLI   NUMBER(8,0)                     Código do cliente            OPERACIONAL                        NaN
PCROTACLIFIXAI      SEQUENCIA   NUMBER(8,0)         Seqüência da faixa cadastrada            OPERACIONAL                        NaN
PCROTACLIFIXAI      DIASEMANA   VARCHAR2(1)                         Dia da semana            OPERACIONAL                        NaN
PCROTACLIFIXAI           HORA   VARCHAR2(2)                                  Hora            OPERACIONAL                        NaN
PCROTACLIFIXAI            MIN   VARCHAR2(2)                                Minuto            OPERACIONAL                        NaN
PCROTACLIFIXAI            MES   VARCHAR2(2)                            Mês do ano            OPERACIONAL                        NaN
PCROTACLIFIXAI         SEMANA   VARCHAR2(1)                         Semana do mês            OPERACIONAL                        NaN
PCROTACLIFIXAI      METAVENDA  NUMBER(12,2)                         Meta de venda            OPERACIONAL                        NaN
PCROTACLIFIXAI            OBS VARCHAR2(150) Observação do item da rota cadastrada            OPERACIONAL                        NaN
PCROTACLIFIXAI CODCOMPROMISSO   NUMBER(9,0)                                   NaN            OPERACIONAL                        NaN
PCROTACLIFIXAI     DTMXSALTER          DATE                                   NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*