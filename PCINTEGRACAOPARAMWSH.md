# 📊 Tabela: PCINTEGRACAOPARAMWSH

### Estrutura de Colunas e Restrições

              Tabela                   Coluna  Tipo/Tamanho                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOPARAMWSH                       ID  NUMBER(10,0)                                Chave primária da tabela, armazena a numeração sequencial do cadastro    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOPARAMWSH                     NOME VARCHAR2(200)                                                                         Armazena o nome do parâmetro            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH                    VALOR VARCHAR2(500)                                                                        Armazena o valor do parâmetro            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH                DESCRICAO VARCHAR2(500)                                        Armazena a descrição detalhada da funcionalizada do parâmetro            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH                TIPOVALOR  VARCHAR2(20)              Armazena a tipificação de cada valor do parâmetro. Ex: (string, literal, data, boolean)            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH                    GRUPO  VARCHAR2(40)                                                         Armazena o grupo que cada parâmetro pertence            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH                    ATIVO   VARCHAR2(1)                                                                       Armazena o status do parâmetro            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH               DTCADASTRO          DATE                                                           Armazena a data que o parâmetro foi criado            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH               DTULTALTER          DATE                                                     Armazena a data de última alteração do parâmetro            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH                NOMEALIAS VARCHAR2(200)                                                                    Nome alternativo para o parâmetro            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH                 READONLY   VARCHAR2(1)                                                                     Definir se o campo será readOnly            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH                ORDENACAO  NUMBER(10,0)                                                                      Definir a ordenação na listagem            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH      RETORNAVALORDEFAULT   VARCHAR2(1) Indica se o parâmetro irá retornar o valor default automaticamente depois de um determinado período;            OPERACIONAL                        NaN
PCINTEGRACAOPARAMWSH TEMPORETORNAVALORDEFAULT   NUMBER(5,0)                  Indica o tempo em horas para retornar a configuração do valor default do parâmetro;            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*