# 📊 Tabela: PCPIXCOBRANCADADOS

### Estrutura de Colunas e Restrições

            Tabela             Coluna   Tipo/Tamanho                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPIXCOBRANCADADOS             FILIAL    VARCHAR2(2)                                                         Código da filial            OPERACIONAL                        NaN
PCPIXCOBRANCADADOS               LINK  VARCHAR2(250)                                         URL do endereço do QRCODE gerado            OPERACIONAL                        NaN
PCPIXCOBRANCADADOS             QRCODE VARCHAR2(4000)                                                QRCODE retornado pela API            OPERACIONAL                        NaN
PCPIXCOBRANCADADOS NUMTRANSPAGDIGITAL  VARCHAR2(100)                   Número da transação digital retornada pelo API do PIX     CHAVE PRIMÁRIA (PK)                        NaN
PCPIXCOBRANCADADOS         VENCIMENTO   TIMESTAMP(6)                                            Data de vencimento do título             OPERACIONAL                        NaN
PCPIXCOBRANCADADOS          DESCRICAO VARCHAR2(4000)                                         Descrição das informações do PIX            OPERACIONAL                        NaN
PCPIXCOBRANCADADOS      NUMTRANSVENDA   VARCHAR2(30)                 Número da transação do título a receber vinculado ao PIX            OPERACIONAL                        NaN
PCPIXCOBRANCADADOS              PREST    VARCHAR2(2)                           Número da prestação do título vinculado ao PIX            OPERACIONAL                        NaN
PCPIXCOBRANCADADOS              JUROS   NUMBER(10,2)                                            Juros vinculado ao Pix gerado            OPERACIONAL                        NaN
PCPIXCOBRANCADADOS      EMAIL_ENVIADO    VARCHAR2(1) Informação se o email foi ou não enviado com os dados da cobrança do PIX            OPERACIONAL                        NaN
PCPIXCOBRANCADADOS          EXPIRACAO   TIMESTAMP(6)                                             Data de expiração do título             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*