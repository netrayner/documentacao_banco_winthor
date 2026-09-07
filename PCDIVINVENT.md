# 📊 Tabela: PCDIVINVENT

### Estrutura de Colunas e Restrições

     Tabela            Coluna Tipo/Tamanho                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDIVINVENT         NUMINVENT  NUMBER(8,0)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT           CODPROD  NUMBER(6,0)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT                QT NUMBER(20,8)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT             DTVAL         DATE                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT     DTATUALIZACAO         DATE                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT       CODENDERECO NUMBER(10,0)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT             QTDIV NUMBER(20,8)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT   QTESTENDERECADA NUMBER(20,8)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT          QTESTGER NUMBER(20,8)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT    DTPENULTIMOINV         DATE                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT          CUSTOREP NUMBER(18,6)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT         CODFILIAL  VARCHAR2(2)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT          CUSTOFIN NUMBER(18,6)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT         CUSTOCONT NUMBER(18,6)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT          QTRESERV NUMBER(22,8)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT         CUSTOREAL NUMBER(18,6)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT           LEGENDA  NUMBER(4,0)                                                                                      NaN            OPERACIONAL                        NaN
PCDIVINVENT       QTENDAVARIA NUMBER(20,8)                                                                    Quantidade de avaria.            OPERACIONAL                        NaN
PCDIVINVENT      QTENDEXCESSO NUMBER(20,8)                                                                   Quantidade de excesso.            OPERACIONAL                        NaN
PCDIVINVENT        QTENDCROSS NUMBER(20,8)                                                              Quantidade de crossdocking.            OPERACIONAL                        NaN
PCDIVINVENT        QTENDFALTA NUMBER(20,8)                                                                     Quantidade de falta.            OPERACIONAL                        NaN
PCDIVINVENT          QTAVARIA NUMBER(20,6)                     Quantidade de avaria para cada produto na atualização do inventario.            OPERACIONAL                        NaN
PCDIVINVENT        QTENDSTAGE NUMBER(20,8) Quantida do produto que estava em endereço de stage no momento da atualização gerencial.            OPERACIONAL                        NaN
PCDIVINVENT VERSAOATUALIZACAO    NVARCHAR2                                                                    VERSÃO DA ATUALIZAÇÃO            OPERACIONAL                        NaN
PCDIVINVENT ROTINAATUALIZACAO  NUMBER(6,0)                                                                    ROTINA DA ATUALIZAÇÃO            OPERACIONAL                        NaN
PCDIVINVENT   FILIALGESTAOWMS  VARCHAR2(2)                                                                  Filial de Gestão do WMS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*