# 📊 Tabela: PCHISTESTLOTE

### Estrutura de Colunas e Restrições

       Tabela      Coluna Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTESTLOTE   CODFILIAL  VARCHAR2(2)                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTLOTE     CODPROD  NUMBER(6,0)                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTLOTE        DATA         DATE                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTLOTE          QT NUMBER(22,8)                                                                                            NaN            OPERACIONAL                        NaN
PCHISTESTLOTE       QTEST NUMBER(22,8)                                                                                            NaN            OPERACIONAL                        NaN
PCHISTESTLOTE    QTRESERV NUMBER(22,8)                                                                                            NaN            OPERACIONAL                        NaN
PCHISTESTLOTE QTBLOQUEADA NUMBER(22,8)                                                                                            NaN            OPERACIONAL                        NaN
PCHISTESTLOTE   QTINDENIZ NUMBER(22,8)                                                                                            NaN            OPERACIONAL                        NaN
PCHISTESTLOTE   DTGERACAO         DATE                                                                                            NaN            OPERACIONAL                        NaN
PCHISTESTLOTE     NUMLOTE VARCHAR2(15)                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTLOTE QTINDUSTRIA NUMBER(20,6) Campo destinado a quantidade de produtos que está em poder da indústria, aguardando liberação.            OPERACIONAL                        NaN
PCHISTESTLOTE QTCROSSDOCK NUMBER(22,8)                                                                  Saldo Estoque em Crossdocking            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*