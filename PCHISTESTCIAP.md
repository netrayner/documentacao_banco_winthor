# 📊 Tabela: PCHISTESTCIAP

### Estrutura de Colunas e Restrições

       Tabela                        Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTESTCIAP                            ID NUMBER(12,0)                          Chave única da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTCIAP                       CODPROD  NUMBER(6,0)                              Código do produto            OPERACIONAL                        NaN
PCHISTESTCIAP                     CODFILIAL  VARCHAR2(2)                               Código da filial            OPERACIONAL                        NaN
PCHISTESTCIAP                      QTPEDIDA NUMBER(22,8)                          Qtde pedida de compra            OPERACIONAL                        NaN
PCHISTESTCIAP                      QTESTGER NUMBER(22,8)                      Qtde de estoque gerencial            OPERACIONAL                        NaN
PCHISTESTCIAP                      QTRESERV NUMBER(22,8)                                 Qtde reservada            OPERACIONAL                        NaN
PCHISTESTCIAP                          DATA         DATE                               Data da inclusão            OPERACIONAL                        NaN
PCHISTESTCIAP          VLCUSTOULTIMAENTRADA NUMBER(18,6)                Custo da última entrada do CIAP            OPERACIONAL                        NaN
PCHISTESTCIAP             VLCUSTOFINANCEIRO NUMBER(18,6)                       Custo financeiro do CIAP            OPERACIONAL                        NaN
PCHISTESTCIAP  VLCUSTOULTIMAENTRADAANTERIOR NUMBER(18,6)       Custo da última entrada anterior do CIAP            OPERACIONAL                        NaN
PCHISTESTCIAP     VLCUSTOFINANCEIROANTERIOR NUMBER(18,6)              Custo financeiro anterior do CIAP            OPERACIONAL                        NaN
PCHISTESTCIAP         DATAHORAULTIMAENTRADA         DATE          Data e hora da última entrada do CIAP            OPERACIONAL                        NaN
PCHISTESTCIAP DATAHORAULTIMAENTRADAANTERIOR         DATE Data e hora da última entrada anterior do CIAP            OPERACIONAL                        NaN
PCHISTESTCIAP               QTULTIMAENTRADA NUMBER(22,8)                 Qtde da última entrada do CIAP            OPERACIONAL                        NaN
PCHISTESTCIAP                TIPOMERCADORIA  VARCHAR2(2)                     Tipo de mercadoria do CIAP            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*