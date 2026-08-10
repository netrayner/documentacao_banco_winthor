# 📊 Tabela: PCBONUSI

### Estrutura de Colunas e Restrições

  Tabela                    Coluna  Tipo/Tamanho                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBONUSI                  NUMBONUS  NUMBER(10,0)                                                                  Descricao coluna NUMBONUS            OPERACIONAL                        NaN
PCBONUSI                   CODPROD   NUMBER(6,0)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                      QTNF  NUMBER(20,6)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                 QTENTRADA  NUMBER(20,6)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                ENDERECADO   VARCHAR2(1)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                DTVALIDADE          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                 CODFORNEC   NUMBER(9,0)                                                                 Descricao coluna CODFORNEC            OPERACIONAL                        NaN
PCBONUSI                   CODEPTO   NUMBER(6,0)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                   QTSAIDA  NUMBER(20,6)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                  QTESTGER  NUMBER(20,6)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                DTULTSAIDA          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                  QTAVARIA  NUMBER(20,6)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                   NUMBONO   NUMBER(8,0)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI               PERCINTEIRO   NUMBER(6,3)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI              PERCQUEBRADO   NUMBER(6,3)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI              PERCIMPUREZA   NUMBER(6,3)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI              PERCVERMELHO   NUMBER(6,3)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI               PERCUMIDADE   NUMBER(6,3)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                 CODMOTIVO   NUMBER(4,0)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                   NUMLOTE  VARCHAR2(15)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                   QTFALTA  NUMBER(20,6)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                 QTEXCESSO  NUMBER(20,6)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI               DIVERGENCIA   VARCHAR2(2)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI            OBSDIVERGENCIA VARCHAR2(300)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI           TIPODIVERGENCIA   NUMBER(4,0)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI CODFUNCSOLUCAODIVERGENCIA   NUMBER(8,0)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI      DTSOLUCAODIVERGENCIA          DATE                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI                 CONFERIDA   VARCHAR2(1)                                                                 Utilizado na rotina 1799.             OPERACIONAL                        NaN
PCBONUSI                QTAVARIANF  NUMBER(16,3)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI       TOLERANCIASHELFLIFE   NUMBER(4,0)                                                                                        NaN            OPERACIONAL                        NaN
PCBONUSI       QTBLOQUEADALIBERADA   VARCHAR2(1)                                                             Quantidade bloqueada liberada.            OPERACIONAL                        NaN
PCBONUSI            DATAFABRICACAO          DATE                                                       Indica a data de fabricação do item.            OPERACIONAL                        NaN
PCBONUSI                    NUMSEQ  NUMBER(20,0)                                                                        NÚmero de Sequencia            OPERACIONAL                        NaN
PCBONUSI           QTDEPECAPESAGEM   NUMBER(8,0)                                                                     Qtde. peças na pesagem            OPERACIONAL                        NaN
PCBONUSI          VALORTARAPORPECA  NUMBER(18,6)                                                                     Valor da tara por peça            OPERACIONAL                        NaN
PCBONUSI                 NUMLOTENF  VARCHAR2(15)                                                          Lote origninal da nota de entrada            OPERACIONAL                        NaN
PCBONUSI               QTENTRADACX  NUMBER(20,6)                                                            Quantidade de entrada de caixas            OPERACIONAL                        NaN
PCBONUSI                QTAVARIACX  NUMBER(20,6)                                                     Quantidade de avaria em caixa no bônus            OPERACIONAL                        NaN
PCBONUSI                   QTENTCX  NUMBER(20,6)                                                               Quantidade em caixa no bônus            OPERACIONAL                        NaN
PCBONUSI                   QTENTUN  NUMBER(20,6)                                                             Quantidade em unidade no bônus            OPERACIONAL                        NaN
PCBONUSI                QTAVARIAUN  NUMBER(20,6)                                                   Quantidade de avaria em unidade no bônus            OPERACIONAL                        NaN
PCBONUSI                   EANCONF  NUMBER(20,0)                                                                        Código de Barra EAN            OPERACIONAL                        NaN
PCBONUSI                   DUNCONF  NUMBER(20,0)                                                                       Código de barras DUN            OPERACIONAL                        NaN
PCBONUSI                LASTROCONF  NUMBER(10,4)                                                                                     Lastro            OPERACIONAL                        NaN
PCBONUSI                CAMADACONF  NUMBER(10,4)                                                                                     Camada            OPERACIONAL                        NaN
PCBONUSI              QTTOTPALCONF   NUMBER(8,2)                                                                           Total de paletes            OPERACIONAL                        NaN
PCBONUSI           DADOSLOGISTICOS   VARCHAR2(1) Informa se está ou não correto as informações de acordo com os dados logísticos do produto            OPERACIONAL                        NaN
PCBONUSI           NUMVIASETIQUETA   NUMBER(2,0)                                                     Número de vias da emissão de etiquetas            OPERACIONAL                        NaN
PCBONUSI              CODAGREGACAO  VARCHAR2(20)                                                               Chave para rastreio do bonus            OPERACIONAL                        NaN
PCBONUSI                NUMLOTEFAB  VARCHAR2(20)                                                                         Lote do fabricante            OPERACIONAL                        NaN
PCBONUSI             NUMLOTEFORNEC  VARCHAR2(20)                                                                         Lote do fornecedor            OPERACIONAL                        NaN
PCBONUSI               CODDEPOSITO  NUMBER(10,0)                                Código do depósito onde o estoque esta armazenado na filial            OPERACIONAL                        NaN
PCBONUSI            QTAVARIADIGITA  NUMBER(20,6)                                                              Quantidade de Avaria Digitado            OPERACIONAL                        NaN
PCBONUSI            ITEMDESDOBRADO   VARCHAR2(1)                                                 Indica se o item foi desdobrado nova linha            OPERACIONAL                        NaN
PCBONUSI       TIPOEMBALAGEMPEDIDO   VARCHAR2(1)                                                        Tipo de embalagem do pedido(M ou V)            OPERACIONAL                        NaN
PCBONUSI TRANSACAONOTADESDOBRALOTE  NUMBER(10,0)                                                        NÚMERO TRANSAÇÃO DESDOBRAMENTO LOTE            OPERACIONAL                        NaN
PCBONUSI             ID_PCBONUSINF  VARCHAR2(50)                                                           ROWID da PCBONUSI original da NF            OPERACIONAL                        NaN
PCBONUSI                  QTNFORIG  NUMBER(20,6)                                                    Quantidade original da nota de entrada.            OPERACIONAL                        NaN
PCBONUSI                 CODAVARIA   NUMBER(8,0)                                                           Codigo de avaria da pcprodavaria            OPERACIONAL                        NaN
PCBONUSI           CODFORNECAVARIA   NUMBER(6,0)                                                     Código do fonecedor da avaria do bonus            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*