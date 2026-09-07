# 📊 Tabela: PCGARANTIA

### Estrutura de Colunas e Restrições

    Tabela                      Coluna  Tipo/Tamanho                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGARANTIA                 NUMGARANTIA  NUMBER(10,0)                                                                                     Número da garantia    CHAVE PRIMÁRIA (PK)                        NaN
PCGARANTIA                NUMTRANSITEM  NUMBER(10,0)                                                               Chave estrangeira NUMTRANSITEM da PCMOV.            OPERACIONAL                        NaN
PCGARANTIA                    DATALANC          DATE                                                                        Data de lançamento do registro.            OPERACIONAL                        NaN
PCGARANTIA            DATAENCERRAMENTO          DATE                                                                      Data de encerramento da garantia.            OPERACIONAL                        NaN
PCGARANTIA                      CODCLI  NUMBER(10,0)                                                                         Cliente envolvido na garantia.            OPERACIONAL                        NaN
PCGARANTIA                     CODPROD  NUMBER(10,0)                                                                         Produto envolvido na garantia.            OPERACIONAL                        NaN
PCGARANTIA              ACEITAGARANTIA   VARCHAR2(1)                                                                                        Aceita Garantia            OPERACIONAL                        NaN
PCGARANTIA              STATUSANTERIOR   VARCHAR2(3)                                                                                        Status Anterior            OPERACIONAL                        NaN
PCGARANTIA                      STATUS   VARCHAR2(3)                                                                                                 Status            OPERACIONAL                        NaN
PCGARANTIA                AGUARDALAUDO   VARCHAR2(1)                                                                                          Aguarda Laudo            OPERACIONAL                        NaN
PCGARANTIA           REPOSICAOIMEDIATA   VARCHAR2(1)                                                                                     Reposição Imediata            OPERACIONAL                        NaN
PCGARANTIA              RESULTADOLAUDO   VARCHAR2(1)                                                                                        Resultado Laudo            OPERACIONAL                        NaN
PCGARANTIA                PAGOUCLIENTE   VARCHAR2(1)                                                                                            Status. S/N            OPERACIONAL                        NaN
PCGARANTIA                  NUMREMESSA  NUMBER(10,0)                                                                                     Número de remessa.            OPERACIONAL                        NaN
PCGARANTIA      NUMTRANSVENDAAOCLIENTE  NUMBER(10,0)                                                               Número de transação de Venda ao cliente             OPERACIONAL                        NaN
PCGARANTIA        NUMTRANSENTDOCLIENTE  NUMBER(10,0)                                                   Número de transação de entrada p/Garantia do cliente            OPERACIONAL                        NaN
PCGARANTIA         NUMTRANSVENDAFORNEC  NUMBER(10,0)                                                             Número de transação de saída ao Fornecedor            OPERACIONAL                        NaN
PCGARANTIA         NUMTRANSENTDOFORNEC  NUMBER(10,0)                                                           Número de transação de entrada ao Fornecedor            OPERACIONAL                        NaN
PCGARANTIA    NUMTRANSVENDAPAGGARANTIA  NUMBER(10,0)           Número de transação de saída para atender garantia ao cliente (1322 - Saída Simples remessa)            OPERACIONAL                        NaN
PCGARANTIA NUMTRANSVENDAPRODDEFEITUOSO  NUMBER(10,0) Número de transação de saída para devolver produto velho ou defeituoso ( 1322 - saída simples remessa)            OPERACIONAL                        NaN
PCGARANTIA                    NUMSERIE  VARCHAR2(30)                                                               Número de serie que identifica cada peça            OPERACIONAL                        NaN
PCGARANTIA                         OBS VARCHAR2(300)                                                                                           Observações.            OPERACIONAL                        NaN
PCGARANTIA                CODFILIALDEV   VARCHAR2(2)                                                                          Código de Filial de Devolução            OPERACIONAL                        NaN
PCGARANTIA                   CODFORNEC   NUMBER(6,0)                                     Código do Fornecedor do Produto que Entrou no Processo de Garantia            OPERACIONAL                        NaN
PCGARANTIA                    NUMBONUS  NUMBER(10,0)                                                                                        Número do Bônus            OPERACIONAL                        NaN
PCGARANTIA                  DTEXCLUSAO          DATE                                                                          Data de exclusão da garantia.            OPERACIONAL                        NaN
PCGARANTIA                  NUMCREDITO  NUMBER(10,0)                                                                Número de crédito gerado pela peça nova            OPERACIONAL                        NaN
PCGARANTIA     RESULTADOLAUDOALTMANUAL   VARCHAR2(1)                                            Identifica se o Resultado do Laudo foi alterado manualmente            OPERACIONAL                        NaN
PCGARANTIA             CODFUNCULTALTER   NUMBER(8,0)                                              Código do Funcionário que fez a última edição no registro            OPERACIONAL                        NaN
PCGARANTIA                   FORMAPGTO   VARCHAR2(1)                                                                                     Forma de pagamento            OPERACIONAL                        NaN
PCGARANTIA                  ROTINAPGTO  VARCHAR2(15)                                                                         Rotina que efetuou o pagamento            OPERACIONAL                        NaN
PCGARANTIA                ENVIARFORNEC   VARCHAR2(1)                                        Define se o item de garantia será enviado ou não ao fornecedor.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*