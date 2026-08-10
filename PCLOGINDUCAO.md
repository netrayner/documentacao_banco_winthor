# 📊 Tabela: PCLOGINDUCAO

### Estrutura de Colunas e Restrições

      Tabela         Coluna  Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGINDUCAO     NUMINDUCAO   NUMBER(8,0) IDENTIFICAÇÃO DO NÚMERO DE INDUÇÕES FEITAS NO LOTE PARA O PEDIDO            OPERACIONAL                        NaN
PCLOGINDUCAO      DTINDUCAO          DATE                                 DATA COMPLETA DA INDUÇÃO DO LOTE            OPERACIONAL                        NaN
PCLOGINDUCAO      CODFILIAL   VARCHAR2(2)                                       FILIAL DOS LOTES INDUZIDOS            OPERACIONAL                        NaN
PCLOGINDUCAO         NUMPED  NUMBER(10,0)                    NUMERO DO PEDIDO A SOFRER A INDUÇÃO DOS LOTES            OPERACIONAL                        NaN
PCLOGINDUCAO        CODPROD   NUMBER(6,0)                                      CODIGO DO PRODUTO DO PEDIDO            OPERACIONAL                        NaN
PCLOGINDUCAO         NUMSEQ  NUMBER(10,0)                            NÚMERO DE SEQUENCIA DO ITEM DO PEDIDO            OPERACIONAL                        NaN
PCLOGINDUCAO        NUMLOTE  VARCHAR2(15)                                                   LOTE DO PEDIDO            OPERACIONAL                        NaN
PCLOGINDUCAO         QTCONF  NUMBER(18,6)                           QUANTIDADE CONFERIDA DO ITEM DO PEDIDO            OPERACIONAL                        NaN
PCLOGINDUCAO         NUMCAR   NUMBER(8,0)                                 NÚMERO DO CARREGAMENTO DO PEDIDO            OPERACIONAL                        NaN
PCLOGINDUCAO       NUMCAIXA  NUMBER(10,0)                                        NÚMERO DA CAIXA DO PEDIDO            OPERACIONAL                        NaN
PCLOGINDUCAO       QTRESERV  NUMBER(18,6)                           QUANTIDADE RESERVADA DO ITEM DO PEDIDO            OPERACIONAL                        NaN
PCLOGINDUCAO     QTINDUZIDA  NUMBER(18,6)                                      QUANTIDADE INDUZIDA DO LOTE            OPERACIONAL                        NaN
PCLOGINDUCAO     DTVALIDADE          DATE                                         DATA DE VALIDADE DO LOTE            OPERACIONAL                        NaN
PCLOGINDUCAO  ROTINAINDUCAO  VARCHAR2(40)                  ROTINA QUE ORIGINOU A INDUCAO DO LOTE NO PEDIDO            OPERACIONAL                        NaN
PCLOGINDUCAO   OBSAPLICACAO VARCHAR2(200)                                          OBSERVAÇÃO DA APLICAÇÃO            OPERACIONAL                        NaN
PCLOGINDUCAO NUMVIASMAPASEP   NUMBER(2,0)                      NUMERO DE VIAS DE EMISSÃO DO MAPA DO PEDIDO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*