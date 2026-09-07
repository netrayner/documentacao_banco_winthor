# 📊 Tabela: PCREGISTROREQUISICOESSERVICOS

### Estrutura de Colunas e Restrições

                       Tabela               Coluna   Tipo/Tamanho                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREGISTROREQUISICOESSERVICOS               CODIGO   NUMBER(10,0)                                              Código do registro e pk da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCREGISTROREQUISICOESSERVICOS   DATAHORAREQUISICAO           DATE                                          Data/ hora que a requisição foi feita            OPERACIONAL                        NaN
PCREGISTROREQUISICOESSERVICOS PROCESSOREQUISITANTE  VARCHAR2(200)                                              Processo que requisitou o serviço            OPERACIONAL                        NaN
PCREGISTROREQUISICOESSERVICOS   SERVICOREQUISITADO  VARCHAR2(200)                                 Nome/ descrição do serviço que foi requisitado            OPERACIONAL                        NaN
PCREGISTROREQUISICOESSERVICOS  RESULTADOREQUISICAO VARCHAR2(1000)                                     Texto/ mensagem de resultado da requisição            OPERACIONAL                        NaN
PCREGISTROREQUISICOESSERVICOS            CODFILIAL    VARCHAR2(2)                                  Código da filial onde o serviço foi executado            OPERACIONAL                        NaN
PCREGISTROREQUISICOESSERVICOS        IDENTIFICADOR  VARCHAR2(120) Identificador do registro ou grupo de registro, para facilitar busca dos dados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*