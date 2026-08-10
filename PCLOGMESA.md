# 📊 Tabela: PCLOGMESA

### Estrutura de Colunas e Restrições

   Tabela           Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGMESA            DTLOG          DATE                                     DATA do Log            OPERACIONAL                        NaN
PCLOGMESA             ACAO VARCHAR2(500)                                     ACAO do Log            OPERACIONAL                        NaN
PCLOGMESA        MATRICULA   NUMBER(8,0)                    MATRICULA para salvar no Log            OPERACIONAL                        NaN
PCLOGMESA         NUMFICHA  NUMBER(10,0)                     NUMFICHA para salvar no Log            OPERACIONAL                        NaN
PCLOGMESA          NUMORCA  NUMBER(10,0)                      NUMORCA para salvar no Log            OPERACIONAL                        NaN
PCLOGMESA          CODPROD   NUMBER(6,0)                      CODPROD para salvar no Log            OPERACIONAL                        NaN
PCLOGMESA           CODCLI   NUMBER(6,0)                       CODCLI para salvar no Log            OPERACIONAL                        NaN
PCLOGMESA         PROGRAMA  VARCHAR2(30)                     PROGRAMA para salvar no Log            OPERACIONAL                        NaN
PCLOGMESA               QT  NUMBER(18,6)                  Quantidade da venda do produto            OPERACIONAL                        NaN
PCLOGMESA           PVENDA  NUMBER(18,6)                       Preço de venda do produto            OPERACIONAL                        NaN
PCLOGMESA        CODGARCON  NUMBER(10,0) Código do garçom que está fazendo o atendimento            OPERACIONAL                        NaN
PCLOGMESA CODSUPERVISORLIB  NUMBER(10,0)     Código do supervisor que liberou a operação            OPERACIONAL                        NaN
PCLOGMESA DTENVIOSERVCARGA          DATE          Data de envio para o servidor de carga            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*