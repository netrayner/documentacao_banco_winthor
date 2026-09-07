# 📊 Tabela: PCROTINA

### Estrutura de Colunas e Restrições

  Tabela                    Coluna   Tipo/Tamanho                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTINA                    CODIGO    NUMBER(6,0)                                                                NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCROTINA                NOMEROTINA   VARCHAR2(40)                                                                NaN            OPERACIONAL                        NaN
PCROTINA                      ACAO  VARCHAR2(250)                                                                NaN            OPERACIONAL                        NaN
PCROTINA                     AJUDA VARCHAR2(1000)                                                                NaN            OPERACIONAL                        NaN
PCROTINA                 CODMODULO    NUMBER(4,0)                                                                NaN            OPERACIONAL                        NaN
PCROTINA              CODSUBMODULO    NUMBER(4,0)                                                                NaN            OPERACIONAL                        NaN
PCROTINA                       LOG    VARCHAR2(1)                                                                NaN            OPERACIONAL                        NaN
PCROTINA                    NUMSEQ    NUMBER(4,0)                                                                NaN            OPERACIONAL                        NaN
PCROTINA                     NIVEL    NUMBER(2,0)                                                                NaN            OPERACIONAL                        NaN
PCROTINA                    STATUS    VARCHAR2(1)                                                                NaN            OPERACIONAL                        NaN
PCROTINA              NUMULTVERSAO    NUMBER(4,2)                                                                NaN            OPERACIONAL                        NaN
PCROTINA               DTULTVERSAO           DATE                                                                NaN            OPERACIONAL                        NaN
PCROTINA                EXIBIRMENU    VARCHAR2(1)                                                                NaN            OPERACIONAL                        NaN
PCROTINA              QTUTILIZACAO   NUMBER(10,0)                                                                NaN            OPERACIONAL                        NaN
PCROTINA           DTULTUTILIZACAO           DATE                                                                NaN            OPERACIONAL                        NaN
PCROTINA           DTPRIUTILIZACAO           DATE                                                                NaN            OPERACIONAL                        NaN
PCROTINA            CODFUNCULTUTIL    NUMBER(8,0)                                                                NaN            OPERACIONAL                        NaN
PCROTINA                   DATAEXE           DATE                                                                NaN            OPERACIONAL                        NaN
PCROTINA                   AUTMENU   NUMBER(10,0)                                                                NaN            OPERACIONAL                        NaN
PCROTINA            VERSAOCOMPLETA   VARCHAR2(20) Indica a versão da rotina.|Campo do tipo caracter, de tamanho 20.             OPERACIONAL                        NaN
PCROTINA UTILIZACONTROLEBIOMETRICO    VARCHAR2(1)                              Indica a utiliza controle biometrico.            OPERACIONAL                        NaN
PCROTINA                      FIID   VARCHAR2(50)                          Identificação da rotina no FLUIG Identity            OPERACIONAL                        NaN
PCROTINA              VERSAOEXEANT   VARCHAR2(20)                                         Versão anterior da rotina.            OPERACIONAL                        NaN
PCROTINA            VERSAOEXEATUAL   VARCHAR2(20)                                             Versão atual da rotina            OPERACIONAL                        NaN
PCROTINA               HASHCODEMD5   VARCHAR2(32)                      Hashcode MD5 gerado na atualização da rotina.            OPERACIONAL                        NaN
PCROTINA                 ROTINAWEB    VARCHAR2(1)         Define se a rotina será web ou será aberta no menu desktop            OPERACIONAL                        NaN
PCROTINA                    ROTINA   VARCHAR2(45)               Nome da rotina sem extensão que está sendo executado            OPERACIONAL                        NaN
PCROTINA         DATASINCRONIZACAO           DATE             Data e hora da sincronização com a central de controle            OPERACIONAL                        NaN
PCROTINA                DTMXSALTER           DATE                                                                NaN            OPERACIONAL                        NaN
PCROTINA                 DESCRICAO  VARCHAR2(150)                                                Descrição da rotina            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*