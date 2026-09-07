# 📊 Tabela: PCGRUPOAVARIA

### Estrutura de Colunas e Restrições

       Tabela          Coluna Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGRUPOAVARIA        CODGRUPO  NUMBER(6,0)                                                  Cód. Grupo avaria.            OPERACIONAL                        NaN
PCGRUPOAVARIA          NUMPED NUMBER(10,0)                                                    Numero do pedido            OPERACIONAL                        NaN
PCGRUPOAVARIA         NUMLOTE VARCHAR2(40)                                                      Numero do lote            OPERACIONAL                        NaN
PCGRUPOAVARIA              QT NUMBER(20,6)                                                        Qt. Avariado            OPERACIONAL                        NaN
PCGRUPOAVARIA        NUMVERBA  NUMBER(6,0)                                                     Numero da verba            OPERACIONAL                        NaN
PCGRUPOAVARIA         CODPROD  NUMBER(6,0)                                                     Cód. Do produto            OPERACIONAL                        NaN
PCGRUPOAVARIA       CODFILIAL  VARCHAR2(2)                                                         Cód. Filial            OPERACIONAL                        NaN
PCGRUPOAVARIA    VALORDOGRUPO NUMBER(16,3)                                                      Valor do grupo            OPERACIONAL                        NaN
PCGRUPOAVARIA       CODFORNEC  NUMBER(6,0)                                                  Cód. Do fornecedor            OPERACIONAL                        NaN
PCGRUPOAVARIA   CODTIPOAVARIA  NUMBER(2,0)                                             Cód. Do tipo de avaria.            OPERACIONAL                        NaN
PCGRUPOAVARIA      TIPOAVARIA VARCHAR2(40)                                                    Des. Tipo avaria            OPERACIONAL                        NaN
PCGRUPOAVARIA          STATUS  VARCHAR2(1)                                                     Status do grupo            OPERACIONAL                        NaN
PCGRUPOAVARIA         EMITENF  VARCHAR2(1)                                   Valida se o grupo emite ou não nf            OPERACIONAL                        NaN
PCGRUPOAVARIA       DATAGRUPO         DATE                                            Data de geração do Grupo            OPERACIONAL                        NaN
PCGRUPOAVARIA  DATABAIXAGRUPO         DATE                                              Data de baixa do Grupo            OPERACIONAL                        NaN
PCGRUPOAVARIA    CODPRODTROCA  NUMBER(6,0)                                                  Produto para troca            OPERACIONAL                        NaN
PCGRUPOAVARIA       NUMSEQPED  NUMBER(6,0)                                                 Sequencia do pedido            OPERACIONAL                        NaN
PCGRUPOAVARIA      QTORIGINAL NUMBER(20,6)                                             Qtde. original do grupo            OPERACIONAL                        NaN
PCGRUPOAVARIA         VLVERBA NUMBER(16,3)                                                Vlr. Verba associada            OPERACIONAL                        NaN
PCGRUPOAVARIA   CODUSUARIOGER  NUMBER(8,0)                                 Código do usuario gerador do grupo.            OPERACIONAL                        NaN
PCGRUPOAVARIA CODMOTIVOAVARIA  NUMBER(4,0) Código de motivo o qual os produtos do grupo estão sendo avariados.            OPERACIONAL                        NaN
PCGRUPOAVARIA       CODAVARIA  NUMBER(8,0)                                         Código da entrada de avaria            OPERACIONAL                        NaN
PCGRUPOAVARIA     NUMTRANSENT NUMBER(20,0)                      Número de transação da Nota Fiscal de Entrada.            OPERACIONAL                        NaN
PCGRUPOAVARIA     CODDEPOSITO NUMBER(10,0)                                                  Código do Depósito            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*