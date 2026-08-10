# 📊 Tabela: PCCORREN

### Estrutura de Colunas e Restrições

  Tabela                      Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCORREN                      RECNUM  NUMBER(8,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                   CODFILIAL  VARCHAR2(2)                                         NaN            OPERACIONAL                        NaN
PCCORREN                      DTLANC         DATE                                         NaN            OPERACIONAL                        NaN
PCCORREN                     CODFUNC  NUMBER(8,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                   HISTORICO VARCHAR2(40)                                         NaN            OPERACIONAL                        NaN
PCCORREN                    TIPOLANC  VARCHAR2(1)                                         NaN            OPERACIONAL                        NaN
PCCORREN                       VALOR NUMBER(14,2)                                         NaN            OPERACIONAL                        NaN
PCCORREN                      NUMDOC NUMBER(12,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                     CODHIST  NUMBER(4,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                  HISTORICO2 VARCHAR2(40)                                         NaN            OPERACIONAL                        NaN
PCCORREN                      DTVENC         DATE                                         NaN            OPERACIONAL                        NaN
PCCORREN                     NUMVALE NUMBER(12,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                    TIPOFUNC  VARCHAR2(1)                                         NaN            OPERACIONAL                        NaN
PCCORREN                    CODEMITE  NUMBER(8,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                    DTTRANSF         DATE                                         NaN            OPERACIONAL                        NaN
PCCORREN                 CODFUNCORIG  NUMBER(8,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                CODEMITEORIG  NUMBER(8,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                    COBJUROS  VARCHAR2(1)                                         NaN            OPERACIONAL                        NaN
PCCORREN                    CODBANCO  NUMBER(4,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                    NUMTRANS NUMBER(10,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                        HORA  NUMBER(2,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                      MINUTO  NUMBER(2,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                  DTVENCORIG         DATE                                         NaN            OPERACIONAL                        NaN
PCCORREN              CODFUNCPRORROG  NUMBER(8,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                      INDICE  VARCHAR2(1)                                         NaN            OPERACIONAL                        NaN
PCCORREN           NUMTRANSENTDEVCLI NUMBER(10,0)                                         NaN            OPERACIONAL                        NaN
PCCORREN                       DTDOC         DATE                                         NaN            OPERACIONAL                        NaN
PCCORREN                   CODROTINA  NUMBER(6,0)          Indica a rotina geradora do Vale.             OPERACIONAL                        NaN
PCCORREN                 DTBAIXAVALE         DATE                       Data de baixa do vale            OPERACIONAL                        NaN
PCCORREN                 CODFUNBAIXA NUMBER(10,0)  Código do funcionário que realizou a baixa            OPERACIONAL                        NaN
PCCORREN               NUMTRANSBAIXA NUMBER(10,0)               Número de transação de baixa.            OPERACIONAL                        NaN
PCCORREN CONSIDERABASECALCULOIMPOSTO  VARCHAR2(1) Considerar na Base de Cálculo dos Impostos.            OPERACIONAL                        NaN
PCCORREN            ORIGEMLANCAMENTO  VARCHAR2(2)               Origem do lançamento do vale.            OPERACIONAL                        NaN
PCCORREN               VALEEXPORTADO  VARCHAR2(1)      Vale exportado para folha de pagamento            OPERACIONAL                        NaN
PCCORREN                CODIGOCOMRCA NUMBER(14,0)      Campo de ligação com a tabela PCCOMRCA            OPERACIONAL                        NaN
PCCORREN               CODIGOCOMFUNC NUMBER(14,0)           Número da comissao do funcionario            OPERACIONAL                        NaN
PCCORREN               DTPAGCOMISSAO         DATE               Fechamento de comissão do RCA            OPERACIONAL                        NaN
PCCORREN             DTPAGCOMISSAOOP         DATE          Fechamento de comissão do Operador            OPERACIONAL                        NaN
PCCORREN                  DTMXSALTER         DATE                                         NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*