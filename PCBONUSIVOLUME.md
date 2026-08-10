# 📊 Tabela: PCBONUSIVOLUME

### Estrutura de Colunas e Restrições

        Tabela                       Coluna  Tipo/Tamanho                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBONUSIVOLUME                    CODIGOUMA  NUMBER(14,0)                                                     Informa a UMA que pertence o volume.            OPERACIONAL                        NaN
PCBONUSIVOLUME                     NUMBONUS   NUMBER(8,0)                                              Informa o numero da conferência de entrada.            OPERACIONAL                        NaN
PCBONUSIVOLUME                      CODPROD   NUMBER(8,0)                                                        Código do produto ref a PCPRODUT.            OPERACIONAL                        NaN
PCBONUSIVOLUME                      NUMLOTE  VARCHAR2(15)                                                Numero de lote informado pelo conferente.            OPERACIONAL                        NaN
PCBONUSIVOLUME                   DTVALIDADE          DATE                                                 Informe a data de vencimento do produto.            OPERACIONAL                        NaN
PCBONUSIVOLUME                         TIPO       CHAR(1)                        Quando o valor for "N" o produto será NORMAL, "A" igual a avaria.            OPERACIONAL                        NaN
PCBONUSIVOLUME                      QTPECAS   NUMBER(4,0)                                       Informa a Quantidade de Peças Existentes no Volume            OPERACIONAL                        NaN
PCBONUSIVOLUME                    QTENTRADA  NUMBER(18,6)              Informado na conferência, referente ao total do produto presente no volume.            OPERACIONAL                        NaN
PCBONUSIVOLUME                         QTNF  NUMBER(18,6)                     Informa a quantidade do produto referente na nota fiscal de entrada.            OPERACIONAL                        NaN
PCBONUSIVOLUME                   ENDERECADO       CHAR(1) Quando S informa que o volume foi endereçado, N informa que endereçamento esta pendente.            OPERACIONAL                        NaN
PCBONUSIVOLUME                    CODMOTIVO   NUMBER(6,0)                        O codigo do motivo da avaria referente a tabela PCTABDEV.CODDEVOL            OPERACIONAL                        NaN
PCBONUSIVOLUME                 DTLANCAMENTO          DATE                                                              Data do Lancamento do Bônus            OPERACIONAL                        NaN
PCBONUSIVOLUME                      NUMVIAS   NUMBER(6,0)                                                                  Número da Vias do Bônus            OPERACIONAL                        NaN
PCBONUSIVOLUME                 DTFECHAMENTO          DATE                                                                       Data do Fechamento            OPERACIONAL                        NaN
PCBONUSIVOLUME             CODFILIALESTOQUE   VARCHAR2(3)                                                                    Código Filial Estoque            OPERACIONAL                        NaN
PCBONUSIVOLUME              CODFILIALGESTAO   VARCHAR2(3)                                                                     Código Filial Gestão            OPERACIONAL                        NaN
PCBONUSIVOLUME                        NUMOS  NUMBER(10,0)                                                                                Número OS            OPERACIONAL                        NaN
PCBONUSIVOLUME                  CODENDERECO   NUMBER(8,0)                                                            Código do endereço de destino            OPERACIONAL                        NaN
PCBONUSIVOLUME            CODFUNCCONFERENTE   NUMBER(8,0)                                                            Código do conferênte do bônus            OPERACIONAL                        NaN
PCBONUSIVOLUME          DESCRICAOOCORRENCIA  VARCHAR2(60)                                                                  Descrição da ocorrência            OPERACIONAL                        NaN
PCBONUSIVOLUME         OCORRENCIAAUTORIZADA       CHAR(1)                                                                    Ocorrência autorizada            OPERACIONAL                        NaN
PCBONUSIVOLUME MOTIVODAUTORIZACAOOCORRENCIA VARCHAR2(100)                                                      Motivo da autorização de ocorrência            OPERACIONAL                        NaN
PCBONUSIVOLUME                 CODAGREGACAO  VARCHAR2(20)                                                                     Código de agregação.            OPERACIONAL                        NaN
PCBONUSIVOLUME      CODFUNCAUTORIOCORRENCIA   NUMBER(8,0)                                         Codigo do funcionario que autorizou a ocorrencia            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*