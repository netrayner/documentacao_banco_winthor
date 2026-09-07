# 📊 Tabela: PCCROSSDOCKING

### Estrutura de Colunas e Restrições

        Tabela        Coluna Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCROSSDOCKING       CODPROD  NUMBER(6,0)                                                     NaN            OPERACIONAL                        NaN
PCCROSSDOCKING        CODCLI  NUMBER(6,0)                                                     NaN            OPERACIONAL                        NaN
PCCROSSDOCKING            QT NUMBER(20,8)                                                     NaN            OPERACIONAL                        NaN
PCCROSSDOCKING      NUMBONUS  NUMBER(6,0)                                                     NaN            OPERACIONAL                        NaN
PCCROSSDOCKING   CODENDERECO NUMBER(10,0)                  Indica o código do endereço reservado.            OPERACIONAL                        NaN
PCCROSSDOCKING       NUMLOTE VARCHAR2(15)                                                     NaN            OPERACIONAL                        NaN
PCCROSSDOCKING    DESPACHADO  VARCHAR2(1)                                                     NaN            OPERACIONAL                        NaN
PCCROSSDOCKING NUMTRANSVENDA NUMBER(10,0)                                                     NaN            OPERACIONAL                        NaN
PCCROSSDOCKING           BOX  NUMBER(6,0)                                                     NaN            OPERACIONAL                        NaN
PCCROSSDOCKING    CODFUNCGER  NUMBER(8,0) Indica o código do funcionário gerador da movimentação.            OPERACIONAL                        NaN
PCCROSSDOCKING          DATA         DATE                          Indica a data da movimentação.            OPERACIONAL                        NaN
PCCROSSDOCKING       DTFIMOS         DATE                    Indica a data e hora da finalização.            OPERACIONAL                        NaN
PCCROSSDOCKING  DTINTEGRACAO         DATE                                         Data Integração            OPERACIONAL                        NaN
PCCROSSDOCKING        NUMPED NUMBER(10,0)                                       Número do pedido.            OPERACIONAL                        NaN
PCCROSSDOCKING       POSICAO      CHAR(1)        Posição da reserva. P = Pendente, C = Confirmado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*