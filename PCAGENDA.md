# 📊 Tabela: PCAGENDA

### Estrutura de Colunas e Restrições

  Tabela       Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDA    CODAGENDA  NUMBER(10,0)                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDA       CODCLI   NUMBER(6,0)                                    NaN            OPERACIONAL                        NaN
PCAGENDA         DATA          DATE                                    NaN            OPERACIONAL                        NaN
PCAGENDA CODOPERADORA   NUMBER(8,0)                                    NaN            OPERACIONAL                        NaN
PCAGENDA          OBS VARCHAR2(500)                                    NaN            OPERACIONAL                        NaN
PCAGENDA       STATUS   VARCHAR2(2)                                    NaN            OPERACIONAL                        NaN
PCAGENDA      CONTATO  VARCHAR2(40)              Indica o nome do contato.            OPERACIONAL                        NaN
PCAGENDA     RESPOSTA VARCHAR2(500)                                    NaN            OPERACIONAL                        NaN
PCAGENDA    DIASEMANA   NUMBER(2,0)                                    NaN            OPERACIONAL                        NaN
PCAGENDA         HORA          DATE                                    NaN            OPERACIONAL                        NaN
PCAGENDA    CODFUNCAB   NUMBER(8,0)                                    NaN            OPERACIONAL                        NaN
PCAGENDA         DTAB          DATE                                    NaN            OPERACIONAL                        NaN
PCAGENDA DTFECHAMENTO          DATE Indica a data de fechamento da agenda.            OPERACIONAL                        NaN
PCAGENDA  CODPESQUISA   NUMBER(8,0)           Indica o código da pesquisa.            OPERACIONAL                        NaN
PCAGENDA         TIPO   VARCHAR2(2)                  Indica o tipo Agenda.            OPERACIONAL                        NaN
PCAGENDA    CODMOTIVO   NUMBER(8,0)                   Código Motivo Agenda            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*