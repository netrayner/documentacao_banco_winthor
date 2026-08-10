# 📊 Tabela: PCESTCIAP

### Estrutura de Colunas e Restrições

   Tabela                        Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTCIAP                       CODPROD  NUMBER(6,0)                      Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCESTCIAP                     CODFILIAL  VARCHAR2(2)                       Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCESTCIAP                      QTPEDIDA NUMBER(22,8)                  Qtde Pedida de compra            OPERACIONAL                        NaN
PCESTCIAP                      QTESTGER NUMBER(22,8)              Qtde de estoque gerencial            OPERACIONAL                        NaN
PCESTCIAP                      QTRESERV NUMBER(22,8)                   Quantidade Reservada            OPERACIONAL                        NaN
PCESTCIAP          VLCUSTOULTIMAENTRADA NUMBER(18,6)                Custo da última entrada            OPERACIONAL                        NaN
PCESTCIAP             VLCUSTOFINANCEIRO NUMBER(18,6)                       Custo financeiro            OPERACIONAL                        NaN
PCESTCIAP  VLCUSTOULTIMAENTRADAANTERIOR NUMBER(18,6)       Custo da ultima entrada anterior            OPERACIONAL                        NaN
PCESTCIAP     VLCUSTOFINANCEIROANTERIOR NUMBER(18,6)              Custo financeiro anterior            OPERACIONAL                        NaN
PCESTCIAP         DATAHORAULTIMAENTRADA         DATE          Data e hora da ultima entrada            OPERACIONAL                        NaN
PCESTCIAP DATAHORAULTIMAENTRADAANTERIOR         DATE Data e hora da ultima entrada anterior            OPERACIONAL                        NaN
PCESTCIAP               QTULTIMAENTRADA NUMBER(22,8)           Quantidade da ultima entrada            OPERACIONAL                        NaN
PCESTCIAP                TIPOMERCADORIA  VARCHAR2(2)                     Tipo de mercadoria            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*