# 📊 Tabela: PCFINANC3LANCOUTROS

### Estrutura de Colunas e Restrições

             Tabela           Coluna Tipo/Tamanho                                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFINANC3LANCOUTROS   DATAREFERENCIA         DATE                                   Data de referencia dos dados (data)\tData de referencia dos dados (data)    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCOUTROS      DATAGERACAO         DATE                               Data de geração dos dados (data/hora)\tData de geração dos dados (data/hora)            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS CODROTINAGERACAO  NUMBER(4,0)                                   Códido da rotina que gerou os dados\tCódido da rotina que gerou os dados    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCOUTROS        CODFILIAL  VARCHAR2(2)                                                     Código da filial do título\tCódigo da filial do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCOUTROS         TIPODADO VARCHAR2(10)                               Tipo de dado gerado como na PCFINANC2\tTipo de dado gerado como na PCFINANC2    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCOUTROS           RECNUM  NUMBER(8,0)                                             Número de lançamento do título\tNúmero de lançamento do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCOUTROS      RECNUMPRINC  NUMBER(8,0)                         Número de lançamento principal do título\tNúmero de lançamento principal do título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS           DTLANC         DATE             Data de lançamento do título no sistema (data)\tData de lançamento do título no sistema (data)            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS         CODGRUPO  NUMBER(4,0)                                     Código do grupo da conta do título\tCódigo do grupo da conta do título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS         CODCONTA NUMBER(10,0)                                                       Código da conta do título\tCódigo da conta do título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS        CODFORNEC  NUMBER(8,0)                             Código do parceiro vinculado ao título\tCódigo do parceiro vinculado ao título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS          NUMNOTA NUMBER(10,0)               Número da nota de entrada vinculada ao título\tNúmero da nota de entrada vinculada ao título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS           DUPLIC  VARCHAR2(1)                               Número da duplicata (parcela) a pagar\tNúmero da duplicata (parcela) a pagar            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS            VALOR NUMBER(24,8)                                                                           Valor do título\tValor do título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS           DTVENC         DATE                                   Data de vencimento do título (data)\tData de vencimento do título (data)            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS            VPAGO NUMBER(24,8)                                                 Valor que foi pago no título\tValor que foi pago no título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS          DTPAGTO         DATE                                     Data de pagamento do título (data)\tData de pagamento do título (data)            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS     TIPOPARCEIRO  VARCHAR2(1)                                 Tipo do parceiro vinculado ao título\tTipo do parceiro vinculado ao título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS           DTDESD         DATE                             Data de desdobramento do título (data)\tData de desdobramento do título (data)            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS         VALORDEV NUMBER(24,8)                                 Valor de devolução da nota do título\tValor de devolução da nota do título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS           TXPERM NUMBER(14,2)                                         Valor da taxa de juros do título\tValor da taxa de juros do título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS      DESCONTOFIN  NUMBER(8,0)                                 Valor de desconto aplicado ao título\tValor de desconto aplicado ao título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS       NUMBORDERO  NUMBER(6,0)                                                   Número de borderô do título\tNúmero de borderô do título            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS     VPAGOBORDERO NUMBER(14,2)                                                               Valor pago no borderô\tValor pago no borderô            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS     INVESTIMENTO  VARCHAR2(1) Identifica se conta do lançamento é ou não de investimento\tIdentifica se o fornecedor é ou não cadastrado            OPERACIONAL                        NaN
PCFINANC3LANCOUTROS        CODROTINA VARCHAR2(40)                                                                       Código da rotina que lançou o título            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*