# 📊 Tabela: PCLOTECONT

### Estrutura de Colunas e Restrições

    Tabela    Coluna Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOTECONT CODFILIAL  VARCHAR2(2)                                        Indica o código da Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTECONT   CODLOTE NUMBER(38,0) Indica o código do lote que foi informado no lançamento contábil.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTECONT       MES  NUMBER(2,0)                              Indica o mês do lançamento contábil.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTECONT       ANO  NUMBER(4,0)                              Indica o ano do lançamento contábil.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTECONT VALORLOTE NUMBER(22,2)                    Indica o valor do Lote no lançamento contábil.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*