# 📊 Tabela: PCDESPESAIMPCE

### Estrutura de Colunas e Restrições

        Tabela             Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESPESAIMPCE IDCONTROLEEMBARQUE VARCHAR2(20)         Identificação do controle de embarque.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESPESAIMPCE         CODDESPESA NUMBER(10,0)                Código da despesa de importação    CHAVE PRIMÁRIA (PK)                        NaN
PCDESPESAIMPCE             DTVENC         DATE               Data de vencimento do lançamento    CHAVE PRIMÁRIA (PK)                        NaN
PCDESPESAIMPCE              VALOR NUMBER(22,6)                               Valor da despesa            OPERACIONAL                        NaN
PCDESPESAIMPCE        VLREALIZADO NUMBER(22,6)                                Valor realizado            OPERACIONAL                        NaN
PCDESPESAIMPCE               VALE  VARCHAR2(2)                                           Vale            OPERACIONAL                        NaN
PCDESPESAIMPCE             RECNUM  NUMBER(8,0)          Número do lançamento na tabela PCLANC            OPERACIONAL                        NaN
PCDESPESAIMPCE          CODFORNEC  NUMBER(6,0)                          Código do fornecedor.            OPERACIONAL                        NaN
PCDESPESAIMPCE            NUMNOTA NUMBER(10,0)                     Número do documento fiscal            OPERACIONAL                        NaN
PCDESPESAIMPCE           CODBANCO  NUMBER(4,0)            Código do banco conta vale pendente            OPERACIONAL                        NaN
PCDESPESAIMPCE       NUMDOCUMENTO VARCHAR2(20)      Número de documento de despesa importação            OPERACIONAL                        NaN
PCDESPESAIMPCE          VLDESPESA NUMBER(18,6)                Valor da despesa em moeda da DI            OPERACIONAL                        NaN
PCDESPESAIMPCE          VLCOTACAO NUMBER(14,6)              Cotação da moeda da despesa na DI            OPERACIONAL                        NaN
PCDESPESAIMPCE        VALORFISCAL NUMBER(18,6)        Valor fiscal da despesa calculado na DI            OPERACIONAL                        NaN
PCDESPESAIMPCE     VLCOTACAOCUSTO NUMBER(14,6)                           Cotação custo fiscal            OPERACIONAL                        NaN
PCDESPESAIMPCE   MOEDAESTRANGEIRA  VARCHAR2(1)    Informa se a despesa é em moeda estrangeira            OPERACIONAL                        NaN
PCDESPESAIMPCE            CODHIST NUMBER(10,0)                 Código do historico da despesa            OPERACIONAL                        NaN
PCDESPESAIMPCE             NUMPED NUMBER(10,0)                     Número do pedido de compra            OPERACIONAL                        NaN
PCDESPESAIMPCE         CODMOEDADI  NUMBER(6,0)                    Código da moeda estrangeira            OPERACIONAL                        NaN
PCDESPESAIMPCE        DTCOTACAODI         DATE               Data da cotação moeda estrageira            OPERACIONAL                        NaN
PCDESPESAIMPCE      CODMOEDACUSTO  NUMBER(6,0)                    Código da moeda estrangeira            OPERACIONAL                        NaN
PCDESPESAIMPCE     DTCOTACAOCUSTO         DATE               Data da cotação moeda estrageira            OPERACIONAL                        NaN
PCDESPESAIMPCE       FORACONTROLE  VARCHAR2(1)           Feito dentro do controle de embarque            OPERACIONAL                        NaN
PCDESPESAIMPCE             GERACP  VARCHAR2(1) Informa se a despesa deve gerar contas a pagar            OPERACIONAL                        NaN
PCDESPESAIMPCE        CODCOBSEFAZ  VARCHAR2(4)                    Código de cobrança da Sefaz            OPERACIONAL                        NaN
PCDESPESAIMPCE          VALOR_BKP NUMBER(12,6)                                            NaN            OPERACIONAL                        NaN
PCDESPESAIMPCE    VLREALIZADO_BKP NUMBER(12,6)                                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*