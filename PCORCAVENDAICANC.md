# 📊 Tabela: PCORCAVENDAICANC

### Estrutura de Colunas e Restrições

          Tabela              Coluna  Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORCAVENDAICANC             NUMORCA  NUMBER(10,0)                                                 Número orçamento            OPERACIONAL                        NaN
PCORCAVENDAICANC             CODPROD   NUMBER(6,0)                                                   Código produto            OPERACIONAL                        NaN
PCORCAVENDAICANC              NUMSEQ  NUMBER(20,0)                                              Número de sequencia            OPERACIONAL                        NaN
PCORCAVENDAICANC              PVENDA  NUMBER(19,6)                                                   Preço de venda            OPERACIONAL                        NaN
PCORCAVENDAICANC             PTABELA  NUMBER(19,6)                                                  Preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAICANC                  QT  NUMBER(20,6)                                                       Quantidade            OPERACIONAL                        NaN
PCORCAVENDAICANC         CODAUXILIAR  NUMBER(16,0)                               Código de barras de uma embalagem.            OPERACIONAL                        NaN
PCORCAVENDAICANC               CODST   NUMBER(4,0)                            Código da situação tributária do item            OPERACIONAL                        NaN
PCORCAVENDAICANC          DTABERTURA          DATE                                                   Data abertura.            OPERACIONAL                        NaN
PCORCAVENDAICANC        NUMFICHAORIG  NUMBER(10,0)                                          Número de ficha origem.            OPERACIONAL                        NaN
PCORCAVENDAICANC        NUMFICHADEST  NUMBER(10,0)                                         Número de ficha destino.            OPERACIONAL                        NaN
PCORCAVENDAICANC         NUMORCADEST  NUMBER(10,0)                                        Número orçamento destino.            OPERACIONAL                        NaN
PCORCAVENDAICANC            DATACANC          DATE                                               Data cancelamento.            OPERACIONAL                        NaN
PCORCAVENDAICANC         CODFUNCCANC   NUMBER(8,0)                                 Código funcionário cancelamento.            OPERACIONAL                        NaN
PCORCAVENDAICANC    CODSUPERVLIBCANC   NUMBER(8,0)                 Supervisor que autorizou o cancelamento do item.            OPERACIONAL                        NaN
PCORCAVENDAICANC  IMPRIMERESTAURANTE   VARCHAR2(1)                          Embalagem permite impressão restaurante            OPERACIONAL                        NaN
PCORCAVENDAICANC IMPRESSORESTAURANTE   VARCHAR2(1)                                      Status de impressão do item            OPERACIONAL                        NaN
PCORCAVENDAICANC       CODGARCOMCANC   NUMBER(8,0) Código do garçom responsável pelo cancelamento de itens e mesas.            OPERACIONAL                        NaN
PCORCAVENDAICANC          TIPOCANCEL   VARCHAR2(1)                                             Tipo de cancelamento            OPERACIONAL                        NaN
PCORCAVENDAICANC           CODFILIAL   VARCHAR2(2)                                                 Código da filial            OPERACIONAL                        NaN
PCORCAVENDAICANC              CODIMP   NUMBER(6,0)                                       Cód. Cadastro de Impressão            OPERACIONAL                        NaN
PCORCAVENDAICANC     NUMSEQIMPRESSAO   NUMBER(6,0)                                Núm. Sêq de Impressâo Restaurante            OPERACIONAL                        NaN
PCORCAVENDAICANC          MOTIVOCANC VARCHAR2(120)                                           Motivo de cancelamento            OPERACIONAL                        NaN
PCORCAVENDAICANC          ROTINALANC  VARCHAR2(48)                               Última rotina que alterou a tabela            OPERACIONAL                        NaN
PCORCAVENDAICANC    DTENVIOSERVCARGA          DATE                           Data de envio para o servidor de carga            OPERACIONAL                        NaN
PCORCAVENDAICANC            SITUACAO  VARCHAR2(20)              Situação do item se e cancelamento ou transferencia            OPERACIONAL                        NaN
PCORCAVENDAICANC              MD5PAF VARCHAR2(200)                                   Hash das informações do PAFECF            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*