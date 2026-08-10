# 📊 Tabela: PCCONSOLIDATRIBUTACAO

### Estrutura de Colunas e Restrições

               Tabela               Coluna   Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONSOLIDATRIBUTACAO                CODST    NUMBER(4,0)                                                 Figura tributária    CHAVE PRIMÁRIA (PK)                   PCTRIBUT
PCCONSOLIDATRIBUTACAO         PERCALIQUOTA    NUMBER(8,4)                                            Percentual de aliquota            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO        PERCTRIBUTADO    NUMBER(8,4)                                              Percentual tributado            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO           PERCISENTO    NUMBER(8,4)                                                 Percentual Isento            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO            PERCOUTRO    NUMBER(8,4)                                        Percentual outras despesas            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO        REDUCAOBASEST    VARCHAR2(1)                                                  Reduz base de ST            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO    PERCACRESCBENFFIS    NUMBER(3,0)                             Percentual acréscimo beneficio fiscal            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO            SITTRIBUT    NUMBER(3,0)                                               Situação tributária            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO            CODFISCAL    NUMBER(8,0)                                              Código Fiscal - CFOP            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO             UFORIGEM    VARCHAR2(2)                                                  Estado de origem    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSOLIDATRIBUTACAO            UFDESTINO    VARCHAR2(2)                                                 Estado de destino    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSOLIDATRIBUTACAO   CODBENEFICIOFISCAL VARCHAR2(4000)                                        Código do beneficio fiscal            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO        CALCICMSDESON    VARCHAR2(1)                                          Calcula ICMS desoneração            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO      PERCDESONERACAO    NUMBER(8,4)                                         Percentual de desoneração            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO CODMOTIVODESONERACAO    NUMBER(4,0)                                         Código Motivo desoneração            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO            DTALTERC5   TIMESTAMP(6)                                                 Data de alteração            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO            NUMREGIAO    NUMBER(4,0)                                                  Numero da regiao    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSOLIDATRIBUTACAO                 CFOP    NUMBER(8,0)                                                     Código fiscal            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO          CFOPEXTERNO    NUMBER(8,0)                                             Código Fiscal externo            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO            ALIQICMS1   NUMBER(12,4)                                                  Aliquota de icms            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO            ALIQICMS2   NUMBER(12,4)                                                     Aliquota ICMS            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO            CODICMTAB   NUMBER(12,4)                                                       Codigo ICMS            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO      PERCALIQFCPICMS   NUMBER(18,6)                           Aliquota do fundo de combate a pobreza.            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO    PERDESCICMISENCAO    NUMBER(8,4)                                 Percentual desconto ICMS iserncao            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO      CODOBSERVACAOC5    NUMBER(6,0) Vinculo entre a tributação e as tabelas de integraçao da Consinco            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO       TIPOTRIBUTACAO    VARCHAR2(2)                   Tipo da tributação - U : por UF; R : por Região            OPERACIONAL                        NaN
PCCONSOLIDATRIBUTACAO          SITTRIBUTSN    VARCHAR2(3)       CST de Simples Nacional, recebe o campo SITTRIBUTSIMPLESNAC            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*