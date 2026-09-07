# 📊 Tabela: PCFINANC3LANCADIANT

### Estrutura de Colunas e Restrições

             Tabela                   Coluna Tipo/Tamanho                                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFINANC3LANCADIANT           DATAREFERENCIA         DATE                                   Data de referencia dos dados (data)\tData de referencia dos dados (data)    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCADIANT              DATAGERACAO         DATE                               Data de geração dos dados (data/hora)\tData de geração dos dados (data/hora)            OPERACIONAL                        NaN
PCFINANC3LANCADIANT         CODROTINAGERACAO  NUMBER(4,0)                                   Códido da rotina que gerou os dados\tCódido da rotina que gerou os dados    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCADIANT                CODFILIAL  VARCHAR2(2)                                                     Código da filial do título\tCódigo da filial do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCADIANT                 TIPODADO VARCHAR2(10)                               Tipo de dado gerado como na PCFINANC2\tTipo de dado gerado como na PCFINANC2    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCADIANT                   RECNUM  NUMBER(8,0)                                             Número de lançamento do título\tNúmero de lançamento do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCADIANT              RECNUMPRINC  NUMBER(8,0)                         Número de lançamento principal do título\tNúmero de lançamento principal do título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                   DTLANC         DATE             Data de lançamento do título no sistema (data)\tData de lançamento do título no sistema (data)            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                 CODGRUPO  NUMBER(4,0)                                     Código do grupo da conta do título\tCódigo do grupo da conta do título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                 CODCONTA NUMBER(10,0)                                                       Código da conta do título\tCódigo da conta do título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                CODFORNEC  NUMBER(8,0)                             Código do parceiro vinculado ao título\tCódigo do parceiro vinculado ao título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                  NUMNOTA NUMBER(10,0)               Número da nota de entrada vinculada ao título\tNúmero da nota de entrada vinculada ao título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                   DUPLIC  VARCHAR2(1)                               Número da duplicata (parcela) a pagar\tNúmero da duplicata (parcela) a pagar            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                    VALOR NUMBER(24,8)                                                                           Valor do título\tValor do título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                   DTVENC         DATE                                   Data de vencimento do título (data)\tData de vencimento do título (data)            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                    VPAGO NUMBER(24,8)                                                 Valor que foi pago no título\tValor que foi pago no título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                  DTPAGTO         DATE                                     Data de pagamento do título (data)\tData de pagamento do título (data)            OPERACIONAL                        NaN
PCFINANC3LANCADIANT             TIPOPARCEIRO  VARCHAR2(1)                                 Tipo do parceiro vinculado ao título\tTipo do parceiro vinculado ao título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                   DTDESD         DATE                             Data de desdobramento do título (data)\tData de desdobramento do título (data)            OPERACIONAL                        NaN
PCFINANC3LANCADIANT             ADIANTAMENTO  VARCHAR2(1)                                                          Identifica se lançamento é ou não de adiantamento            OPERACIONAL                        NaN
PCFINANC3LANCADIANT           DTESTORNOBAIXA         DATE                                                                     Data de estorno de baixa de lançamento            OPERACIONAL                        NaN
PCFINANC3LANCADIANT VLRUTILIZADOADIANTFORNEC NUMBER(12,2)                                                  Valor que já foi utilizado pelo adiantamento a Fornecedor            OPERACIONAL                        NaN
PCFINANC3LANCADIANT        VLVARIACAOCAMBIAL NUMBER(18,6)                                                                                  Valor da variação cambial            OPERACIONAL                        NaN
PCFINANC3LANCADIANT           CODROTINABAIXA  NUMBER(6,0)                                                         Código da rotina que efetuou a baixa do lançamento            OPERACIONAL                        NaN
PCFINANC3LANCADIANT        NUMTRANSADIANTFOR NUMBER(10,0)                                                          Número de transação de adiantamento de fornecedor            OPERACIONAL                        NaN
PCFINANC3LANCADIANT        CODCONTAADIANTFOR NUMBER(10,0)                                 Conta definida para lançamentos de adiantamento a fornecedor na rotina 132            OPERACIONAL                        NaN
PCFINANC3LANCADIANT  CODCONTAADIANTFOROUTROS NUMBER(10,0)                        Conta definida para lançamentos de adiantamento a outros fornecedores na rotina 132            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                 VALORDEV NUMBER(24,8)                                 Valor de devolução da nota do título\tValor de devolução da nota do título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                   TXPERM NUMBER(14,2)                                         Valor da taxa de juros do título\tValor da taxa de juros do título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT              DESCONTOFIN  NUMBER(8,0)                                 Valor de desconto aplicado ao título\tValor de desconto aplicado ao título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT               NUMBORDERO  NUMBER(6,0)                                                   Número de borderô do título\tNúmero de borderô do título            OPERACIONAL                        NaN
PCFINANC3LANCADIANT             VPAGOBORDERO NUMBER(14,2)                                                               Valor pago no borderô\tValor pago no borderô            OPERACIONAL                        NaN
PCFINANC3LANCADIANT             INVESTIMENTO  VARCHAR2(1) Identifica se conta do lançamento é ou não de investimento\tIdentifica se o fornecedor é ou não cadastrado            OPERACIONAL                        NaN
PCFINANC3LANCADIANT                CODROTINA VARCHAR2(40)                                                                       Código da rotina que lançou o título            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*