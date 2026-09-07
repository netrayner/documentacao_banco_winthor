# 📊 Tabela: PCBIONEXOPDCICONSOLIDADOR

### Estrutura de Colunas e Restrições

                   Tabela                         Coluna   Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBIONEXOPDCICONSOLIDADOR                         ID_PDC   NUMBER(10,0)              Identificação do pedido            OPERACIONAL                        NaN
PCBIONEXOPDCICONSOLIDADOR                      SEQUENCIA   NUMBER(10,0)          Sequência do item do pedido            OPERACIONAL                        NaN
PCBIONEXOPDCICONSOLIDADOR                 CODIGO_PRODUTO  VARCHAR2(100)                    Código do produto            OPERACIONAL                        NaN
PCBIONEXOPDCICONSOLIDADOR         ID_ARTIGO_CONSOLIDADOR   NUMBER(10,0) Identificação do artigo consolidador            OPERACIONAL                        NaN
PCBIONEXOPDCICONSOLIDADOR    CODIGO_PRODUTO_CONSOLIDADOR   VARCHAR2(30)       Código do produto consolidador            OPERACIONAL                        NaN
PCBIONEXOPDCICONSOLIDADOR DESCRICAO_PRODUTO_CONSOLIDADOR VARCHAR2(1500)    Descrição do produto consolidador            OPERACIONAL                        NaN
PCBIONEXOPDCICONSOLIDADOR        QUANTIDADE_CONSOLIDADOR   NUMBER(12,6)               Quantidade consolidada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*