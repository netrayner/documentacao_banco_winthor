# 📊 Tabela: PCFINANC3PREST

### Estrutura de Colunas e Restrições

        Tabela           Coluna Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFINANC3PREST   DATAREFERENCIA         DATE                                                          Data de referencia dos dados (data)    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3PREST      DATAGERACAO         DATE                 Data de geração dos dados (data/hora)\tData de geração dos dados (data/hora)            OPERACIONAL                        NaN
PCFINANC3PREST CODROTINAGERACAO  NUMBER(4,0)                     Códido da rotina que gerou os dados\tCódido da rotina que gerou os dados    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3PREST         TIPODADO VARCHAR2(10)                 Tipo de dado gerado como na PCFINANC2\tTipo de dado gerado como na PCFINANC2    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3PREST        CODROTINA  NUMBER(4,0)                   Código da rotina que lançou o título\tCódigo da rotina que lançou o título            OPERACIONAL                        NaN
PCFINANC3PREST        CODFILIAL  VARCHAR2(2)                                       Código da filial do título\tCódigo da filial do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3PREST    NUMTRANSVENDA NUMBER(10,0)               Número de transação de venda do título\tNúmero de transação de venda do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3PREST           DUPLIC NUMBER(10,0)                         Número da nota de venda do título\tNúmero da nota de venda do título            OPERACIONAL                        NaN
PCFINANC3PREST            PREST  VARCHAR2(2)                                 Prestação (parcela) do título\tPrestação (parcela) do título    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC3PREST            VALOR NUMBER(24,8)                                                             Valor do título\tValor do título            OPERACIONAL                        NaN
PCFINANC3PREST           CODCOB  VARCHAR2(4)                                   Código da cobrança do título\tCódigo da cobrança do título            OPERACIONAL                        NaN
PCFINANC3PREST           DTVENC         DATE                   Data de venciamento do título (data)\tData de venciamento do título (data)            OPERACIONAL                        NaN
PCFINANC3PREST            DTPAG         DATE                       Data de pagamento do título (data)\tData de pagamento do título (data)            OPERACIONAL                        NaN
PCFINANC3PREST            VPAGO NUMBER(24,8)                                   Valor que foi pago no título\tValor que foi pago no título            OPERACIONAL                        NaN
PCFINANC3PREST           TXPERM NUMBER(10,2)                           Valor da taxa de juros do título\tValor da taxa de juros do título            OPERACIONAL                        NaN
PCFINANC3PREST        DTEMISSAO         DATE                           Data de emissão do título (data)\tData de emissão do título (data)            OPERACIONAL                        NaN
PCFINANC3PREST        VALORDESC NUMBER(24,8)                   Valor de desconto aplicado no título\tValor de desconto aplicado no título            OPERACIONAL                        NaN
PCFINANC3PREST           DTDESD         DATE               Data de desdobramento do título (data)\tData de desdobramento do título (data)            OPERACIONAL                        NaN
PCFINANC3PREST          DTBAIXA         DATE                               Data de baixa do título (data)\tData de baixa do título (data)            OPERACIONAL                        NaN
PCFINANC3PREST         DTCANCEL         DATE                 Data de cancelamento do título (data)\tData de cancelamento do título (data)            OPERACIONAL                        NaN
PCFINANC3PREST          DTFECHA         DATE                     Data de fechamento do título (data)\tData de fechamento do título (data)            OPERACIONAL                        NaN
PCFINANC3PREST         NUMTRANS  NUMBER(8,0)                     Número de transação de movimentação\tNúmero de transação de movimentação            OPERACIONAL                        NaN
PCFINANC3PREST          DTDEVOL         DATE       Data de devolução da nota do título (data)\tData de devolução da nota do título (data)            OPERACIONAL                        NaN
PCFINANC3PREST          VLDEVOL NUMBER(24,8)                   Valor de devolução da nota do título\tValor de devolução da nota do título            OPERACIONAL                        NaN
PCFINANC3PREST        DTESTORNO         DATE Data de estorno de pagamento do título (data)\tData de estorno de pagamento do título (data)            OPERACIONAL                        NaN
PCFINANC3PREST       VALORMULTA NUMBER(24,8)                         Valor de multa aplicada no título\tValor de multa aplicada no título            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*