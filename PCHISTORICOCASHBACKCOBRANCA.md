# 📊 Tabela: PCHISTORICOCASHBACKCOBRANCA

### Estrutura de Colunas e Restrições

                     Tabela              Coluna Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTORICOCASHBACKCOBRANCA         NUMDOCTOPDV NUMBER(11,0)                         Numero de identificação de venda do PDV Supermercados    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKCOBRANCA       CODEMPRESAPDV  NUMBER(3,0)                    Numero da filial que realizou a venda no PDV Supermercados    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKCOBRANCA      CODCHECKOUTPDV  NUMBER(3,0)                      Numero do caixa que realizou a venda no PDV Supermercado    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKCOBRANCA              CODCLI  NUMBER(6,0)                                       Código do cliente que originou cashback    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKCOBRANCA     CODFINALIZADORA  NUMBER(4,0)                   Código da finalizadora que originou o cashback por cobrança    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACKCOBRANCA         VALORGERADO NUMBER(12,2)                                                      Valor de cashback gerado            OPERACIONAL                        NaN
PCHISTORICOCASHBACKCOBRANCA      VALORCONSUMIDO NUMBER(12,2)                                        Valor consumido no ato da venda no PDV            OPERACIONAL                        NaN
PCHISTORICOCASHBACKCOBRANCA      VALORCANCELADO NUMBER(12,2)              Valor cancelado no ato da venda no PDV ou em devolução posterior            OPERACIONAL                        NaN
PCHISTORICOCASHBACKCOBRANCA    NUMDOCTOPDVBAIXA NUMBER(11,0) Numero de identificação de venda do PDV Supermercados que utilizou o cashback            OPERACIONAL                        NaN
PCHISTORICOCASHBACKCOBRANCA  CODEMPRESAPDVBAIXA  NUMBER(3,0)                 Numero da filial que utilizou o cashback no PDV Supermercados            OPERACIONAL                        NaN
PCHISTORICOCASHBACKCOBRANCA CODCHECKOUTPDVBAIXA  NUMBER(3,0)                   Numero do caixa que utilizou o cashback no PDV Supermercado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*