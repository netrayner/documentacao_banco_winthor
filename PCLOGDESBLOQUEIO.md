# 📊 Tabela: PCLOGDESBLOQUEIO

### Estrutura de Colunas e Restrições

          Tabela             Coluna  Tipo/Tamanho                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDESBLOQUEIO      DTDESBLOQUEIO          DATE                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO            NUMLOTE  VARCHAR2(15)                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO CODFUNCDESBLOQUEIO   NUMBER(8,0)                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO            CODPROD   NUMBER(6,0)                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO     QTDESBLOQUEADA  NUMBER(20,6)                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO     QTBLOQUEADAANT  NUMBER(20,6)                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO                OBS  VARCHAR2(80)                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO          HISTORICO VARCHAR2(100)                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO      ESTDISPZERADO   VARCHAR2(1)                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO          CODFILIAL   VARCHAR2(2)                                                                                   NaN            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO            NUMLANC   NUMBER(8,0) Contém o número do lançamento de liberação através das rotinas PCFAR1613 / PCINF1667.            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO     NUMCERTIFICADO  VARCHAR2(15)                                                               Número do Certificado.             OPERACIONAL                        NaN
PCLOGDESBLOQUEIO         OBSANALISE   VARCHAR2(2)                                                               Observação da Análise.             OPERACIONAL                        NaN
PCLOGDESBLOQUEIO           PROGRAMA  VARCHAR2(50)                                                                    Nome do programa.             OPERACIONAL                        NaN
PCLOGDESBLOQUEIO           CODDEVOL   NUMBER(4,0)                                                   Contém o código motivo desbloqueio.            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO        QTBLOQUEADA  NUMBER(20,6)      Indica a quantidade de produto que foi bloqueado a partir do estoque disponível.            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO  QTDESBLOQUEADAANT  NUMBER(20,6)                                          Indica a quantidade Bloqueada anteriormente.            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO          QTINDENIZ  NUMBER(20,6)                          Indica a quantidade de produto que foi colocado como avaria.            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO       QTINDENIZANT  NUMBER(20,6)            Indica a quantidade de produto que foi colocado como avaria anteriormente.            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO        NUMTRANSWMS  NUMBER(10,0)                                                    Numero de transação gerada no WMS.            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO        NUMTRANSENT  NUMBER(10,0)                                                   Numero de transação de desbloqueio.            OPERACIONAL                        NaN
PCLOGDESBLOQUEIO           NUMBONUS  NUMBER(10,0)                                                                       Número do bônus            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*