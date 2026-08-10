# 📊 Tabela: PCEDITAIS

### Estrutura de Colunas e Restrições

   Tabela                    Coluna   Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEDITAIS                 CODEDITAL    NUMBER(9,0)                                     Código edital.    CHAVE PRIMÁRIA (PK)                        NaN
PCEDITAIS                  CODBANCO    NUMBER(4,0)                                      Código banco.            OPERACIONAL                        NaN
PCEDITAIS                    CODCLI    NUMBER(6,0)                                    Código cliente.            OPERACIONAL                        NaN
PCEDITAIS       CONDICOES_PAGAMENTO   VARCHAR2(50)                            Condições do pagamento.            OPERACIONAL                        NaN
PCEDITAIS   DATA_ABERTURA_LICITACAO           DATE                     Data da abertura da licitação.            OPERACIONAL                        NaN
PCEDITAIS    DATA_ENTREGA_ENVELOPES           DATE                     Data da entrega dos envelopes.            OPERACIONAL                        NaN
PCEDITAIS                  DECIMAIS    NUMBER(1,0)                                          Decimais.            OPERACIONAL                        NaN
PCEDITAIS DECLARACAO_CREDENCIAMENTO        CHAR(1)                      Declaração do credenciamento.            OPERACIONAL                        NaN
PCEDITAIS    DECLARACAO_HABILITACAO        CHAR(1)                         Declaração da habilitação.            OPERACIONAL                        NaN
PCEDITAIS   DECLARACAO_INEXISTENCIA        CHAR(1)                        Declaração da inexistencia.            OPERACIONAL                        NaN
PCEDITAIS        DECLARACAO_MENORES        CHAR(1)                            Declaração dos menores.            OPERACIONAL                        NaN
PCEDITAIS                   CODATIV    NUMBER(6,0)                                  Código atividade.            OPERACIONAL                        NaN
PCEDITAIS                 CODFILIAL    VARCHAR2(2)                                     Código Filial.            OPERACIONAL                        NaN
PCEDITAIS   HORA_ABERTURA_LICITACAO           DATE                     Hora da abertura da Licitacao.            OPERACIONAL                        NaN
PCEDITAIS    HORA_ENTREGA_ENVELOPES           DATE                     Hora da entrega dos envelopes.            OPERACIONAL                        NaN
PCEDITAIS             CODMODALIDADE    NUMBER(4,0)                                 Código modalidade.            OPERACIONAL                        NaN
PCEDITAIS              NUMERO_CONTA   VARCHAR2(20)                                   Numero da conta.            OPERACIONAL                        NaN
PCEDITAIS            NUMERO_EMPENHO   VARCHAR2(20)                                 Numero do empenho.            OPERACIONAL                        NaN
PCEDITAIS          NUMERO_LICITACAO   VARCHAR2(20)                                  Numero licitacao.            OPERACIONAL                        NaN
PCEDITAIS           NUMERO_PROCESSO   VARCHAR2(20)                                   Numero processo.            OPERACIONAL                        NaN
PCEDITAIS                    OBJETO  VARCHAR2(255)                                            Obejto.            OPERACIONAL                        NaN
PCEDITAIS                OBSERVACAO VARCHAR2(4000)                                        Observação.            OPERACIONAL                        NaN
PCEDITAIS        OBSERVACAO_EMPENHO  VARCHAR2(100)                             Observação do empenho.            OPERACIONAL                        NaN
PCEDITAIS    OBSERVACAO_MAPA_PRECOS  VARCHAR2(100)                        Observação mapa dos preços.            OPERACIONAL                        NaN
PCEDITAIS       OBSERVACAO_PROPOSTA  VARCHAR2(100)                            Observação da proposta.            OPERACIONAL                        NaN
PCEDITAIS      PERCENTUAL_ACRESCIMO   NUMBER(10,4)                           Percentual de acrescimo.            OPERACIONAL                        NaN
PCEDITAIS     PERCENTUAL_DECRESCIMO   NUMBER(10,4)                          Percentual de decrescimo.            OPERACIONAL                        NaN
PCEDITAIS             PRAZO_ENTREGA   VARCHAR2(50)                                  Prazo de entrega.            OPERACIONAL                        NaN
PCEDITAIS             PROPOSTA_ICMS        CHAR(1)                                  Proposta de ICMS.            OPERACIONAL                        NaN
PCEDITAIS                 MATRICULA    NUMBER(8,0)                                         Matricula.            OPERACIONAL                        NaN
PCEDITAIS                    STATUS        CHAR(2)                                            Status.            OPERACIONAL                        NaN
PCEDITAIS            STATUS_CLIENTE        CHAR(1)                                 Status do cliente.            OPERACIONAL                        NaN
PCEDITAIS             TIPO_PROPOSTA        CHAR(2)                                  Tipo da proposta.            OPERACIONAL                        NaN
PCEDITAIS         VALIDADE_PRODUTOS   VARCHAR2(50)                             Validade dos produtos.            OPERACIONAL                        NaN
PCEDITAIS         VALIDADE_PROPOSTA   VARCHAR2(50)                              Validade da proposta.            OPERACIONAL                        NaN
PCEDITAIS                VALOR_ICMS   NUMBER(10,4)                                     Valor do ICMS.            OPERACIONAL                        NaN
PCEDITAIS     VERIFICAR_CERTIFICADO        CHAR(1)                              Verifica certificado.            OPERACIONAL                        NaN
PCEDITAIS        VERIFICAR_REGISTRO        CHAR(1)                                 Verifica registro.            OPERACIONAL                        NaN
PCEDITAIS                  VIGENCIA   VARCHAR2(30)                                          Vigencia.            OPERACIONAL                        NaN
PCEDITAIS           DATA_VENCIMENTO           DATE Data de Vencimento do contrato vinculado ao edital            OPERACIONAL                        NaN
PCEDITAIS                  CONTRATO   VARCHAR2(20)                       Contrato vinculado ao Edital            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*