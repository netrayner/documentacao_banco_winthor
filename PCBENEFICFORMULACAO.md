# 📊 Tabela: PCBENEFICFORMULACAO

### Estrutura de Colunas e Restrições

             Tabela              Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICFORMULACAO         NUMTRANSENT NUMBER(10,0)                   Transação de entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICFORMULACAO              NUMPED NUMBER(10,0)              Numero pedido req.insumos CHAVE ESTRANGEIRA (FK)               PCBENEFICMPI
PCBENEFICFORMULACAO             CODPROD NUMBER(10,0)             Codigo produto req.insumos CHAVE ESTRANGEIRA (FK)               PCBENEFICMPI
PCBENEFICFORMULACAO              NUMSEQ  NUMBER(5,0)          Sequencia produto req.insumos CHAVE ESTRANGEIRA (FK)               PCBENEFICMPI
PCBENEFICFORMULACAO      QTMATERIAPRIMA NUMBER(18,6)            Quantidade de materia prima            OPERACIONAL                        NaN
PCBENEFICFORMULACAO   PRECOMATERIAPRIMA NUMBER(18,6)                 Preço da materia prima            OPERACIONAL                        NaN
PCBENEFICFORMULACAO            NUMPEDPA NUMBER(10,0)     Numero pedido ordem beneficiamento CHAVE ESTRANGEIRA (FK)               PCBENEFICPAI
PCBENEFICFORMULACAO           CODPRODPA NUMBER(10,0)    Codigo produto ordem beneficiamento CHAVE ESTRANGEIRA (FK)               PCBENEFICPAI
PCBENEFICFORMULACAO            NUMSEQPA  NUMBER(5,0) Sequencia produto ordem beneficiamento CHAVE ESTRANGEIRA (FK)               PCBENEFICPAI
PCBENEFICFORMULACAO    QTPRODUTOACABADO NUMBER(18,6)          Quantidade de produto acabado            OPERACIONAL                        NaN
PCBENEFICFORMULACAO PRECOPRODUTOACABADO NUMBER(18,6)               Preço do produto acabado            OPERACIONAL                        NaN
PCBENEFICFORMULACAO       ALIQPROPORCAO  NUMBER(7,4)            Alíquota de rateio de custo            OPERACIONAL                        NaN
PCBENEFICFORMULACAO             QTSOBRA NUMBER(18,6)   Quantidade de sobra de materia prima            OPERACIONAL                        NaN
PCBENEFICFORMULACAO             QTPERDA NUMBER(18,6)   Quantidade de perda de materia prima            OPERACIONAL                        NaN
PCBENEFICFORMULACAO        PRECOPAFINAL NUMBER(18,6)         Preço final do produto acabado            OPERACIONAL                        NaN
PCBENEFICFORMULACAO       CODBENEFICMPI  NUMBER(8,0)           Número sequencial formulação    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*