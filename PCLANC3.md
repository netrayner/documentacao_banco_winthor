# 📊 Tabela: PCLANC3

### Estrutura de Colunas e Restrições

 Tabela                  Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLANC3                  NUMPED NUMBER(10,0)                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLANC3                   PREST  VARCHAR2(3)                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLANC3                DTPEDIDO         DATE                                               NaN            OPERACIONAL                        NaN
PCLANC3               CODFORNEC  NUMBER(6,0)                                               NaN            OPERACIONAL                        NaN
PCLANC3               HISTORICO VARCHAR2(40)                                               NaN            OPERACIONAL                        NaN
PCLANC3              HISTORICO2 VARCHAR2(40)                                               NaN            OPERACIONAL                        NaN
PCLANC3                  DTVENC         DATE                                               NaN            OPERACIONAL                        NaN
PCLANC3               CODFILIAL  VARCHAR2(2)                                               NaN            OPERACIONAL                        NaN
PCLANC3                  INDICE  VARCHAR2(1)                                               NaN            OPERACIONAL                        NaN
PCLANC3                   VALOR NUMBER(14,2)                                               NaN            OPERACIONAL                        NaN
PCLANC3                   MOEDA  VARCHAR2(1)                                               NaN            OPERACIONAL                        NaN
PCLANC3                   PRAZO  NUMBER(6,0)                                                 .            OPERACIONAL                        NaN
PCLANC3              ROTINALANC  NUMBER(6,0) Indica o número da rotina que alterou o registro.            OPERACIONAL                        NaN
PCLANC3               VLDESPFIN NUMBER(18,6)           Valor da despesa financeira da parcela.            OPERACIONAL                        NaN
PCLANC3                  RECNUM  NUMBER(8,0)                Número do título de contas a pagar            OPERACIONAL                        NaN
PCLANC3               FORMAPGTO  VARCHAR2(2)        Forma de pagamento do controle de embarque            OPERACIONAL                        NaN
PCLANC3                    TIPO  NUMBER(3,0)          Define o tipo de Contas a Pagar previsto            OPERACIONAL                        NaN
PCLANC3                CODCONTA NUMBER(10,0)                                   Código da conta            OPERACIONAL                        NaN
PCLANC3                   CONTA VARCHAR2(40)                                             Conta            OPERACIONAL                        NaN
PCLANC3           DTCOMPETENCIA         DATE                               Data da competência            OPERACIONAL                        NaN
PCLANC3 RATEIOCENTROCUSTOMANUAL  VARCHAR2(1)                  Rateio manual de centro de custo            OPERACIONAL                        NaN
PCLANC3             CODCOBSEFAZ  VARCHAR2(4)                       Código de cobrança da Sefaz            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*