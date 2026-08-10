# 📊 Tabela: PCBIONEXOPDCI

### Estrutura de Colunas e Restrições

       Tabela                 Coluna   Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBIONEXOPDCI                 ID_PDC   NUMBER(10,0)                  Identificação do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCBIONEXOPDCI              SEQUENCIA   NUMBER(10,0)            Sequência dos itens do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCBIONEXOPDCI              ID_ARTIGO   NUMBER(10,0)                  Identificação do artigo            OPERACIONAL                        NaN
PCBIONEXOPDCI         CODIGO_PRODUTO  VARCHAR2(100)                        Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCBIONEXOPDCI      DESCRICAO_PRODUTO  VARCHAR2(100)                      Descrição do pedido            OPERACIONAL                        NaN
PCBIONEXOPDCI             QUANTIDADE   NUMBER(18,6)                       Quatidade de itens            OPERACIONAL                        NaN
PCBIONEXOPDCI                  VALOR   NUMBER(18,6)                      Valor total do item            OPERACIONAL                        NaN
PCBIONEXOPDCI         MARCA_FAVORITA  VARCHAR2(100)                         Marca do produto            OPERACIONAL                        NaN
PCBIONEXOPDCI             FABRICANTE  VARCHAR2(300)                    Fabricante do produto            OPERACIONAL                        NaN
PCBIONEXOPDCI                    IVA    VARCHAR2(3)                              Imposto IVA            OPERACIONAL                        NaN
PCBIONEXOPDCI PRECO_UNITARIO_LIQUIDO   NUMBER(12,6)                   Preço unitário do item            OPERACIONAL                        NaN
PCBIONEXOPDCI                   ICMS   NUMBER(12,6)                          ICMS do produto            OPERACIONAL                        NaN
PCBIONEXOPDCI                    IPI   NUMBER(12,6)                           IPI do produto            OPERACIONAL                        NaN
PCBIONEXOPDCI             COMENTARIO VARCHAR2(3000)                Comentário para o produto            OPERACIONAL                        NaN
PCBIONEXOPDCI                CODPROD    NUMBER(6,0)                        Código do produto            OPERACIONAL                        NaN
PCBIONEXOPDCI     QUANTIDADEATENDIDA   NUMBER(12,6) Quantidade separada/conferida do produto            OPERACIONAL                        NaN
PCBIONEXOPDCI         ID_CONFIRMACAO   NUMBER(10,0)             Identificação da confirmação            OPERACIONAL                        NaN
PCBIONEXOPDCI             MSGULT_ENV VARCHAR2(4000)                  Última mensagem enviava            OPERACIONAL                        NaN
PCBIONEXOPDCI       ENVIADONACOTACAO    VARCHAR2(1)                       Enviado na cotação            OPERACIONAL                        NaN
PCBIONEXOPDCI         UNIDADE_MEDIDA  VARCHAR2(100)                        Unidade de medida            OPERACIONAL                        NaN
PCBIONEXOPDCI      ID_UNIDADE_MEDIDA   NUMBER(20,6)       Identificação da unidade de medida            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*