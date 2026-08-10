# 📊 Tabela: PCPRESTANTECIPADA

### Estrutura de Colunas e Restrições

           Tabela                Coluna Tipo/Tamanho                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRESTANTECIPADA  NUMTRANSPAGADIANTADO NUMBER(10,0)                                               TRANSAÇÃO DE PAGAMENTO ANTECIPADO    CHAVE PRIMÁRIA (PK)                        NaN
PCPRESTANTECIPADA                CODCLI  NUMBER(9,0)             CAMPO QUE IDENTIFICA COM QUAL CLIENTE ESSE PAGAMENTO ESTÁ VINCULADO            OPERACIONAL                        NaN
PCPRESTANTECIPADA             CODFILIAL  VARCHAR2(2)                                               CAMPO QUE FILIAL É ESSE PAGAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA                NUMPED NUMBER(10,0)    CAMPO QUE IDENTIFICA COM QUAL PEDIDO DA PCPEDC ESSE PAGAMENTO ESTÁ VINCULADO            OPERACIONAL                        NaN
PCPRESTANTECIPADA               NUMORCA NUMBER(10,0) CAMPO QUE IDENTIFICA COM QUAL ORÇAMENTO DA PCPEDC ESSE PAGAMENTO ESTÁ VINCULADO            OPERACIONAL                        NaN
PCPRESTANTECIPADA         COBANTECIPADA  VARCHAR2(1)               CAMPO QUE IDENTIFICA SE A COBRANÇA É DO TIPO PAGAMENTO ANTECIPADO            OPERACIONAL                        NaN
PCPRESTANTECIPADA          QUITAPCPREST  VARCHAR2(1)      CAMPO QUE IDENTIFICA SE A PCPREST DEVERÁ SER QUITADA NO ATO DO FATURAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA                 VALOR NUMBER(10,2)                                                              VALOR DO PAGAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA     VLRCREDITOABATIDO NUMBER(10,2)                              VALOR DOS CRÉDITOS UTILIZADOS AO GERAR O PAGAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA           VALORPEDIDO NUMBER(10,2)                                                     VALOR DO PEDIDO / ORÇAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA            CODCOBPGTO  VARCHAR2(4)                                                           COBRANÇA DO PAGAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA            STATUSPGTO VARCHAR2(50)                                                             STATUS DO PAGAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA          DTEMISSAOPED         DATE                                             DATA DA EMISSÃO DO PEDIDO/ORÇAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA         DTGERACAOPGTO         DATE                                         DATA DA GERAÇÃO DO PAGAMENTO ANTECIPADO            OPERACIONAL                        NaN
PCPRESTANTECIPADA     DTCONFIRMACAOPGTO         DATE                                                DATA DA CONFIRMAÇÃO DO PAGAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA                DTPGTO         DATE                                              DATA DO PAGAMENTO INFORMADO NA API            OPERACIONAL                        NaN
PCPRESTANTECIPADA             DTESTORNO         DATE                                                                 DATA DO ESTORNO            OPERACIONAL                        NaN
PCPRESTANTECIPADA       NUMTRANSESTORNO NUMBER(10,0)                                                            TRANSAÇÃO DE ESTORNO            OPERACIONAL                        NaN
PCPRESTANTECIPADA      MATRICULAGERACAO  NUMBER(8,0)                                      MATRÍCULA DO USUÁRIO QUE GEROU O PAGAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA  MATRICULACONFIRMACAO  NUMBER(8,0)                                  MATRÍCULA DO USUÁRIO QUE CONFIRMOU O PAGAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA      MATRICULAESTORNO  NUMBER(8,0)                                   MATRÍCULA DO USUÁRIO QUE ESTORNOU O PAGAMENTO            OPERACIONAL                        NaN
PCPRESTANTECIPADA              NUMTRANS NUMBER(10,0)                                                             Número de Transação            OPERACIONAL                        NaN
PCPRESTANTECIPADA                NSUTEF VARCHAR2(20)                                                           Número sequencial TEF            OPERACIONAL                        NaN
PCPRESTANTECIPADA               NSUHOST VARCHAR2(20)                                                       Identificador do host TEF            OPERACIONAL                        NaN
PCPRESTANTECIPADA               CODREDE VARCHAR2(10)                                                   Código da rede de adquirência            OPERACIONAL                        NaN
PCPRESTANTECIPADA         QTDPARCELATEF  NUMBER(2,0)                                                      Quantidade de parcelas TEF            OPERACIONAL                        NaN
PCPRESTANTECIPADA NOME_CARTEIRA_DIGITAL VARCHAR2(50)                                              Nome da carteira digital utilizada            OPERACIONAL                        NaN
PCPRESTANTECIPADA     CODADMINISTRADORA VARCHAR2(10)                                              Código da administradora do cartão            OPERACIONAL                        NaN
PCPRESTANTECIPADA           CODBANDEIRA  VARCHAR2(5)                                                    Código da bandeira do cartão            OPERACIONAL                        NaN
PCPRESTANTECIPADA    NUMTRANSPAGDIGITAL VARCHAR2(50)                                 Identificador da transação de pagamento digital            OPERACIONAL                        NaN
PCPRESTANTECIPADA        NUMCAIXAFISCAL  NUMBER(4,0)                                                          NUMERO DO CAIXA FISCAL            OPERACIONAL                        NaN
PCPRESTANTECIPADA       CODFUNCCHECKOUT  NUMBER(8,0)                                               CÓDIGO DO FUNCIONÁRIO DO CHECKOUT            OPERACIONAL                        NaN
PCPRESTANTECIPADA              NUMCAIXA  NUMBER(4,0)                                                                 NÚMERO DO CAIXA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*