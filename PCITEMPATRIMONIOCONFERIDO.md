# 📊 Tabela: PCITEMPATRIMONIOCONFERIDO

### Estrutura de Colunas e Restrições

                   Tabela         Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMPATRIMONIOCONFERIDO      CODFILIAL  VARCHAR2(2)                           Filial do equipamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMPATRIMONIOCONFERIDO         NUMPED NUMBER(10,0) Número do pedidos do produto que controla equip.    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMPATRIMONIOCONFERIDO        CODPROD  NUMBER(6,0)                               Código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMPATRIMONIOCONFERIDO CODEQUIPAMENTO NUMBER(10,0)             Código identificados do equipamento.            OPERACIONAL                        NaN
PCITEMPATRIMONIOCONFERIDO   IDPATRIMONIO VARCHAR2(75)      ID do patrimônio do equipamento conferido..    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMPATRIMONIOCONFERIDO         NUMCAR  NUMBER(8,0) Número de carregamento do pedido em conferência.            OPERACIONAL                        NaN
PCITEMPATRIMONIOCONFERIDO        NUMNOTA NUMBER(10,0)                         Número da nota do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMPATRIMONIOCONFERIDO  NUMTRANSVENDA NUMBER(10,0)                    Número de transação de saída.            OPERACIONAL                        NaN
PCITEMPATRIMONIOCONFERIDO         QTCONF NUMBER(20,4)                            Quantidade conferida.            OPERACIONAL                        NaN
PCITEMPATRIMONIOCONFERIDO    CODFUNCCONF  NUMBER(8,0)                            Código do conferente.            OPERACIONAL                        NaN
PCITEMPATRIMONIOCONFERIDO       DATACONF         DATE                             Data da conferência.            OPERACIONAL                        NaN
PCITEMPATRIMONIOCONFERIDO    CODAUXILIAR NUMBER(20,0)                      Código auxiliar do produto.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*