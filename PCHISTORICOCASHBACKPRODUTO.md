# 📊 Tabela: PCHISTORICOCASHBACKPRODUTO

### Estrutura de Colunas e Restrições

                    Tabela              Coluna Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTORICOCASHBACKPRODUTO         NUMDOCTOPDV VARCHAR2(11)                         Numero de identificação de venda do PDV Supermercados    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKPRODUTO       CODEMPRESAPDV  NUMBER(3,0)                    Numero da filial que realizou a venda no PDV Supermercados    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKPRODUTO      CODCHECKOUTPDV  NUMBER(3,0)                      Numero do caixa que realizou a venda no PDV Supermercado    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKPRODUTO             CODPROD  NUMBER(6,0)                                       Codigo do produto que originou cashback    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKPRODUTO              CODCLI  NUMBER(6,0)                                       Código do cliente que originou cashback    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKPRODUTO       VALORCASHBACK NUMBER(12,2)                                                      Valor do cahsback gerado            OPERACIONAL                        NaN
PCHISTORICOCASHBACKPRODUTO      VALORCONSUMIDO NUMBER(12,2)                                               Valor consumido no ato da venda            OPERACIONAL                        NaN
PCHISTORICOCASHBACKPRODUTO      VALORCANCELADO NUMBER(12,2)                            Valor cancelado na venda ou em devolução posterior            OPERACIONAL                        NaN
PCHISTORICOCASHBACKPRODUTO    NUMDOCTOPDVBAIXA NUMBER(11,0) Numero de identificação de venda do PDV Supermercados que consumiu o cashback            OPERACIONAL                        NaN
PCHISTORICOCASHBACKPRODUTO  CODEMPRESAPDVBAIXA  NUMBER(3,0)                 Numero da filial que utilizou o cashback no PDV Supermercados            OPERACIONAL                        NaN
PCHISTORICOCASHBACKPRODUTO CODCHECKOUTPDVBAIXA  NUMBER(3,0)                     Numero do caixa que utilizou cashback no PDV Supermercado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*