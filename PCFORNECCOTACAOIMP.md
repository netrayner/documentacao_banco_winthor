# 📊 Tabela: PCFORNECCOTACAOIMP

### Estrutura de Colunas e Restrições

            Tabela           Coluna   Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORNECCOTACAOIMP  CODFORNECCOTIMP    NUMBER(8,0)                                   Sequencial da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCFORNECCOTACAOIMP       NUMCOTACAO    NUMBER(8,0)                                      Número da cotação CHAVE ESTRANGEIRA (FK)               PCCOTACAOIMP
PCFORNECCOTACAOIMP        CODFORNEC    NUMBER(8,0)                                   Código do fornecedor            OPERACIONAL                        NaN
PCFORNECCOTACAOIMP       FORNECEDOR   VARCHAR2(60)                                     Nome do fornecedor            OPERACIONAL                        NaN
PCFORNECCOTACAOIMP       OBSERVACAO VARCHAR2(4000)                                             Observação            OPERACIONAL                        NaN
PCFORNECCOTACAOIMP         INCOTERM    VARCHAR2(5)                                Código INCOTERM - Frete            OPERACIONAL                        NaN
PCFORNECCOTACAOIMP         CODMOEDA    NUMBER(6,0)                                        Código da moeda            OPERACIONAL                        NaN
PCFORNECCOTACAOIMP PERCADIANTAMENTO   NUMBER(22,8)              Percentual de pagamento tipo adiantamento            OPERACIONAL                        NaN
PCFORNECCOTACAOIMP       PERCAVISTA   NUMBER(22,8)                   Percentual de pagamento tipo à vista            OPERACIONAL                        NaN
PCFORNECCOTACAOIMP       PERCAPRAZO   NUMBER(22,8)                   Percentual de pagamento tipo a prazo            OPERACIONAL                        NaN
PCFORNECCOTACAOIMP        VLCOTACAO   NUMBER(18,6) Valor da cotação da moeda no dia da cotação do produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*