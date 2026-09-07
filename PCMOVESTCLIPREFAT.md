# 📊 Tabela: PCMOVESTCLIPREFAT

### Estrutura de Colunas e Restrições

           Tabela                 Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVESTCLIPREFAT                 CODCLI  NUMBER(6,0)                       Código Cliente            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT              CODFILIAL  VARCHAR2(2)                        Código Filial            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT        CODGENEROFISCAL  NUMBER(6,0)                 Código genero fiscal            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT             CODINTERNO VARCHAR2(20)            Código Interno do Produto            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                CODOPER  VARCHAR2(1)                   Código da operação            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                CODPROD  NUMBER(6,0)                       Código Produto            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT              CUSTOCONT NUMBER(18,6)                       Custo Contábíl            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT             CUSTODOLAR NUMBER(18,6)                       Custo do dólar            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT               CUSTOFIN NUMBER(18,6)                     Custo financeiro            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT              CUSTOREAL NUMBER(18,6)                           Custo Real            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT         CUSTOREALSEMST NUMBER(18,6)                  Custo real sem o ST            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT               CUSTOREP NUMBER(18,6)                   Custo de reposição            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT            CUSTOULTENT NUMBER(18,6)              Custo da Última Entrada            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT              DESCRICAO VARCHAR2(40)                 Descrição do Produto            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                  DTMOV         DATE                    Data Movimentação            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT               DTMOVLOG         DATE                   Data movimento Log            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                     DV  NUMBER(1,0)                   Digito Verificador            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT              EMBALAGEM VARCHAR2(12)                            Embalagem            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                    NBM VARCHAR2(15)                       Informação NBM            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                NUMNOTA NUMBER(10,0)                       Número da Nota            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT            NUMTRANSENT NUMBER(10,0)          Número Transação de Entrada            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT          NUMTRANSVENDA NUMBER(10,0)            Número Transação de Saída            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT              PERCOFINS NUMBER(12,4)                          % do COFINS            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                 PERICM NUMBER(10,2)                            % do ICMS            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                 PERPIS NUMBER(12,4)                             % do PIS            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT        PISCOFINSRETIDO  VARCHAR2(1) Informa se o PIS e COFINS foi retido            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                     QT NUMBER(18,6)                           Quantidade            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT              SITTRIBUT  VARCHAR2(3)                  Situaçao Tributária            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT               TIPOMERC  VARCHAR2(2)                   Tipo da Mercadoria            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT          TIPOMERCDEPTO  VARCHAR2(2)     Tipo mercadoria por departamento            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT                UNIDADE  VARCHAR2(2)                   Unidade do Produto            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT            VALORULTENT NUMBER(18,6)              Valor da Última Entrada            OPERACIONAL                        NaN
PCMOVESTCLIPREFAT DATACONSOLIDACAOPREFAT         DATE    Data Consolidação Pré Faturamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*