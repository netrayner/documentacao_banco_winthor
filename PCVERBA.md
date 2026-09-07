# 📊 Tabela: PCVERBA

### Estrutura de Colunas e Restrições

 Tabela                   Coluna   Tipo/Tamanho                                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVERBA                 NUMVERBA    NUMBER(6,0)                                                                                             NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCVERBA                CODFILIAL    VARCHAR2(2)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                CODFORNEC    NUMBER(6,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                DTEMISSAO           DATE                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                     TIPO    VARCHAR2(1)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                FORMAPGTO    VARCHAR2(1)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                  CODEPTO    NUMBER(6,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA               REFERENCIA   VARCHAR2(80)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA              REFERENCIA1   VARCHAR2(80)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                    VALOR   NUMBER(10,2)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                   DTVENC           DATE                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA             TIPOQUITACAO   VARCHAR2(10)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA               DTQUITACAO           DATE                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                  NUMNOTA   NUMBER(10,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                 CODBANCO    NUMBER(4,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                 DINHEIRO    NUMBER(8,2)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                   OUTROS   VARCHAR2(10)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                   NUMPED   NUMBER(10,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                 CODCONTA   NUMBER(10,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                   ORIGEM    VARCHAR2(1)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA             SUPERVFORNEC   VARCHAR2(40)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                REPFORNEC   VARCHAR2(40)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA              RGREPFORNEC   VARCHAR2(30)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA             CPFREPFORNEC   VARCHAR2(30)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                   CODSEC    NUMBER(6,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA               DATAEDICAO           DATE                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA                    VPAGO   NUMBER(10,2)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA          CODFUNCQUITACAO    NUMBER(8,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA         PROGRAMAQUITACAO    NUMBER(5,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA               DTULTPAGTO           DATE                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA     NUMTRANSENTDEVFORNEC   NUMBER(10,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA              NUMTRANSENT   NUMBER(10,0)                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA               DTAPURACAO           DATE                                                 Indica a data de apuração da verba rebaixa CMV.            OPERACIONAL                        NaN
PCVERBA                 DTCANCEL           DATE                                                      Indica a data de de cancelamento da verba.            OPERACIONAL                        NaN
PCVERBA             CODTIPOVERBA   NUMBER(10,0)                                                               Indica o código do tipo da verba.            OPERACIONAL                        NaN
PCVERBA               ROTINALANC    NUMBER(6,0)                                               Indica o número da rotina que alterou o registro.            OPERACIONAL                        NaN
PCVERBA            CODFUNCCANCEL    NUMBER(8,0)                         Indica a matrícula do funcionário que realizou o cancelamento de verba.            OPERACIONAL                        NaN
PCVERBA               DTCADASTRO           DATE                                                                     Indica a data de casdastro.            OPERACIONAL                        NaN
PCVERBA                  NUMVIAS    NUMBER(2,0)                               Número de vezes que foi emitida a autorização aplicação de verba.            OPERACIONAL                        NaN
PCVERBA           CODGRUPOAVARIA    NUMBER(8,0)                                         Codigo do grupo de avaria a qual a verba esta vinculada            OPERACIONAL                        NaN
PCVERBA              ORIGEMVERBA   NUMBER(22,0) Campo utilizado para identificar a verba de origem quando ocorrer a transferencia entre filiais            OPERACIONAL                        NaN
PCVERBA   HISTORICOTRANSFERENCIA VARCHAR2(4000)         Campo utilizado para registrar os históricos das transferências de verbas entre filiais            OPERACIONAL                        NaN
PCVERBA      MOTIVOTRANSFERENCIA VARCHAR2(4000)                 Campo utilizado para registrar o motivo da transferência da verba entre filiais            OPERACIONAL                        NaN
PCVERBA        DATATRANSFERENCIA           DATE                   Campo utilizado para registrar a data da transferência da verba entre filiais            OPERACIONAL                        NaN
PCVERBA  UTILIZAVERBAMULTIFILIAL    VARCHAR2(1)                                                           Indica se a verba utiliza multifilial            OPERACIONAL                        NaN
PCVERBA             CODCOMPRADOR    NUMBER(8,0)                                                         Campo para gravar o codigo do comprador            OPERACIONAL                        NaN
PCVERBA CODCONTAFUNDOMULTIFILIAL   NUMBER(10,0)                                        Campo para gravar o codigo da conta do fundo multifilial            OPERACIONAL                        NaN
PCVERBA ALIMENTAFUNDOMULTIFILIAL    VARCHAR2(1)                                       Campo para gravar o histórico do parâmetro da rotina 202.            OPERACIONAL                        NaN
PCVERBA        VERBAREBCMVAPURAR    VARCHAR2(1)                                    Campo para gravar se a verba é para rebaixa de cmv a apurar.            OPERACIONAL                        NaN
PCVERBA       APLICVERBAREBCUSTO    VARCHAR2(1)                                       Campo para gravar o histórico do parâmetro da rotina 202.            OPERACIONAL                        NaN
PCVERBA       ASSINATURACONTRATO    VARCHAR2(1)                                   Campo aonde grava se o contrato de verba esta assinado ou não            OPERACIONAL                        NaN
PCVERBA        CODUSURASSINATURA    NUMBER(8,0)                                                        Matricula do usuário que assinou a verba            OPERACIONAL                        NaN
PCVERBA          DTATUASSINATURA           DATE                                                                     Data da assinatura da verba            OPERACIONAL                        NaN
PCVERBA     CODUSURDESASSINATURA    NUMBER(8,0)                                                     Matricula do usuário que desassinou a verba            OPERACIONAL                        NaN
PCVERBA                 CONTRATO           BLOB                                                                                             NaN            OPERACIONAL                        NaN
PCVERBA           CODFUNCCRIACAO    NUMBER(8,0)                                                        Código do funcionário que criou a verba.            OPERACIONAL                        NaN
PCVERBA           IDDOCUMENTOTAE    NUMBER(8,0)                                                       Identificador do documento enviado no TAE            OPERACIONAL                        NaN
PCVERBA         NOMEDOCUMENTOTAE   VARCHAR2(50)                                                         Nome do documento no repositório do TAE            OPERACIONAL                        NaN
PCVERBA     SITUACAODOCUMENTOTAE   VARCHAR2(30)                                                     Situação do documento no repositório do TAE            OPERACIONAL                        NaN
PCVERBA       DTSINCRONIZACAOTAE           DATE            Data da última sincronização realizado no TAE para atualizar a situação do documento            OPERACIONAL                        NaN
PCVERBA  CODSITUACAODOCUMENTOTAE    NUMBER(2,0)                                           Código da situação do documento no repositório do TAE            OPERACIONAL                        NaN
PCVERBA                 CODMARCA    NUMBER(8,0)                                                Código da marca dos produtos associados a verba.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*