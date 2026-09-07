# 📊 Tabela: PCPRODSUBST

### Estrutura de Colunas e Restrições

     Tabela         Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODSUBST   CODPRODSUBST  NUMBER(6,0)            Indica o código do produto substituído.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODSUBST         NUMSEQ  NUMBER(6,0)        Indica o sequencial do produto substituído.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODSUBST   CODPRODSIMIL  NUMBER(6,0)                Indica o código do produto similar.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODSUBST    NUMPEDSUBST NUMBER(10,0) Indica o número do pedido com produto substituído.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODSUBST      DATASUBST         DATE                     Indica a data da substituição.            OPERACIONAL                        NaN
PCPRODSUBST   CODFUNCSUBST  NUMBER(8,0)    Indica o código do funcionário da substituição.            OPERACIONAL                        NaN
PCPRODSUBST   PTABELASUBST NUMBER(18,6)      Indica o preço de tabela produto substituído.            OPERACIONAL                        NaN
PCPRODSUBST PTABELASIMILAR NUMBER(18,6)       Indica o preço de tabela do produto similar.            OPERACIONAL                        NaN
PCPRODSUBST        QTSUBST NUMBER(14,6)                        Quantidade da substituição.            OPERACIONAL                        NaN
PCPRODSUBST      QTSIMILAR NUMBER(14,6)                             Quantidade do similar.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*