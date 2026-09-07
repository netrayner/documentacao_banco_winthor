# 📊 Tabela: PCITEMPECACONFERIDO

### Estrutura de Colunas e Restrições

             Tabela    Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMPECACONFERIDO CODFILIAL  VARCHAR2(2)          Código filial do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMPECACONFERIDO    NUMPED NUMBER(10,0) Número do pedido vinculo a venda    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMPECACONFERIDO   CODPROD  NUMBER(6,0)                codigo do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMPECACONFERIDO    QTCONF NUMBER(20,6)             Quantidade conferida            OPERACIONAL                        NaN
PCITEMPECACONFERIDO   ID_PECA NUMBER(20,0)      Identificador único da peça    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMPECACONFERIDO    NUMSEQ NUMBER(20,0)               Sequencia do item.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*