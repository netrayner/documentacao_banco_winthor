# 📊 Tabela: PCFWLOGDEBUG

### Estrutura de Colunas e Restrições

      Tabela    Coluna   Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFWLOGDEBUG   SERVICO  VARCHAR2(100)                                       Nome do serviço            OPERACIONAL                        NaN
PCFWLOGDEBUG    VERSAO   VARCHAR2(10)                                     Versão do serviço            OPERACIONAL                        NaN
PCFWLOGDEBUG      DATA           DATE                                Data de geração do log            OPERACIONAL                        NaN
PCFWLOGDEBUG      TIPO   VARCHAR2(10)                         Tipo de mensagem (DEBUG/ERRO)            OPERACIONAL                        NaN
PCFWLOGDEBUG  MENSAGEM VARCHAR2(4000)                                      Descrição do log            OPERACIONAL                        NaN
PCFWLOGDEBUG TRANSACAO   NUMBER(10,0)                        Transação da NF uso do serviço            OPERACIONAL                        NaN
PCFWLOGDEBUG ROTINACAD   VARCHAR2(48)                       Código da rotina uso do serviço            OPERACIONAL                        NaN
PCFWLOGDEBUG       SQL           CLOB                        CONSULTA TRIBUTAÇÃO DA REFORMA            OPERACIONAL                        NaN
PCFWLOGDEBUG SEQUENCIA   NUMBER(10,0) SEQUENCIA DAS LINHAS DE REGISTRO DO LOG POR TRANSACAO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*