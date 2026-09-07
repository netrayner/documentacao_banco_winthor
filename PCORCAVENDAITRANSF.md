# 📊 Tabela: PCORCAVENDAITRANSF

### Estrutura de Colunas e Restrições

            Tabela              Coluna  Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORCAVENDAITRANSF             NUMORCA  NUMBER(10,0)                    Número do orçamento de origem            OPERACIONAL                        NaN
PCORCAVENDAITRANSF             CODPROD   NUMBER(6,0)                    Código do produto transferido            OPERACIONAL                        NaN
PCORCAVENDAITRANSF              NUMSEQ  NUMBER(20,0)        Número sequencial do produto no orçamento            OPERACIONAL                        NaN
PCORCAVENDAITRANSF              PVENDA  NUMBER(19,6)                        Preço de venda do produto            OPERACIONAL                        NaN
PCORCAVENDAITRANSF             PTABELA  NUMBER(19,6)                       Preço de tabela do produto            OPERACIONAL                        NaN
PCORCAVENDAITRANSF                  QT  NUMBER(26,6)                           Quantidade Transferida            OPERACIONAL                        NaN
PCORCAVENDAITRANSF         CODAUXILIAR  NUMBER(16,0)                       Código de barra do produto            OPERACIONAL                        NaN
PCORCAVENDAITRANSF               CODST   NUMBER(4,0)                          Código do ST do produto            OPERACIONAL                        NaN
PCORCAVENDAITRANSF          DTABERTURA          DATE                         Data de Abertura da mesa            OPERACIONAL                        NaN
PCORCAVENDAITRANSF        NUMFICHAORIG  NUMBER(10,0)                        Número da ficha de origem            OPERACIONAL                        NaN
PCORCAVENDAITRANSF        NUMFICHADEST  NUMBER(10,0)                       Número da ficha de destino            OPERACIONAL                        NaN
PCORCAVENDAITRANSF         NUMORCADEST  NUMBER(10,0)                   Número do orçamento de destino            OPERACIONAL                        NaN
PCORCAVENDAITRANSF          DATATRANSF          DATE                 Data da transferencia do produto            OPERACIONAL                        NaN
PCORCAVENDAITRANSF       CODFUNCTRANSF   NUMBER(8,0)              Código do funcionario transferencia            OPERACIONAL                        NaN
PCORCAVENDAITRANSF  CODSUPERVLIBTRANSF   NUMBER(8,0) Código do supervisor que liberou a transferencia            OPERACIONAL                        NaN
PCORCAVENDAITRANSF  IMPRIMERESTAURANTE   VARCHAR2(1)                   Imprime produto no restaurante            OPERACIONAL                        NaN
PCORCAVENDAITRANSF IMPRESSORESTAURANTE   VARCHAR2(1)                  Produto impresso no restaurante            OPERACIONAL                        NaN
PCORCAVENDAITRANSF     CODGARCOMTRANSF   NUMBER(8,0)   Código do Garçom que solicitou a transferencia            OPERACIONAL                        NaN
PCORCAVENDAITRANSF           CODFILIAL   VARCHAR2(2)                                 Código da filial            OPERACIONAL                        NaN
PCORCAVENDAITRANSF              CODIMP   NUMBER(6,0)       Código da impressora que imprime o produto            OPERACIONAL                        NaN
PCORCAVENDAITRANSF     NUMSEQIMPRESSAO   NUMBER(6,0)        Número sequencial de impressão do produto            OPERACIONAL                        NaN
PCORCAVENDAITRANSF        MOTIVOTRANSF VARCHAR2(120)                             Motivo transferencia            OPERACIONAL                        NaN
PCORCAVENDAITRANSF        ROTINATRANSF  VARCHAR2(48)            Rotina que fez o lançamento na tabela            OPERACIONAL                        NaN
PCORCAVENDAITRANSF          TIPOTRANSF   VARCHAR2(1)           TIpo de transferencia Total ou Parcial            OPERACIONAL                        NaN
PCORCAVENDAITRANSF    DTENVIOSERVCARGA          DATE           Data de envio para o servidor de carga            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*