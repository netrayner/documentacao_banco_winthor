# 📊 Tabela: PCCOMPOSICAO

### Estrutura de Colunas e Restrições

      Tabela              Coluna  Tipo/Tamanho                                                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMPOSICAO       CODPRODMASTER   NUMBER(6,0)                                                                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAO           CODFILIAL   VARCHAR2(2)                                                                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAO             CODPROD   NUMBER(6,0)                                                                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAO              METODO   VARCHAR2(4)                                                                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAO                  QT  NUMBER(14,6)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO              NUMSEQ   NUMBER(4,0)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO           PERCPERDA   NUMBER(8,4)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO          DTCADASTRO          DATE                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO     CODFUNCCADASTRO   NUMBER(8,0)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO          DTULTALTER          DATE                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO        CODFUNCALTER   NUMBER(8,0)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO  LOTEPRODUCAOMASTER  NUMBER(14,2)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO     CODFUNCULTALTER   NUMBER(8,0)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO         FRACAOUMIDA   VARCHAR2(5)                                                                                                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPOSICAO     FRACAOSEPARACAO  NUMBER(20,8)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO            VALIDADE   NUMBER(4,0)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO         UNESTRUTURA  VARCHAR2(40)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO  ACEITAREQACIMAPREV   VARCHAR2(1)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO            NUMETAPA  NUMBER(10,0)                                                                                                                                          NaN            OPERACIONAL                        NaN
PCCOMPOSICAO         NUMDECIMAIS   NUMBER(1,0) Indica número de casas decimais usado na Ordem de Produção (rotinas 1615, 1616). |Campo do tipo numérico, de tamanho 1, sem casas decimais.             OPERACIONAL                        NaN
PCCOMPOSICAO          NUMDECIMAL   NUMBER(1,0)                                                            Indica número de casas decimais usado na Ordem de Produção (rotinas 1615, 1616).             OPERACIONAL                        NaN
PCCOMPOSICAO PERCFORMULACAOTOTAL   NUMBER(6,3)                                                                                                           Indica o percentual da formulação.            OPERACIONAL                        NaN
PCCOMPOSICAO          REPROCESSO   VARCHAR2(1)                                                                                                      Informa se a op é de reprocesso ou não.            OPERACIONAL                        NaN
PCCOMPOSICAO      OBSMETODOTEMPS VARCHAR2(200)                                                                                                                                          NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*