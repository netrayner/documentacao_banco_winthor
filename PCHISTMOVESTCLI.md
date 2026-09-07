# 📊 Tabela: PCHISTMOVESTCLI

### Estrutura de Colunas e Restrições

         Tabela          Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTMOVESTCLI       CODFILIAL  VARCHAR2(2)                  Código Filial            OPERACIONAL                        NaN
PCHISTMOVESTCLI      CODINTERNO VARCHAR2(20)      Código Interno do Produto            OPERACIONAL                        NaN
PCHISTMOVESTCLI       DESCRICAO VARCHAR2(40)           Descrição do Produto            OPERACIONAL                        NaN
PCHISTMOVESTCLI       EMBALAGEM VARCHAR2(12)                      Embalagem            OPERACIONAL                        NaN
PCHISTMOVESTCLI        TIPOMERC  VARCHAR2(2)             Tipo da Mercadoria            OPERACIONAL                        NaN
PCHISTMOVESTCLI       SITTRIBUT  VARCHAR2(3)            Situaçao Tributária            OPERACIONAL                        NaN
PCHISTMOVESTCLI             NBM VARCHAR2(15)                            NBM            OPERACIONAL                        NaN
PCHISTMOVESTCLI         UNIDADE  VARCHAR2(2)             Unidade do Produto            OPERACIONAL                        NaN
PCHISTMOVESTCLI              DV  NUMBER(1,0)             Digito Verificador            OPERACIONAL                        NaN
PCHISTMOVESTCLI          PERICM NUMBER(10,2)                      % do ICMS            OPERACIONAL                        NaN
PCHISTMOVESTCLI          PERPIS NUMBER(12,4)                       % do PIS            OPERACIONAL                        NaN
PCHISTMOVESTCLI       PERCOFINS NUMBER(12,4)                    % do COFINS            OPERACIONAL                        NaN
PCHISTMOVESTCLI       CUSTOCONT NUMBER(18,6)                 Custo Contábíl            OPERACIONAL                        NaN
PCHISTMOVESTCLI         CODPROD  NUMBER(6,0)              Código do produto            OPERACIONAL                        NaN
PCHISTMOVESTCLI          CODCLI  NUMBER(6,0)              Codigo do cliente            OPERACIONAL                        NaN
PCHISTMOVESTCLI           DTMOV         DATE           Data da movimentação            OPERACIONAL                        NaN
PCHISTMOVESTCLI         CODOPER  VARCHAR2(1)             Codigo do operação            OPERACIONAL                        NaN
PCHISTMOVESTCLI              QT NUMBER(18,6)                     Quantidade            OPERACIONAL                        NaN
PCHISTMOVESTCLI         NUMNOTA NUMBER(10,0)                 Numero da nota            OPERACIONAL                        NaN
PCHISTMOVESTCLI     NUMTRANSENT NUMBER(10,0) Numero de transação de entrada            OPERACIONAL                        NaN
PCHISTMOVESTCLI   NUMTRANSVENDA NUMBER(10,0)   Numero de transação de venda            OPERACIONAL                        NaN
PCHISTMOVESTCLI        DTMOVLOG         DATE    Data de movimentação de log            OPERACIONAL                        NaN
PCHISTMOVESTCLI        CUSTOFIN NUMBER(18,6)               Custo Financeiro            OPERACIONAL                        NaN
PCHISTMOVESTCLI       CUSTOREAL NUMBER(18,6)                     Custo Real            OPERACIONAL                        NaN
PCHISTMOVESTCLI        CUSTOREP NUMBER(18,6)                      Custo rep            OPERACIONAL                        NaN
PCHISTMOVESTCLI     CUSTOULTENT NUMBER(18,6)        Custo da Última Entrada            OPERACIONAL                        NaN
PCHISTMOVESTCLI     VALORULTENT NUMBER(18,6)        Valor da Última Entrada            OPERACIONAL                        NaN
PCHISTMOVESTCLI   TIPOMERCDEPTO  VARCHAR2(2)   Tipo mercadoria departamento            OPERACIONAL                        NaN
PCHISTMOVESTCLI CODGENEROFISCAL  NUMBER(6,0)           Codigo genero fiscal            OPERACIONAL                        NaN
PCHISTMOVESTCLI PISCOFINSRETIDO  VARCHAR2(1)              Pis cofins retido            OPERACIONAL                        NaN
PCHISTMOVESTCLI      CUSTODOLAR NUMBER(18,6)                    Custo Dolar            OPERACIONAL                        NaN
PCHISTMOVESTCLI  CUSTOREALSEMST NUMBER(18,6)              Custo real sem st            OPERACIONAL                        NaN
PCHISTMOVESTCLI       DTGERACAO         DATE                Data da geração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*