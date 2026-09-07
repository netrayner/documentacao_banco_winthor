# 📊 Tabela: PCFINANC3LANCFORNEC

### Estrutura de Colunas e Restrições

             Tabela           Coluna Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFINANC3LANCFORNEC   DATAREFERENCIA         DATE                       Data de referencia dos dados (data)\tData de referencia dos dados (data)    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCFORNEC      DATAGERACAO         DATE                   Data de geração dos dados (data/hora)\tData de geração dos dados (data/hora)            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC CODROTINAGERACAO  NUMBER(4,0)                       Códido da rotina que gerou os dados\tCódido da rotina que gerou os dados    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCFORNEC        CODFILIAL  VARCHAR2(2)                                         Código da filial do título\tCódigo da filial do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCFORNEC         TIPODADO VARCHAR2(10)                   Tipo de dado gerado como na PCFINANC2\tTipo de dado gerado como na PCFINANC2    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCFORNEC           RECNUM  NUMBER(8,0)                                 Número de lançamento do título\tNúmero de lançamento do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCFORNEC      RECNUMPRINC  NUMBER(8,0)             Número de lançamento principal do título\tNúmero de lançamento principal do título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC           DTLANC         DATE Data de lançamento do título no sistema (data)\tData de lançamento do título no sistema (data)            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC         CODGRUPO  NUMBER(4,0)                         Código do grupo da conta do título\tCódigo do grupo da conta do título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC         CODCONTA NUMBER(10,0)                                           Código da conta do título\tCódigo da conta do título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC        CODFORNEC  NUMBER(8,0)                 Código do parceiro vinculado ao título\tCódigo do parceiro vinculado ao título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3LANCFORNEC          NUMNOTA NUMBER(10,0)   Número da nota de entrada vinculada ao título\tNúmero da nota de entrada vinculada ao título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC           DUPLIC  VARCHAR2(1)                   Número da duplicata (parcela) a pagar\tNúmero da duplicata (parcela) a pagar            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC            VALOR NUMBER(24,8)                                                               Valor do título\tValor do título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC           DTVENC         DATE                       Data de vencimento do título (data)\tData de vencimento do título (data)            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC            VPAGO NUMBER(24,8)                                     Valor que foi pago no título\tValor que foi pago no título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC          DTPAGTO         DATE                         Data de pagamento do título (data)\tData de pagamento do título (data)            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC     TIPOPARCEIRO  VARCHAR2(1)                     Tipo do parceiro vinculado ao título\tTipo do parceiro vinculado ao título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC           DTDESD         DATE                 Data de desdobramento do título (data)\tData de desdobramento do título (data)            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC         VALORDEV NUMBER(24,8)                     Valor de devolução da nota do título\tValor de devolução da nota do título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC           TXPERM NUMBER(14,2)                             Valor da taxa de juros do título\tValor da taxa de juros do título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC      DESCONTOFIN  NUMBER(8,0)                     Valor de desconto aplicado ao título\tValor de desconto aplicado ao título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC       NUMBORDERO  NUMBER(6,0)                                       Número de borderô do título\tNúmero de borderô do título            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC     VPAGOBORDERO NUMBER(14,2)                                                   Valor pago no borderô\tValor pago no borderô            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC       CADASTRADO  VARCHAR2(1) Identifica se o fornecedor é ou não cadastrado\tIdentifica se o fornecedor é ou não cadastrado            OPERACIONAL                        NaN
PCFINANC3LANCFORNEC        CODROTINA VARCHAR2(40)                                                           Código da rotina que lançou o título            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*