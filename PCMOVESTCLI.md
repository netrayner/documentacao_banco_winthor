# 📊 Tabela: PCMOVESTCLI

### Estrutura de Colunas e Restrições

     Tabela                 Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVESTCLI                CODPROD  NUMBER(6,0)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI                 CODCLI  NUMBER(6,0)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI                  DTMOV         DATE                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI                CODOPER  VARCHAR2(1)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI                     QT NUMBER(18,6)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI                NUMNOTA NUMBER(10,0)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI            NUMTRANSENT NUMBER(10,0)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI          NUMTRANSVENDA NUMBER(10,0)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI               DTMOVLOG         DATE                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI               CUSTOFIN NUMBER(18,6)                  Custo Financeiro            OPERACIONAL                        NaN
PCMOVESTCLI                 PERPIS NUMBER(12,4)                          % do PIS            OPERACIONAL                        NaN
PCMOVESTCLI              PERCOFINS NUMBER(12,4)                       % do COFINS            OPERACIONAL                        NaN
PCMOVESTCLI              CUSTOCONT NUMBER(18,6)                    Custo Contábíl            OPERACIONAL                        NaN
PCMOVESTCLI              CUSTOREAL NUMBER(18,6)                        Custo Real            OPERACIONAL                        NaN
PCMOVESTCLI               CUSTOREP NUMBER(18,6)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI            CUSTOULTENT NUMBER(18,6)           Custo da Última Entrada            OPERACIONAL                        NaN
PCMOVESTCLI            VALORULTENT NUMBER(18,6)           Valor da Última Entrada            OPERACIONAL                        NaN
PCMOVESTCLI             CUSTODOLAR NUMBER(18,6)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI         CUSTOREALSEMST NUMBER(18,6)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI              CODFILIAL  VARCHAR2(2)                     Código Filial            OPERACIONAL                        NaN
PCMOVESTCLI             CODINTERNO VARCHAR2(20)         Código Interno do Produto            OPERACIONAL                        NaN
PCMOVESTCLI              DESCRICAO VARCHAR2(40)              Descrição do Produto            OPERACIONAL                        NaN
PCMOVESTCLI              EMBALAGEM VARCHAR2(12)                         Embalagem            OPERACIONAL                        NaN
PCMOVESTCLI          TIPOMERCDEPTO  VARCHAR2(2)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI               TIPOMERC  VARCHAR2(2)                Tipo da Mercadoria            OPERACIONAL                        NaN
PCMOVESTCLI              SITTRIBUT  VARCHAR2(3)               Situaçao Tributária            OPERACIONAL                        NaN
PCMOVESTCLI        CODGENEROFISCAL  NUMBER(6,0)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI                    NBM VARCHAR2(15)                               NBM            OPERACIONAL                        NaN
PCMOVESTCLI                UNIDADE  VARCHAR2(2)                Unidade do Produto            OPERACIONAL                        NaN
PCMOVESTCLI                     DV  NUMBER(1,0)                Digito Verificador            OPERACIONAL                        NaN
PCMOVESTCLI                 PERICM NUMBER(10,2)                         % do ICMS            OPERACIONAL                        NaN
PCMOVESTCLI        PISCOFINSRETIDO  VARCHAR2(1)                               NaN            OPERACIONAL                        NaN
PCMOVESTCLI DATACONSOLIDACAOPREFAT         DATE Data consolidação Pré-Faturamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*