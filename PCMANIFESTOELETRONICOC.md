# 📊 Tabela: PCMANIFESTOELETRONICOC

### Estrutura de Colunas e Restrições

                Tabela                     Coluna   Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFESTOELETRONICOC                    NUMMDFE   NUMBER(10,0)                                             NUMERO DO MANIFESTO    CHAVE PRIMÁRIA (PK)                        NaN
PCMANIFESTOELETRONICOC                      SERIE    NUMBER(3,0)                                              SERIE DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC            DATAHORAGERACAO           DATE                                               DATA DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC               SITUACAOMDFE    NUMBER(6,0)                                           SITUACAO DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC              PROTOCOLOMDFE   VARCHAR2(20)                                NUMERO DE PROTOCOLO DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC               AMBIENTEMDFE    VARCHAR2(1)                                           AMBIENTE DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                    NUMLOTE   NUMBER(15,0)                                     NUMERO DO LOTE DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                  CHAVEMDFE   VARCHAR2(44)                                    CHAVE DE ACESSO DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                   UFINICIO    VARCHAR2(2)                                       UF DE INICIO DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                      UFFIM    VARCHAR2(2)                                           UF FINAL DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC       MODALIDADETRANSPORTE    VARCHAR2(1)                           MODALIDADE DE TRANSPORTE NO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                  CODFILIAL    VARCHAR2(2)                                   CODIGO DA FILIAL DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC               CODMOTORISTA    NUMBER(8,0)                                    CODIGO DO MOTORISTA DO MDF-E            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                 CODVEICULO    NUMBER(4,0)                                      CODIGO DO VEICULO DO MDF-E            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                TIPOEMISSAO    NUMBER(1,0)                                    TIPO DE EMISSAO DO MANIFESTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC               NUMTRANSACAO   NUMBER(10,0)                                NUMERO DE TRANSAÇÃO DO MANIFESTO    CHAVE PRIMÁRIA (PK)                        NaN
PCMANIFESTOELETRONICOC          NUMTENTATIVAENVIO    NUMBER(3,0)                                   NUMERO DE TENTATIVAS DE ENVIO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC         DATAHORAAUTORSEFAZ           DATE                             DATA E HORA DE AUTORIZAÇÃO NA SEFAZ            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                 RECIBOMDFE   VARCHAR2(20)                                          NUMERO DO RECIBO MDF-E            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC       JUSTIFICATIVACONTING  VARCHAR2(256)                                   JUSTIFICATIVA DA CONTINGENCIA            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC        JUSTIFICATIVACANCEL  VARCHAR2(256)                                   JUSTIFICATIVA DE CANCELAMENTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                 CODFUNCGER    NUMBER(8,0)                         CODIGO DO FUNCIONARIO QUE GEROU O MDF-E            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC               CODFUNCENCER    NUMBER(8,0)                      CODIGO DO FUNCIONARIO QUE ENCERROU O MDF-E            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                CODFUNCCANC    NUMBER(8,0)                      CODIGO DO FUNCIONARIO QUE CANCELOU O MDF-E            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                CODVEICULO2    NUMBER(6,0)                              CODIGO DO SEGUNDO VEICULO DO MDF-E            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                     EVENTO    VARCHAR2(1)       EVENTO GERADO PARA O MDF-E (E - ENCERRADO, C - CANCELADO)            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                CODVEICULO3    NUMBER(6,0)                             CODIGO DO TERCEIRO VEICULO DO MDF-E            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC            PROTOCOLOEVENTO   VARCHAR2(20)                                             PROTOCOLO DO EVENTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC             DATAHORAEVENTO           DATE                                           DATA E HORA DO EVENTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC            CODCIDADEENCERR    NUMBER(6,0)                                CODIGO DA CIDADE DE ENCERRAMENTO            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC           NUMVIASIMPRESSAO    NUMBER(3,0)                                Quantidade de impressão do MDF-e            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC               TIPOEMITENTE    NUMBER(1,0)                                                Tipo de Emitente            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC               TODASFILIAIS    VARCHAR2(1)                                        Carregar NFs das filiais            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC      CODCIDADECARREGAMENTO   NUMBER(10,0)                           Município onde iniciou o carregamento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC   NUMTRANSACAOMDFEANTERIOR   NUMBER(10,0)                                     Transação do MDFe de origem            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                        OBS           CLOB                                             Observação do MDF-e            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC            VERSAOLAYOUTNFE    VARCHAR2(5)                            Versão do layout do arquivo na Sefaz            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC            CODVEICREBOQUE1         NUMBER                   Código do veículo reboque 1 utilizado no MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC            CODVEICREBOQUE2         NUMBER                   Código do veículo reboque 2 utilizado no MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC            CODVEICREBOQUE3         NUMBER                   Código do veículo reboque 3 utilizado no MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                     QRCODE VARCHAR2(1000)                                               QRCODE PARA MDF-e            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC        INDCARREGAPOSTERIOR    VARCHAR2(1)                    Indicador de carregamento posterior do MDF-e            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                     NUMSEQ    NUMBER(8,0)               Numero de sequencia do evento de inclusão do MDFe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC        CODPRODPREDOMINANTE   NUMBER(10,0)        Código do produto predominante na operação de transporte            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC        CODIGONUMERICOCHAVE    VARCHAR2(8)                             Código númerico que compoem a chave            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC              TIPOIMPRESSAO    VARCHAR2(1)                         Tipo de impressão (retrato ou paisagem)            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC CODCIDADEDESCARREGPRODPRED   NUMBER(10,0)     Codigo da cidade de descarregamento do produto predominante            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                 QTDVIAGENS    NUMBER(5,0) Quantidade total de viagens realizadas com o pagamento do Frete            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                  NUMVIAGEM    NUMBER(5,0)            Número de referência da viagem do MDF-e referenciado            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC               PROTOCOLODTE   VARCHAR2(20)                           Número do Protocolo de Geração do DTe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC                DATAHORADTE           DATE                         Data e hora de geração do protocolo DTe            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC             REJEITADOSEFAZ    VARCHAR2(1)                    Ampliação do cStat de retorno para 4 dígitos            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOC               QTDEPROCMDFE    NUMBER(6,0)                 Quantidade de tentativas de aprovação do MDF-e.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*