# 📊 Tabela: PCINTEGRACAOROTASERVICO

### Estrutura de Colunas e Restrições

                 Tabela                         Coluna Tipo/Tamanho                                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOROTASERVICO                             ID NUMBER(10,0)                                                                                      Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOROTASERVICO                   IDEMPRESAAPI NUMBER(10,0)                                                                  Chave extangeira pra a tabela da empresa API CHAVE ESTRANGEIRA (FK)   PCINTEGRACAODADOSEMPRESA
PCINTEGRACAOROTASERVICO                        SERVICO VARCHAR2(40)                                                                  Armazena o nome da rota de envio ou de busca            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO              LAYOUTCOMUNICACAO         CLOB                               Armazena o layout de comunicação, responsável pelo request e response com a api            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO            LAYOUTTRANSFORMACAO         CLOB Armazena o layout de transformação, responsável por transformar os dados recebidos pelo layout de comunicação            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO                    ARQUITETURA VARCHAR2(20)                                                                                           Arquitetura da rota            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO                          ATIVO  VARCHAR2(1)                                                                                    Armazeza o status da rota             OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO                   TIPOPROCESSO VARCHAR2(80)                                                                                      Tipo de processo da rota            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO                   AUTENTICADOR  VARCHAR2(1)                                                          Armazena o valor S caso a rota seja uma autenticação            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO                DATASINCRONISMO         DATE                                                                                           Data de sincronismo            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO                   REFRESHTOKEN  VARCHAR2(1)                                                        Armazena o valor S caso a rota seja para refresh token            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO                IDROTAIDEXTERNO NUMBER(10,0)                                                                                          Id da rota idexterno            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO SOMENTEATUALIZARINTEGRACAOCORE  VARCHAR2(1)                                                                                  Somente atualizar integração            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO               IDROTAPRECEDENTE NUMBER(10,0)                                                        Vincula a rota serviço precedente com a rota precedida            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO           GRAVARDADOSRECEBIDOS  VARCHAR2(1)                                                                     Indica se será gravado os dados recebidos            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO                  PAGINAINICIAL  NUMBER(5,0)                      Define a página inicial da busca quando o tipoprocesso for igual a BUSCAR. O padrão é 1;            OPERACIONAL                        NaN
PCINTEGRACAOROTASERVICO              MANTERCAMPOSNULOS  VARCHAR2(1)                                            Define se manterá os campos null do json após a transformação Jolt            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*