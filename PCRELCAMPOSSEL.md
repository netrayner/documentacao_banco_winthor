# 📊 Tabela: PCRELCAMPOSSEL

### Estrutura de Colunas e Restrições

        Tabela       Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRELCAMPOSSEL CODRELATORIO   NUMBER(4,0)                         Código do relatório            OPERACIONAL                        NaN
PCRELCAMPOSSEL     CODCAMPO   NUMBER(6,0)                             Código do campo    CHAVE PRIMÁRIA (PK)                        NaN
PCRELCAMPOSSEL    NOMECAMPO VARCHAR2(100)                     Nome do campo da tabela            OPERACIONAL                        NaN
PCRELCAMPOSSEL       FUNCAO   VARCHAR2(5)            Função de agrupamento dos campos            OPERACIONAL                        NaN
PCRELCAMPOSSEL        ORDEM   NUMBER(4,0) Ordem dos campos que irão sair no relatorio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*