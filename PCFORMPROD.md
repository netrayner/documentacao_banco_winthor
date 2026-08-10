# 📊 Tabela: PCFORMPROD

### Estrutura de Colunas e Restrições

    Tabela               Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMPROD          CODPRODACAB  NUMBER(6,0)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD            CODPRODMP  NUMBER(6,0)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD           QTPRODACAB NUMBER(12,6)                                           Descricao coluna QTPRODACAB            OPERACIONAL                        NaN
PCFORMPROD             QTPRODMP NUMBER(12,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD              CODOPER  VARCHAR2(1)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD         ACEITAFRACAO  VARCHAR2(1)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD         BAIXAESTOQUE  VARCHAR2(1)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD            CODFILIAL  VARCHAR2(2)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD         GERAETIQUETA  VARCHAR2(1)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD              QTRENDA NUMBER(12,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD         CUSTOPRODUTO NUMBER(12,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD              CUSTOKG NUMBER(12,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD              CUSTOMP NUMBER(12,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD          QTDEMPPORKG NUMBER(12,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD           CUSTOPORKG NUMBER(12,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD           QTMPBAIXAR NUMBER(12,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD           QTPRODUCAO NUMBER(12,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD      VLCUSTOMONTAGEM NUMBER(10,6)                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD      PERCPRODACABADO NUMBER(12,4)                   Percentual representativo do produto na formulação.            OPERACIONAL                        NaN
PCFORMPROD PERCVALORPRODACABADO NUMBER(12,4)                                          Percentual financeiro do PA.            OPERACIONAL                        NaN
PCFORMPROD        CODAUXILIARMP NUMBER(20,0) Código auxiliar da embalagem que compõe a fórmula de uma cesta ou kit            OPERACIONAL                        NaN
PCFORMPROD            KITABERTO  VARCHAR2(1)                              Indica se a cesta básica é um kit aberto            OPERACIONAL                        NaN
PCFORMPROD           DTMXSALTER         DATE                                                                   NaN            OPERACIONAL                        NaN
PCFORMPROD           DTCADASTRO         DATE                                                      DATA DO CADASTRO            OPERACIONAL                        NaN
PCFORMPROD           DTULTALTER         DATE                                                     DATA DE ALTERACAO            OPERACIONAL                        NaN
PCFORMPROD      DTULTALTERPRECO         DATE                                                  DATA ALTERACAO PRECO            OPERACIONAL                        NaN
PCFORMPROD  CODFILIALINTEGRACAO  NUMBER(3,0)                                        Código da Filial de Integração            OPERACIONAL                        NaN
PCFORMPROD            DTALTERC5 TIMESTAMP(6)                                            Data alteração do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*