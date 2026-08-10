# 📊 Tabela: PCVISITA

### Estrutura de Colunas e Restrições

  Tabela        Coluna   Tipo/Tamanho                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVISITA     CODVISITA   NUMBER(10,0)                                                                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVISITA        CODCLI    NUMBER(6,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA          DATA           DATE                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA     CODMOTIVO    NUMBER(6,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA  CODOPERADORA    NUMBER(8,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA       ASSUNTO VARCHAR2(4000)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA       CONTATO   VARCHAR2(40)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA  TIPOOPERACAO    VARCHAR2(1)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA     HRINICIAL    NUMBER(2,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA       HRFINAL    NUMBER(2,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA       CODUSUR    NUMBER(4,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA     DIASEMANA   VARCHAR2(10)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA      VISITADO    VARCHAR2(1)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA MINUTOINICIAL    NUMBER(2,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA   MINUTOFINAL    NUMBER(2,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCVISITA          TIPO    VARCHAR2(1)                                                                    Informar módulo que originou a visita.            OPERACIONAL                        NaN
PCVISITA     SEQVISITA    NUMBER(6,0)                                                                     Sequência para visitação de clientes.            OPERACIONAL                        NaN
PCVISITA  CODMOTAGENDA    NUMBER(8,0) Armazena o Motivo de Agendamento informado na Rotina 1912 quando o atendimento, proveniente de uma agenda            OPERACIONAL                        NaN
PCVISITA     CANCELADO    VARCHAR2(1)                                                                                    Informa está cancelado            OPERACIONAL                        NaN
PCVISITA    OBSERVACAO  VARCHAR2(100)                                                                                Observação de cancelamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*