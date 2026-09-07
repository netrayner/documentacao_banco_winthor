# 📊 Tabela: PCLOGDADOSPESSOASECF

### Estrutura de Colunas e Restrições

              Tabela          Coluna   Tipo/Tamanho                                                                                                                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDADOSPESSOASECF       NUMPEDECF   NUMBER(10,0)                                                                                                                                                                      Número do Pedido na ECF.            OPERACIONAL                        NaN
PCLOGDADOSPESSOASECF DATA_REQUISICAO           DATE                                                                                                                                  Data/ hora do evento no PDV (venda, alteração de dados, etc)            OPERACIONAL                        NaN
PCLOGDADOSPESSOASECF       DESCRICAO VARCHAR2(1500)                                                                                                      Descrição do evento. Ex: "Alteração de dados cadastrais", "Emissão de cupom fiscal", etc            OPERACIONAL                        NaN
PCLOGDADOSPESSOASECF CODIGO_CADASTRO   VARCHAR2(50)                                                                                                                          Valor que identifica o cliente na tabela a qual ele está armazenado.            OPERACIONAL                        NaN
PCLOGDADOSPESSOASECF          TABELA   VARCHAR2(60)                                                                                                                        Tabela a qual o cliente está armazenado, PCCLIENT, PCVENDACONSUM, etc.            OPERACIONAL                        NaN
PCLOGDADOSPESSOASECF       MATRICULA    NUMBER(8,0)                                                                                                                                                      Matricula do usuário que operou a rotina            OPERACIONAL                        NaN
PCLOGDADOSPESSOASECF          ROTINA   VARCHAR2(10)                                                                                                                                                Nome do programa utilizado para gerar o evento            OPERACIONAL                        NaN
PCLOGDADOSPESSOASECF            HASH   VARCHAR2(64) Concatenar os valores dos campos que serão armazenados (DATA_REGISTRO + DATA_REQUISICAO + DESCRICAO + DADOS_ANTERIOR + DADOS_ATUAL + CODIGO_CADASTRO + TABELA + MATRICULA + ROTINA + [SALT]).            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*