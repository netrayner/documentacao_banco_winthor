# 📊 Tabela: PCBAIXACARTAOC

### Estrutura de Colunas e Restrições

        Tabela            Coluna   Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBAIXACARTAOC    CODBAIXACARTAO   NUMBER(10,0)                             Código da baixa    CHAVE PRIMÁRIA (PK)                        NaN
PCBAIXACARTAOC         CODFILIAL    VARCHAR2(2)                            Código da filial            OPERACIONAL                        NaN
PCBAIXACARTAOC          CODBANCO    NUMBER(4,0)                             Código do banco            OPERACIONAL                        NaN
PCBAIXACARTAOC          CODMOEDA    VARCHAR2(4)                             Código da moeda            OPERACIONAL                        NaN
PCBAIXACARTAOC        NOMELAYOUT  VARCHAR2(100)                           Nome Layout baixa            OPERACIONAL                        NaN
PCBAIXACARTAOC    DATAIMPORTACAO           DATE               Data da importação do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC    HORAIMPORTACAO   VARCHAR2(10)               Hora da importação do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC CODUSURIMPORTACAO    NUMBER(8,0) Código do usuário que realizou a importação            OPERACIONAL                        NaN
PCBAIXACARTAOC         DATABAIXA           DATE                    Data da baixa do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC         HORABAIXA   VARCHAR2(10)                    Hora da baixa do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC      CODUSURBAIXA    NUMBER(8,0)      Código do usuário que realizou a baixa            OPERACIONAL                        NaN
PCBAIXACARTAOC          NUMTRANS   NUMBER(10,0)              Número da transação na pcprest            OPERACIONAL                        NaN
PCBAIXACARTAOC     NOMEDOARQUIVO  VARCHAR2(100)                             Nome do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC      BANCOARQUIVO    VARCHAR2(1)    Flag para identificar o banco do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC      TIPOREGISTRO    VARCHAR2(5)                 Tipo de Registro do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC         DTCRIACAO   VARCHAR2(10)                     Data.Criação do Arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC         HRCRIACAO   VARCHAR2(10)                  Hora de Criação do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC          DTINICIO   VARCHAR2(10)                         Data Fim do Arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC             DTFIM   VARCHAR2(10)                         Data Fim do Arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC      VERSAOLAYOUT   VARCHAR2(10)                            Versão do Layout            OPERACIONAL                        NaN
PCBAIXACARTAOC         CODIDREDE    VARCHAR2(5)                   Cód.Identificação da rede            OPERACIONAL                        NaN
PCBAIXACARTAOC     NUMSEQARQUIVO   VARCHAR2(16)      Número sequencial de linhas do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC  NUMSEQREGARQUIVO    VARCHAR2(5)     Número sequencial da geração do arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC         CODLAYOUT    NUMBER(8,0)                            Códígo do Layout            OPERACIONAL                        NaN
PCBAIXACARTAOC       ESTABMATRIZ   NUMBER(10,0)            Código do Estabelacimento matriz            OPERACIONAL                        NaN
PCBAIXACARTAOC EMPRESAADQUIRENTE    VARCHAR2(5)                          Empresa adquirente            OPERACIONAL                        NaN
PCBAIXACARTAOC          USOCIELO  VARCHAR2(177)                             De uso da cielo            OPERACIONAL                        NaN
PCBAIXACARTAOC       CAIXAPOSTAL   VARCHAR2(20)                                Caixa Postal            OPERACIONAL                        NaN
PCBAIXACARTAOC               VAN    VARCHAR2(1)                                         VAN            OPERACIONAL                        NaN
PCBAIXACARTAOC      OPCAOEXTRATO    VARCHAR2(2) Opção de extrato do arquivo Tipo de Arquivo            OPERACIONAL                        NaN
PCBAIXACARTAOC             LIVRE VARCHAR2(1000)                                 Texto livre            OPERACIONAL                        NaN
PCBAIXACARTAOC     TIPOMOVIMENTO   VARCHAR2(50)                 TIPO DE MOVIMENTO OPERADORA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*