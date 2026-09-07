# 📊 Tabela: PCCONTACENTROCUSTOITEMSOLMAT

### Estrutura de Colunas e Restrições

                      Tabela            Coluna Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTACENTROCUSTOITEMSOLMAT NUMEROSOLICITACAO NUMBER(10,0)     Número da solicitação            OPERACIONAL                        NaN
PCCONTACENTROCUSTOITEMSOLMAT        CODPRODUTO  NUMBER(6,0)         Código do produto            OPERACIONAL                        NaN
PCCONTACENTROCUSTOITEMSOLMAT          CODCONTA NUMBER(10,0)           Código da conta            OPERACIONAL                        NaN
PCCONTACENTROCUSTOITEMSOLMAT        PERCRATEIO NUMBER(10,6)      Percentual de rateio            OPERACIONAL                        NaN
PCCONTACENTROCUSTOITEMSOLMAT    CODCENTROCUSTO NUMBER(10,0)            CODCENTROCUSTO            OPERACIONAL                        NaN
PCCONTACENTROCUSTOITEMSOLMAT CODIGOCENTROCUSTO VARCHAR2(40) Codigo do centro de custo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*