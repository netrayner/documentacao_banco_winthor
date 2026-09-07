# 📊 Tabela: PCREGRAINTEGRACAOCTB

### Estrutura de Colunas e Restrições

              Tabela          Coluna   Tipo/Tamanho                                                                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREGRAINTEGRACAOCTB        CODREGRA   NUMBER(38,0)                                                                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCREGRAINTEGRACAOCTB    TIPOOPERACAO        CHAR(2)                                                                                                                                               NaN            OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB       DESCRICAO  VARCHAR2(200)                                                                                                                                               NaN            OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB   CODPLANOCONTA    NUMBER(5,0)                                                                                                                                               NaN            OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB  CODREDUZIDO_DB   VARCHAR2(12)                                                                                                                                               NaN            OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB  CODREDUZIDO_CR   VARCHAR2(12)                                                                                                                                               NaN            OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB    CODHISTORICO    NUMBER(3,0)                                                                                                                                               NaN            OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB HISTORICO_COMPL  VARCHAR2(200)                                                                                                                                               NaN            OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB       SCRIPTSQL VARCHAR2(4000)                                                                                                                                               NaN            OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB  TIPOINTEGRACAO    VARCHAR2(2)                                                                                         Identifica o tipo da integração: Analítica ou Sintética.             OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB       CODFILIAL    VARCHAR2(2)                                                                                                                       Indica o código da filial.             OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB      REGRAATIVA    VARCHAR2(1)                                                                                                                 Regra está ativa para integração.            OPERACIONAL                        NaN
PCREGRAINTEGRACAOCTB DESTINORATEIOCC    VARCHAR2(1) Integração e destino do rateio do centro de custo. 'D'=Integrar na conta débito; 'C'=Integrar na conta débito; 'N'=Não integrar o centro de custo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*