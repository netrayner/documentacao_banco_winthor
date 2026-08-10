# 📊 Tabela: PCORCAVENDAISNGPC

### Estrutura de Colunas e Restrições

           Tabela        Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORCAVENDAISNGPC       NUMORCA  NUMBER(10,0)                              NÚMERO ORÇAMENTO.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAISNGPC       CODPROD   NUMBER(6,0)                                CÓDIGO PRODUTO.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAISNGPC        NUMSEQ  NUMBER(20,0)                              NÚMERO SEQUENCIA.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAISNGPC   NUMNOTIFMED  VARCHAR2(10)          NÚMERO DA NOTIFICAÇÃO DE MEDICAMENTO.    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAISNGPC  DTPRESCRICAO          DATE                            DATA DA PRESCRIÇÃO.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC TIPOTRANSACAO   VARCHAR2(1)                       TIPO DA TRANSAÇÃO SNGPC.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC NUMTRANSVENDA  NUMBER(10,0)                 RELACIONAMENTO COM A PCNFSAID. CHAVE ESTRANGEIRA (FK)                   PCNFSAID
PCORCAVENDAISNGPC  TIPOCONSPROF   VARCHAR2(6)           CONSELHO PROFISSIONAL DO PRESCRITOR.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC    NUMREGPROF  VARCHAR2(30) NÚMERO DO REGISTRO PROFISSIONAL DO PRESCRITOR.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC     NOMECOMPR VARCHAR2(100)                                NOME COMPRADOR.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC  CODTIPODOCUM   NUMBER(2,0)         CÓDIGO TIPO DE DOCUMENTO DO COMPRADOR.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC  TIPOORGAOEXP   VARCHAR2(8)     ORGÃO EXPEDIDOR DO DOCUMENTO DO COMPRADOR.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC      NUMDOCUM  VARCHAR2(30)              NÚMERO DO DOCUMENTO DO COMPRADOR.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC       UFDOCUM   VARCHAR2(2)             UF EMISSÃO DO DOCUMENTO COMPRADOR.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC      CPFCOMPR  VARCHAR2(14)                              CPF DO COMPRADOR.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC       UNIDADE   VARCHAR2(2)                  RELACIONAMENTO COM PCUNIDADE. CHAVE ESTRANGEIRA (FK)                  PCUNIDADE
PCORCAVENDAISNGPC   QTPOSOLOGIA  NUMBER(18,6)        QUANTIDADE POSOLOGIA NA RECEITA MÉDICA.            OPERACIONAL                        NaN
PCORCAVENDAISNGPC       QTHORAS  NUMBER(18,6)     QUANTIDADE DE HORAS A REPETIR A POSOLOGIA.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*