# 📊 Tabela: PCLOGDADOSJSON

### Estrutura de Colunas e Restrições

        Tabela       Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDADOSJSON DATAINCLUSAO         DATE        Data hora de inclusão do registro            OPERACIONAL                        NaN
PCLOGDADOSJSON   NOMETABELA VARCHAR2(32)   Nome da tabela pertencente ao registro            OPERACIONAL                        NaN
PCLOGDADOSJSON    TRANSACAO NUMBER(12,0) Código identificar do registro na tabela            OPERACIONAL                        NaN
PCLOGDADOSJSON     OPERACAO  VARCHAR2(1)  Define o tipo de operação do log gerado            OPERACIONAL                        NaN
PCLOGDADOSJSON       ROTINA VARCHAR2(64)       Nome do aplicativo que gerou o log            OPERACIONAL                        NaN
PCLOGDADOSJSON      MAQUINA VARCHAR2(64)              Nome da estação de trabalho            OPERACIONAL                        NaN
PCLOGDADOSJSON       OSUSER VARCHAR2(30)        Nome do usuário logado na estação            OPERACIONAL                        NaN
PCLOGDADOSJSON     REGISTRO         CLOB            Conteúdo do registro alterado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*