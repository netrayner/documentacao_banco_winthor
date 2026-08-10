# 📊 Tabela: PCMOVROTACLI

### Estrutura de Colunas e Restrições

      Tabela          Coluna Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVROTACLI         CODROTA NUMBER(13,0)      Código do RCA possuidor das rotas antes a transferência            OPERACIONAL                        NaN
PCMOVROTACLI         CODUSUR  NUMBER(4,0)                                                Código do rca            OPERACIONAL                        NaN
PCMOVROTACLI       DIASEMANA VARCHAR2(10)                                                Dia da semana            OPERACIONAL                        NaN
PCMOVROTACLI          CODCLI  NUMBER(6,0)                                            Código do cliente            OPERACIONAL                        NaN
PCMOVROTACLI       SEQUENCIA  NUMBER(4,0)                                          Sequência da visita            OPERACIONAL                        NaN
PCMOVROTACLI   PERIODICIDADE VARCHAR2(10)                                      Periodicidade da visita            OPERACIONAL                        NaN
PCMOVROTACLI       NUMSEMANA  NUMBER(4,0)                            Número referente ao dia da semana            OPERACIONAL                        NaN
PCMOVROTACLI     VLMETAVENDA NUMBER(14,2)                                       Valor da meta de venda            OPERACIONAL                        NaN
PCMOVROTACLI             OBS VARCHAR2(60)                                       Observação do vendedor            OPERACIONAL                        NaN
PCMOVROTACLI     CICLOVISITA  NUMBER(4,0)                                              Ciclo de visita            OPERACIONAL                        NaN
PCMOVROTACLI      HORAVISITA  NUMBER(2,0)                                               Hora da visita            OPERACIONAL                        NaN
PCMOVROTACLI    MINUTOVISITA  NUMBER(2,0)                                             Minuto da visita            OPERACIONAL                        NaN
PCMOVROTACLI            SEQ1  NUMBER(4,0)                                 Sequencia semana e quinzenal            OPERACIONAL                        NaN
PCMOVROTACLI            SEQ2  NUMBER(4,0)                                 Sequencia semana e quinzenal            OPERACIONAL                        NaN
PCMOVROTACLI            SEQ3  NUMBER(4,0)                                       Código do dia da semna            OPERACIONAL                        NaN
PCMOVROTACLI         DATAREF         DATE                                           Data de referência            OPERACIONAL                        NaN
PCMOVROTACLI         NUMZONA  NUMBER(4,0)                                               Número da zona            OPERACIONAL                        NaN
PCMOVROTACLI         DTFINAL         DATE                                                  Data incial            OPERACIONAL                        NaN
PCMOVROTACLI        DTINICIO         DATE                                                   Data final            OPERACIONAL                        NaN
PCMOVROTACLI    DTVISITAPROG         DATE                       Data original programada para a visita            OPERACIONAL                        NaN
PCMOVROTACLI    DTPROXVISITA         DATE                       Data para qual foi reagendada a visita            OPERACIONAL                        NaN
PCMOVROTACLI      DTJUSTIFIC         DATE                  Data da justificativa de não visita / venda            OPERACIONAL                        NaN
PCMOVROTACLI        DTPEDIDO         DATE                             Data do último pedido do cliente            OPERACIONAL                        NaN
PCMOVROTACLI        DTCANCEL         DATE                   Data de cancelamento do registro de rotas.            OPERACIONAL                        NaN
PCMOVROTACLI DTULTVISITAPREV         DATE      Recebe o valor do campo DTPROXVISITA antes da alteração            OPERACIONAL                        NaN
PCMOVROTACLI      TIPOVISITA  VARCHAR2(1)                                 Recebe uma lista de valores:            OPERACIONAL                        NaN
PCMOVROTACLI       CODVISITA NUMBER(10,0)   Recebe o mesmo valor do campo CODVISITA da tabela PCVISITA            OPERACIONAL                        NaN
PCMOVROTACLI        QTPEDIDO  NUMBER(2,0) Registra a quantidade de vendas realizadas em uma mesma data            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*