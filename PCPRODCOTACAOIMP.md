# 📊 Tabela: PCPRODCOTACAOIMP

### Estrutura de Colunas e Restrições

          Tabela            Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODCOTACAOIMP CODPRODCOTACAOIMP  NUMBER(8,0)                           Chave primária    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODCOTACAOIMP        NUMCOTACAO  NUMBER(8,0)                        Número da cotação CHAVE ESTRANGEIRA (FK)               PCCOTACAOIMP
PCPRODCOTACAOIMP         CODFILIAL  VARCHAR2(2)                         Código da filial            OPERACIONAL                        NaN
PCPRODCOTACAOIMP           CODPROD  NUMBER(6,0)                        Código do produto            OPERACIONAL                        NaN
PCPRODCOTACAOIMP         DESCRICAO VARCHAR2(40)                     Descrição do produto            OPERACIONAL                        NaN
PCPRODCOTACAOIMP          QTPEDIDA NUMBER(14,4)                        Quantidade pedida            OPERACIONAL                        NaN
PCPRODCOTACAOIMP        QTSUGESTAO NUMBER(14,4)                      Quantidade sugerida            OPERACIONAL                        NaN
PCPRODCOTACAOIMP      PEDIDOGERADO      CHAR(1) Flag verificando se o pedido foi emitido            OPERACIONAL                        NaN
PCPRODCOTACAOIMP           UNIDADE      CHAR(2)                       Unidade do produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*