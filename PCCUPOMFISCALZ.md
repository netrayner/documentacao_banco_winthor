# 📊 Tabela: PCCUPOMFISCALZ

### Estrutura de Colunas e Restrições

        Tabela                Coluna  Tipo/Tamanho                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCUPOMFISCALZ             DTEMISSAO          DATE                                                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCUPOMFISCALZ                NUMECF   NUMBER(4,0)                                                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCUPOMFISCALZ              NUMSERIE  VARCHAR2(30)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ                MODELO  VARCHAR2(10)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ        NUMCUPOMINICIO   NUMBER(6,0)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ           NUMCUPOMFIM   NUMBER(6,0)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ           NUMREDUCAOZ   NUMBER(6,0)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ              GTINICIO  NUMBER(16,2)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ               GTFINAL  NUMBER(16,2)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ           NUMREINICIO   NUMBER(3,0)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ             CODFILIAL   VARCHAR2(2)                                                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCUPOMFISCALZ            VLCONTABIL  NUMBER(12,2)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ               NUMMAPA  NUMBER(10,0)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ             EXPORTADO   VARCHAR2(1)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ          DTEXPORTACAO          DATE                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ        NUMCAIXAFISCAL   NUMBER(4,0)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ    IMPORTADOSERVPRINC   VARCHAR2(1)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ DTIMPORTACAOSERVPRINC          DATE                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ   DTEXPORTACAOSERVINT          DATE                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ      EXPORTADOSERVINT   VARCHAR2(1)                                                                        NaN            OPERACIONAL                        NaN
PCCUPOMFISCALZ           SITUACAONFP  VARCHAR2(10)                                                  Indica a situação da NFP.            OPERACIONAL                        NaN
PCCUPOMFISCALZ          PROTOCOLONFP  VARCHAR2(20)                                          Indica o numero do protocolo NFP.            OPERACIONAL                        NaN
PCCUPOMFISCALZ             DTHORANFP          DATE                              Indica a data e hora recebimento arquivo NFP.            OPERACIONAL                        NaN
PCCUPOMFISCALZ            ARQUIVONFP  VARCHAR2(20)                                              Indica o nome do arquivo NFP.            OPERACIONAL                        NaN
PCCUPOMFISCALZ          MODOENVIONFP   VARCHAR2(1) Indica o modo de envio da redução para o SEFAZ - [P]Produção [V]Validação.            OPERACIONAL                        NaN
PCCUPOMFISCALZ                NUMGNF   NUMBER(8,0)                                     Contador geral de operação não fiscal.            OPERACIONAL                        NaN
PCCUPOMFISCALZ                NUMGRG   NUMBER(8,0)                                     Contador geral de relatório gerencial.            OPERACIONAL                        NaN
PCCUPOMFISCALZ                NUMCDC   NUMBER(8,0)                              Contador de comprovante de crédito ou débito.            OPERACIONAL                        NaN
PCCUPOMFISCALZ         DTHORAEMISSAO          DATE                                                    Data e hora da emissão.            OPERACIONAL                        NaN
PCCUPOMFISCALZ           REENVIARNFP   VARCHAR2(1)                                                              Reenviar NFP.            OPERACIONAL                        NaN
PCCUPOMFISCALZ                OBSNFP VARCHAR2(800)                                                                   OBS NFP.            OPERACIONAL                        NaN
PCCUPOMFISCALZ                 VLNFP  NUMBER(18,6)                                                      Indica o valor do NFP            OPERACIONAL                        NaN
PCCUPOMFISCALZ            ASSINATURA VARCHAR2(255)                                                                Código Md-5            OPERACIONAL                        NaN
PCCUPOMFISCALZ                NUMCOO   NUMBER(8,0)                                                              Número do COO            OPERACIONAL                        NaN
PCCUPOMFISCALZ            VENDABRUTA  NUMBER(18,2)                                                                VENDA BRUTA            OPERACIONAL                        NaN
PCCUPOMFISCALZ      DIRETORIOGERACAO VARCHAR2(400)                                        Diretório onde foi gerado o Arquivo            OPERACIONAL                        NaN
PCCUPOMFISCALZ           NOMEARQUIVO  VARCHAR2(20)                                                     Nome do arquivo gerado            OPERACIONAL                        NaN
PCCUPOMFISCALZ                 COORZ  NUMBER(10,0)                                                 NUMERO DE COO DA REDUCAO Z            OPERACIONAL                        NaN
PCCUPOMFISCALZ            ROTINALANC  VARCHAR2(48)                                             ROTINA QUE GRAVOU A INFORMACAO            OPERACIONAL                        NaN
PCCUPOMFISCALZ             CONFERIDO   VARCHAR2(1)                                Informar se a redução Z foi coferida ou não            OPERACIONAL                        NaN
PCCUPOMFISCALZ             DESCISSQN       CHAR(1)                                            Indicador de desconto ISSQN PAF            OPERACIONAL                        NaN
PCCUPOMFISCALZ                MD5PAF VARCHAR2(200)                                          Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN
PCCUPOMFISCALZ           HORAEMISSAO  VARCHAR2(20)                                                  Hora de emissao redução Z            OPERACIONAL                        NaN
PCCUPOMFISCALZ         NUMUSUARIOECF   NUMBER(4,0)                                          Numero de ordem do usuario do ecf            OPERACIONAL                        NaN
PCCUPOMFISCALZ              NUMCAIXA   NUMBER(4,0)                                                            Número do caixa            OPERACIONAL                        NaN
PCCUPOMFISCALZ   NUMEROORDEMOPERACAO   NUMBER(8,0)                                        Número contador de operações da ecf            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*