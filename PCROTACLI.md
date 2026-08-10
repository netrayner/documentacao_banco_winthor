# 📊 Tabela: PCROTACLI

### Estrutura de Colunas e Restrições

   Tabela           Coluna Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTACLI          CODUSUR  NUMBER(4,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI        DIASEMANA VARCHAR2(10)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI           CODCLI  NUMBER(6,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI        SEQUENCIA  NUMBER(4,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI    PERIODICIDADE VARCHAR2(10)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI     DTPROXVISITA         DATE                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI        NUMSEMANA  NUMBER(4,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI      VLMETAVENDA NUMBER(14,2)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI              OBS VARCHAR2(60)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI      CICLOVISITA  NUMBER(4,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI       HORAVISITA  NUMBER(2,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI     MINUTOVISITA  NUMBER(2,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI  DTULTVISITAPREV         DATE                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI             SEQ1  NUMBER(4,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI             SEQ2  NUMBER(4,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI             SEQ3  NUMBER(4,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI          DATAREF         DATE                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI          NUMZONA  NUMBER(4,0)                            Indica o número da zona da rota do cliente.            OPERACIONAL                        NaN
PCROTACLI          DTFINAL         DATE                                 Indica a data final da rota de visita.            OPERACIONAL                        NaN
PCROTACLI         DTINICIO         DATE                             Indica a data de início da rota de visita.            OPERACIONAL                        NaN
PCROTACLI    CODUSURORIGEM  NUMBER(4,0)                Código do RCA possuidor das rotas antes a transferência            OPERACIONAL                        NaN
PCROTACLI   CODCOMPROMISSO  NUMBER(9,0)                                                                    NaN            OPERACIONAL                        NaN
PCROTACLI          DIAFIXO  VARCHAR2(1)                                                            Indica se é            OPERACIONAL                        NaN
PCROTACLI  DTTRANSFRETORNO         DATE                               Data para retorno automático de clientes            OPERACIONAL                        NaN
PCROTACLI      CODUSURORIG  NUMBER(4,0) Codigo do usuário original da transferência para o retorno automático.            OPERACIONAL                        NaN
PCROTACLI DTPROXVISITAORIG         DATE                                Data para Cancelamento de remanejamento            OPERACIONAL                        NaN
PCROTACLI    SEQUENCIALOLD  NUMBER(4,0)     Valor do campo SEQUENCIAL antes de realizar a transferência de RCA            OPERACIONAL                        NaN
PCROTACLI       DTMXSALTER         DATE                                                                    NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*