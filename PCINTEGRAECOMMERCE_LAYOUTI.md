# 📊 Tabela: PCINTEGRAECOMMERCE_LAYOUTI

### Estrutura de Colunas e Restrições

                    Tabela        Coluna  Tipo/Tamanho                                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRAECOMMERCE_LAYOUTI     CODLAYOUT   NUMBER(6,0)                                           Código do layout referente a tabela PCINTEGRAECOMMERCE_LAYOUTC    CHAVE PRIMÁRIA (PK) PCINTEGRAECOMMERCE_LAYOUTC
PCINTEGRAECOMMERCE_LAYOUTI          TIPO  VARCHAR2(25)                                             Tipo de configuração disponível (CREDENCIAIS, CONFIGURACOES)    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRAECOMMERCE_LAYOUTI         CAMPO  VARCHAR2(50)                                                              Nome do campo a ser utilizado na integração    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRAECOMMERCE_LAYOUTI     DESCRICAO VARCHAR2(200)                                                                                          Descrição livre            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_LAYOUTI     TIPOCAMPO  VARCHAR2(20) Coluna utilizada por rotina Delphi, indica o tipo do campo para exibição de input (ex: VARCHAR2, NUMBER)            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_LAYOUTI   OBRIGATORIO   VARCHAR2(1)                               Coluna utilizada por rotina Delphi para sinalizar se o campo é obrigatório            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_LAYOUTI ORDEMEXIBICAO   NUMBER(5,0)                                Coluna utilizada por rotina Delphi, indica a ordem de exibição dos campos            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_LAYOUTI      EDITAVEL   VARCHAR2(1)                                         Coluna utilizada por rotina Delphi, indica se o campo é editável            OPERACIONAL                        NaN
PCINTEGRAECOMMERCE_LAYOUTI       VISIVEL   VARCHAR2(1)                                          Coluna utilizada por rotina Delphi, indica se o campo é visível            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*