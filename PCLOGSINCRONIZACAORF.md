# 📊 Tabela: PCLOGSINCRONIZACAORF

### Estrutura de Colunas e Restrições

              Tabela                   Coluna Tipo/Tamanho                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGSINCRONIZACAORF                       ID NUMBER(10,0)                                                 Identificador do processo em execução            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF                   ORIGEM VARCHAR2(10)                                        Origem da criação do registro. (APP ou SERVER)            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF            DATA_INSERCAO         DATE                                                  Data da criação do registro no banco            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF       DATA_SINCRONIZACAO         DATE                                      Data da gravação da sincorinazação com o Winthor            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF                   TABELA VARCHAR2(40)                                                       Tabela manipulada pelo processo            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF SINCRONIZACAO_AUTOMATICA  VARCHAR2(1)                                                     Sincronização automática (S ou N)            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF              USUARIO_APP VARCHAR2(30)                                                                 Usuário do aplicativo            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF               VERSAO_APP VARCHAR2(15)                                                                  Versão do aplicativo            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF           VERSAO_SERVICO VARCHAR2(50)                                                                     Versão do serviço            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF                   STATUS VARCHAR2(10)                                    Status da sincronização(CONCLUIDO, FALHA, PARCIAL)            OPERACIONAL                        NaN
PCLOGSINCRONIZACAORF               OBSERVACAO         CLOB Campo usado para salvar causas de exceção e/ou informações importantes para histórico            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*