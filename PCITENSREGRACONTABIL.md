# 📊 Tabela: PCITENSREGRACONTABIL

### Estrutura de Colunas e Restrições

              Tabela                   Coluna  Tipo/Tamanho                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITENSREGRACONTABIL                 CODREGRA  NUMBER(10,0)                                                                Indica o código controle.    CHAVE PRIMÁRIA (PK)                        NaN
PCITENSREGRACONTABIL           CODREDUZIDO_PC  VARCHAR2(40)                                              Indica o código reduzido da conta contábil.    CHAVE PRIMÁRIA (PK)                        NaN
PCITENSREGRACONTABIL                 FORMULAS VARCHAR2(500)                                                    Indica o fórmula para contabilização.            OPERACIONAL                        NaN
PCITENSREGRACONTABIL                 NATUREZA   VARCHAR2(1)                                                     Indica o natureza da contabilizacao.    CHAVE PRIMÁRIA (PK)                        NaN
PCITENSREGRACONTABIL            TOTALIZAVALOR   VARCHAR2(1)                                                       Indica se o valor será totalizado.            OPERACIONAL                        NaN
PCITENSREGRACONTABIL             CODHISTORICO   NUMBER(4,0)                                                            Indica o código do histórico.            OPERACIONAL                        NaN
PCITENSREGRACONTABIL           HISTCOMPLREGRA VARCHAR2(200)                                                         Indica o histórico complementar.            OPERACIONAL                        NaN
PCITENSREGRACONTABIL          CODFILIALLANCTO  VARCHAR2(20) Define qual será a filial à qual será atribuida o lançamento contábil na contabilização.            OPERACIONAL                        NaN
PCITENSREGRACONTABIL                DOCUMENTO  VARCHAR2(40)                                    Indica o documento referente à movimentação contábil.            OPERACIONAL                        NaN
PCITENSREGRACONTABIL CONTABILIZACENTRORECEITA   VARCHAR2(1)                                    Informar se a partida contabilizará centro de receita            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*