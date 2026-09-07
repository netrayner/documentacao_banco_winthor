# 📊 Tabela: PCFINANC3CREDCLI

### Estrutura de Colunas e Restrições

          Tabela            Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFINANC3CREDCLI    DATAREFERENCIA         DATE                             Data de referencia dos dados (data)    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3CREDCLI       DATAGERACAO         DATE                           Data de geração dos dados (data/hora)            OPERACIONAL                        NaN
PCFINANC3CREDCLI  CODROTINAGERACAO  NUMBER(4,0)                             Códido da rotina que gerou os dados    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3CREDCLI         CODFILIAL  VARCHAR2(2)                                      Código da filial do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3CREDCLI          TIPODADO VARCHAR2(10)                           Tipo de dado gerado como na PCFINANC2    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3CREDCLI            CODCLI  NUMBER(6,0)                          Código do cliente vinculado ao crédito            OPERACIONAL                        NaN
PCFINANC3CREDCLI        DTDESCONTO         DATE                   Data de quitação do crédito do cliente (data)            OPERACIONAL                        NaN
PCFINANC3CREDCLI         DTESTORNO         DATE                    Data de estorno do credito de cliente (data)            OPERACIONAL                        NaN
PCFINANC3CREDCLI             VALOR NUMBER(24,8)                                     Valor do credito de cliente            OPERACIONAL                        NaN
PCFINANC3CREDCLI     NUMTRANSVENDA NUMBER(10,0)                Número de transação da venda que gerou o crédito            OPERACIONAL                        NaN
PCFINANC3CREDCLI NUMTRANSVENDADESC NUMBER(12,0)             Número de transação da venda que utilizou o crédito            OPERACIONAL                        NaN
PCFINANC3CREDCLI NUMTRANSENTDEVCLI NUMBER(10,0) Número de transação de entrada de devolução que gerou o credito            OPERACIONAL                        NaN
PCFINANC3CREDCLI      NUMLANCBAIXA  NUMBER(8,0)                        Número de lançamento de baixa do crédito            OPERACIONAL                        NaN
PCFINANC3CREDCLI     NUMTRANSBAIXA NUMBER(10,0)                         Número de transação de baixa do credito            OPERACIONAL                        NaN
PCFINANC3CREDCLI           NUMLANC  NUMBER(8,0)                                 Número de lançamento do crédito            OPERACIONAL                        NaN
PCFINANC3CREDCLI          NUMTRANS NUMBER(10,0)                  Número de transação de movimentação do crédito            OPERACIONAL                        NaN
PCFINANC3CREDCLI           NUMCRED NUMBER(10,0)                              Número de identificação do crédito    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3CREDCLI            DTVENC         DATE                            Data de vencimento do crédito (data)            OPERACIONAL                        NaN
PCFINANC3CREDCLI         CODROTINA  NUMBER(6,0)                Código da rotina que lançou o credito de cliente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*