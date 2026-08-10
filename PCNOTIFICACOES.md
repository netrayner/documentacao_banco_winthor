# 📊 Tabela: PCNOTIFICACOES

### Estrutura de Colunas e Restrições

        Tabela                   Coluna Tipo/Tamanho                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNOTIFICACOES                SEQUENCIA NUMBER(10,0)                                                     Sequencial da justificativa    CHAVE PRIMÁRIA (PK)                        NaN
PCNOTIFICACOES             CODIGOROTINA  NUMBER(4,0)                                                     Código da rotina do winthor            OPERACIONAL                        NaN
PCNOTIFICACOES         DATAHORACADASTRO         DATE                                             Data e hora da inclusão do registro            OPERACIONAL                        NaN
PCNOTIFICACOES               VERSAOERRO VARCHAR2(15)                                             Versão de erro da rotina do winthor            OPERACIONAL                        NaN
PCNOTIFICACOES            VERSAOSOLUCAO VARCHAR2(15)                                         Versao de correção da rotina do winthor            OPERACIONAL                        NaN
PCNOTIFICACOES                 MENSAGEM         BLOB      Mensagem que será apresentada para o usuario durante a abertura do winthor            OPERACIONAL                        NaN
PCNOTIFICACOES   BLOQUEIAABERTURAROTINA  VARCHAR2(1)               Bloqueia ou não a abertura da rotina durante a sua execução (S/N)            OPERACIONAL                        NaN
PCNOTIFICACOES                     TIPO  VARCHAR2(1)                   Indica o tipo do cadastro que pode ser para F=FEED / R=RECALL            OPERACIONAL                        NaN
PCNOTIFICACOES DATAHORAPRIMEIRAEXECUCAO         DATE                           Data e hora da primeira execução da rotina no cliente            OPERACIONAL                        NaN
PCNOTIFICACOES   BLOQUEAREXECUCAOEMDIAS  NUMBER(3,0)                                         Bloqueia a execução da rotina em x dias            OPERACIONAL                        NaN
PCNOTIFICACOES                   STATUS  VARCHAR2(1) Indica o status atual do registro que pode ser: N=NOVO, R=REJEITADO, A=APROVADO            OPERACIONAL                        NaN
PCNOTIFICACOES         SEQUENCIAANULADA NUMBER(10,0)                                           Número da sequêencia que sera anulada            OPERACIONAL                        NaN
PCNOTIFICACOES       VERSAOERRONUMERICO NUMBER(12,0)                                              Versão do erro em formato numérico            OPERACIONAL                        NaN
PCNOTIFICACOES    VERSAOSOLUCAONUMERICO NUMBER(12,0)                                          Versão de correção em formato numérico            OPERACIONAL                        NaN
PCNOTIFICACOES          CODIGOROTINADEP  NUMBER(4,0)                                                                             NaN            OPERACIONAL                        NaN
PCNOTIFICACOES                    OPCAO  NUMBER(6,0)                                                                             NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*