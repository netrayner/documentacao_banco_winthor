# 📊 Tabela: PCSNGPCTRANSCAB

### Estrutura de Colunas e Restrições

         Tabela         Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSNGPCTRANSCAB       NUMTRANS  NUMBER(12,0)                           Número da Transação    CHAVE PRIMÁRIA (PK)                        NaN
PCSNGPCTRANSCAB      CODFILIAL   VARCHAR2(2)                              Código da Filial            OPERACIONAL                        NaN
PCSNGPCTRANSCAB          DTMOV          DATE                             Data do Movimento            OPERACIONAL                        NaN
PCSNGPCTRANSCAB      TIPOTRANS   VARCHAR2(1)                             Tipo de Transação            OPERACIONAL                        NaN
PCSNGPCTRANSCAB  CODTIPORECEIT   NUMBER(1,0)                 Código do Tipo de Receituário            OPERACIONAL                        NaN
PCSNGPCTRANSCAB    NUMNOTIFMED  VARCHAR2(10)          Número da Notificação de Medicamento            OPERACIONAL                        NaN
PCSNGPCTRANSCAB   DTPRESCRICAO          DATE                            Data da Prescrição            OPERACIONAL                        NaN
PCSNGPCTRANSCAB   NOMEPRESCRIT VARCHAR2(100)                               Nome Prescritor            OPERACIONAL                        NaN
PCSNGPCTRANSCAB   TIPOCONSPROF   VARCHAR2(6)           Conselho Profissional do Prescritor            OPERACIONAL                        NaN
PCSNGPCTRANSCAB     NUMREGPROF  VARCHAR2(30) Número do Registro Profissional do Prescritor            OPERACIONAL                        NaN
PCSNGPCTRANSCAB     UFCONSPROF   VARCHAR2(2)           UF Conselho Profissional Prescritor            OPERACIONAL                        NaN
PCSNGPCTRANSCAB  CODTIPOUSOMED   NUMBER(1,0)                Código Tipo de Uso Medicamento            OPERACIONAL                        NaN
PCSNGPCTRANSCAB      NOMECOMPR VARCHAR2(100)                                Nome Comprador            OPERACIONAL                        NaN
PCSNGPCTRANSCAB   CODTIPODOCUM   NUMBER(2,0)      Código do Tipo de Documento do Comprador            OPERACIONAL                        NaN
PCSNGPCTRANSCAB   TIPOORGAOEXP   VARCHAR2(8)     Orgão Expedidor do Documento do Comprador            OPERACIONAL                        NaN
PCSNGPCTRANSCAB       NUMDOCUM  VARCHAR2(30)              Número do Documento do Comprador            OPERACIONAL                        NaN
PCSNGPCTRANSCAB        UFDOCUM   VARCHAR2(2)          UF Emissão do Documento do Comprador            OPERACIONAL                        NaN
PCSNGPCTRANSCAB      MATRICULA   NUMBER(8,0)                          Matricula do usuário            OPERACIONAL                        NaN
PCSNGPCTRANSCAB       DTULTALT          DATE                      Data da Última Alteração            OPERACIONAL                        NaN
PCSNGPCTRANSCAB  CODTIPOPERFIS   NUMBER(2,0)             Código do Tipo de Operação Fiscal            OPERACIONAL                        NaN
PCSNGPCTRANSCAB        NUMNOTA   NUMBER(9,0)                         Número da Nota Fiscal            OPERACIONAL                        NaN
PCSNGPCTRANSCAB        DTEMISS          DATE                Data de Emissão da Nota Fiscal            OPERACIONAL                        NaN
PCSNGPCTRANSCAB          SERIE   VARCHAR2(3)                                         Série            OPERACIONAL                        NaN
PCSNGPCTRANSCAB    CODEMITENTE   NUMBER(6,0)                            Código do Emitente            OPERACIONAL                        NaN
PCSNGPCTRANSCAB CODTIPMOTPERDA   NUMBER(2,0)             Código do Tipo de Motivo de Perda            OPERACIONAL                        NaN
PCSNGPCTRANSCAB         SEQEXP  NUMBER(10,0)                       Sequência de Exportação            OPERACIONAL                        NaN
PCSNGPCTRANSCAB       CPFCOMPR  VARCHAR2(14)                              CPF do Comprador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*