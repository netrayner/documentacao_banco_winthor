# 📊 Tabela: PCRESPOSTA

### Estrutura de Colunas e Restrições

    Tabela          Coluna   Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRESPOSTA     CODPESQUISA    NUMBER(8,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRESPOSTA     CODPERGUNTA    NUMBER(8,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRESPOSTA          CODCLI    NUMBER(6,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRESPOSTA          RESPSN    VARCHAR2(2)                                  NaN            OPERACIONAL                        NaN
PCRESPOSTA           VALOR   NUMBER(16,2)                                  NaN            OPERACIONAL                        NaN
PCRESPOSTA       QUALIDADE   VARCHAR2(20)                                  NaN            OPERACIONAL                        NaN
PCRESPOSTA           TEXTO   VARCHAR2(80)                                  NaN            OPERACIONAL                        NaN
PCRESPOSTA            NOTA    NUMBER(4,2)                                  NaN            OPERACIONAL                        NaN
PCRESPOSTA            TEMP   VARCHAR2(80)                                  NaN            OPERACIONAL                        NaN
PCRESPOSTA             OBS VARCHAR2(1000)                                  NaN            OPERACIONAL                        NaN
PCRESPOSTA CODRESPPERGUNTA    NUMBER(6,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRESPOSTA            DATA           DATE                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRESPOSTA       CODAGENDA   NUMBER(10,0)                    Código da agenda.            OPERACIONAL                        NaN
PCRESPOSTA      COMENTARIO  VARCHAR2(200)     Indica o comentario da resposta.            OPERACIONAL                        NaN
PCRESPOSTA           NUMOS    NUMBER(6,0) Indica o número da ordem de serviço.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*