# 📊 Tabela: PCCONCESSAOCREDMAISNEG

### Estrutura de Colunas e Restrições

                Tabela              Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONCESSAOCREDMAISNEG      PROTOCOLNUMBER  VARCHAR2(50)                                 Número do Protocolo            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG     DATASOLICITACAO  TIMESTAMP(6)                                 Data da Solicitação            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG  LIMITECREDDESEJADO  NUMBER(12,2)                          Limite de Crédito Desejado            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG              CODCLI   NUMBER(9,0)                                   Código de Cliente            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG  LIMITECREDAPROVADO  NUMBER(12,2)                          Limite de Crédito Aprovado            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG   DATAHORAAVALIACAO  TIMESTAMP(6)                            Data e Hora da Avaliação            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG              STATUS   VARCHAR2(2)                      Status da concessão de crédito            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG                  ID  NUMBER(10,0)               Identificação da Concessão de Crédito    CHAVE PRIMÁRIA (PK)                        NaN
PCCONCESSAOCREDMAISNEG               ERPID  VARCHAR2(50)                            Identificação do Cliente            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG                 OBS VARCHAR2(100)                                          Observação            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG DATAHORACONFIRMACAO  TIMESTAMP(6)                          Data e Hora da Confirmação            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG          REQUISICAO          CLOB                                Requisição de Limite            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG             RETORNO          CLOB                              Retorno da Solicitação            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG   RETORNO_CONCESSAO          CLOB                                Retorno da Concessão            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG       STATUSPROCESS   VARCHAR2(1) Status do processamento de solicitação de concessão            OPERACIONAL                        NaN
PCCONCESSAOCREDMAISNEG          DTEXECUCAO  TIMESTAMP(6)                                    Data da execução            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*