# 📊 Tabela: PCLFPISREG0112

### Estrutura de Colunas e Restrições

        Tabela          Coluna Tipo/Tamanho                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLFPISREG0112       CODFILIAL  VARCHAR2(2)                                                                        Código da Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFPISREG0112         DATAINI         DATE                                                     Data Inicial do Período Selecionado.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFPISREG0112         DATAFIM         DATE                                                       Data Final do Período Selecionado.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFPISREG0112           INDST  NUMBER(1,0)                                                        Indicador de Situação Tributária.            OPERACIONAL                        NaN
PCLFPISREG0112 PERRECBRUTRIBMI NUMBER(15,6)     Percentual do Rateio da Receita Bruta Não-Cumulativa - Tributada no Mercado Interno.            OPERACIONAL                        NaN
PCLFPISREG0112   PERRECBRUNTMI NUMBER(15,6) Percentual do Rateio da Receita Bruta Não-Cumulativa ¿ Não Tributada no Mercado Interno.            OPERACIONAL                        NaN
PCLFPISREG0112    PERRECBRUEXP NUMBER(15,6)                       Percentual do Rateio da Receita Bruta Não Cumulativa - Exportação.            OPERACIONAL                        NaN
PCLFPISREG0112    PERRECBRUCUM NUMBER(15,6)                                        Percentual do Rateio da Receita Bruta Cumulativa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*