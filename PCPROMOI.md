# 📊 Tabela: PCPROMOI

### Estrutura de Colunas e Restrições

  Tabela                Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPROMOI           CODPROMOCAO  NUMBER(6,0)                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPROMOI               CODPROD  NUMBER(6,0)                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPROMOI              QTPONTOS NUMBER(10,4)                                                       NaN            OPERACIONAL                        NaN
PCPROMOI                QTMETA  NUMBER(8,2)                                                       NaN            OPERACIONAL                        NaN
PCPROMOI         QTPONTOSVALOR  NUMBER(8,2)                                                       NaN            OPERACIONAL                        NaN
PCPROMOI       QTPONTOSCLIENTE  NUMBER(8,2)                                                       NaN            OPERACIONAL                        NaN
PCPROMOI          QTPONTOSMETA  NUMBER(8,2)                                                       NaN            OPERACIONAL                        NaN
PCPROMOI           VLCADAPONTO NUMBER(18,6)                                                       NaN            OPERACIONAL                        NaN
PCPROMOI            QTMAXPONTO  NUMBER(8,2) Quantidade máxima de pontos neste produto/prod principal.            OPERACIONAL                        NaN
PCPROMOI          QTPONTOSPESO  NUMBER(8,2)                Quantidade de pontos por peso(KG) vendido.            OPERACIONAL                        NaN
PCPROMOI             QTMINITEM  NUMBER(8,0)                            Quantidade minima por produto.            OPERACIONAL                        NaN
PCPROMOI QTPESOMINIMOPONTUACAO  NUMBER(8,2)              Qtd. Peso mínimo para pontuação da campanha.            OPERACIONAL                        NaN
PCPROMOI            DTMXSALTER         DATE                                                       NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*