# 📊 Tabela: PCLAYOUTCOBVAR

### Estrutura de Colunas e Restrições

        Tabela           Coluna   Tipo/Tamanho                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTCOBVAR             NOME   VARCHAR2(50)                                                                                      Nome    CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTCOBVAR        DESCRICAO  VARCHAR2(200)                                                                                 Descrição            OPERACIONAL                        NaN
PCLAYOUTCOBVAR      CODPROCESSO         NUMBER                                                                        Codigo do processo            OPERACIONAL                        NaN
PCLAYOUTCOBVAR NATUREZAOPERACAO    VARCHAR2(2) Indica que layout pode usar a variável: de remessa (RM), de retorno (RT) ou dos dois (RR)            OPERACIONAL                        NaN
PCLAYOUTCOBVAR     TIPOCONTEUDO    VARCHAR2(4)                                                                          Tipo do conteúdo            OPERACIONAL                        NaN
PCLAYOUTCOBVAR         CONTEUDO VARCHAR2(2000)                               De qual tabela e campo ou SQL é obtido o valor da variável.            OPERACIONAL                        NaN
PCLAYOUTCOBVAR        TIPODADOS    VARCHAR2(2)                                                                             Tipo de dados            OPERACIONAL                        NaN
PCLAYOUTCOBVAR        TABELASIS  VARCHAR2(100)                                                                                    Tabela            OPERACIONAL                        NaN
PCLAYOUTCOBVAR        COLUNASIS  VARCHAR2(100)                                                                                    Coluna            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*