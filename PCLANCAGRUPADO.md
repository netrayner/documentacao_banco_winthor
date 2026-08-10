# 📊 Tabela: PCLANCAGRUPADO

### Estrutura de Colunas e Restrições

        Tabela                Coluna  Tipo/Tamanho                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLANCAGRUPADO        CODAGRUPAMENTO  NUMBER(10,0)                                                           Código do Agrupamento    CHAVE PRIMÁRIA (PK)                        NaN
PCLANCAGRUPADO             CODFILIAL   VARCHAR2(2)                                                                Código da Filial            OPERACIONAL                        NaN
PCLANCAGRUPADO                DTLANC          DATE                                                              Data do Lançamento            OPERACIONAL                        NaN
PCLANCAGRUPADO          TIPOPARCEIRO   VARCHAR2(1)                                              Tipo do Parceiro do Contas á Pagar            OPERACIONAL                        NaN
PCLANCAGRUPADO           CODPARCEIRO   NUMBER(9,0)                                            Código do Parceiro do Contas á Pagar            OPERACIONAL                        NaN
PCLANCAGRUPADO              PARCEIRO  VARCHAR2(60)                                                                Nome do Parceiro            OPERACIONAL                        NaN
PCLANCAGRUPADO                 VALOR  NUMBER(12,2)                                                                 Valor do Título            OPERACIONAL                        NaN
PCLANCAGRUPADO                BOLETO   VARCHAR2(1)                                                         Se esse Título é Boleto            OPERACIONAL                        NaN
PCLANCAGRUPADO            FORMAPAGTO   VARCHAR2(4)                                                              Forma de Pagamento            OPERACIONAL                        NaN
PCLANCAGRUPADO           TIPOSERVICO   VARCHAR2(2)                                                                 Tipo do Serviço            OPERACIONAL                        NaN
PCLANCAGRUPADO           CODCOBSEFAZ   VARCHAR2(4)                               Código da Cobrança no SEFAZ - Regra no Fornecedor            OPERACIONAL                        NaN
PCLANCAGRUPADO        LINHADIGITAVEL  VARCHAR2(70)                                                       Linha Digitável do Título            OPERACIONAL                        NaN
PCLANCAGRUPADO           CODIGOBARRA  VARCHAR2(44)                                                      Código de Barras do Título            OPERACIONAL                        NaN
PCLANCAGRUPADO       CODTIPOCHAVEPIX   VARCHAR2(2)                                                     Código do Tipo da Chave PIX            OPERACIONAL                        NaN
PCLANCAGRUPADO          TIPOCHAVEPIX  VARCHAR2(20)                             Descrição da Chave PIX, Conforme o Código Escolhido            OPERACIONAL                        NaN
PCLANCAGRUPADO              CHAVEPIX VARCHAR2(100)                                                                    Chave do PIX            OPERACIONAL                        NaN
PCLANCAGRUPADO             QRCODEPIX VARCHAR2(500)                                                                   QRCODE do PIX            OPERACIONAL                        NaN
PCLANCAGRUPADO      NUMBCODESTTRANSF   NUMBER(4,0)                                       Número do Banco para Transferência ou TED            OPERACIONAL                        NaN
PCLANCAGRUPADO       NUMAGDESTTRANSF   NUMBER(6,0)                                     Número da Agência para Transferência ou TED            OPERACIONAL                        NaN
PCLANCAGRUPADO       NUMCCDESTTRANSF  NUMBER(12,0)                              Número da Conta Corrente para Transferência ou TED            OPERACIONAL                        NaN
PCLANCAGRUPADO       NUMDVDESTTRANSF   VARCHAR2(2)                  Dígito Verificador da Conta Corrente para Transferência ou TED            OPERACIONAL                        NaN
PCLANCAGRUPADO                DTVENC          DATE                                                    Data de Vencimento do Título            OPERACIONAL                        NaN
PCLANCAGRUPADO               DTBAIXA          DATE                                                         Data de Baixa de Título            OPERACIONAL                        NaN
PCLANCAGRUPADO        DTESTORNOBAIXA          DATE                                                        Data de Estorno da Baixa            OPERACIONAL                        NaN
PCLANCAGRUPADO         DTCOMPETENCIA          DATE                                                Data de Competência do Pagamento            OPERACIONAL                        NaN
PCLANCAGRUPADO       CODFUNCINCLUSAO   NUMBER(8,0)                                      Código do Funcionário que Incluiu o Título            OPERACIONAL                        NaN
PCLANCAGRUPADO   CODFUNCULTALTERACAO   NUMBER(8,0)                                  Código do Funcionário que fez última Alteração            OPERACIONAL                        NaN
PCLANCAGRUPADO          CODFUNCBAIXA   NUMBER(8,0)                                      Código do Funcionário que Executou a Baixa            OPERACIONAL                        NaN
PCLANCAGRUPADO   CODFUNCESTORNOBAIXA   NUMBER(8,0)                           Código do Funcionário que Executou o Estorno da Baixa            OPERACIONAL                        NaN
PCLANCAGRUPADO     CODROTINAINCLUSAO  VARCHAR2(40)                                           Código da Rotina que Incluiu o Título            OPERACIONAL                        NaN
PCLANCAGRUPADO        CODROTINABAIXA  VARCHAR2(40)                                            Código da Rotina que Baixou o Título            OPERACIONAL                        NaN
PCLANCAGRUPADO CODROTINAULTALTERACAO  VARCHAR2(40)                                     Código da Rotina que fez a Última Alteração            OPERACIONAL                        NaN
PCLANCAGRUPADO              DTCANCEL          DATE                                             Data de Cancelamento do Agrupamento            OPERACIONAL                        NaN
PCLANCAGRUPADO         CODFUNCCANCEL   NUMBER(8,0)                                Código do Funcionário que Cancelou o Agrupamento            OPERACIONAL                        NaN
PCLANCAGRUPADO            NUMBORDERO   NUMBER(6,0)                                                               Número do Borderô            OPERACIONAL                        NaN
PCLANCAGRUPADO              DTBORDER          DATE                                                     Data da Inclusão em Borderô            OPERACIONAL                        NaN
PCLANCAGRUPADO          VPAGOBORDERO  NUMBER(14,2)                                                           Valor Pago no Borderô            OPERACIONAL                        NaN
PCLANCAGRUPADO                 VPAGO  NUMBER(12,2)                                                                      Valor Pago            OPERACIONAL                        NaN
PCLANCAGRUPADO         NUMSEQBORDERO   NUMBER(6,0)                                                     Sequência Dentro do Borderô            OPERACIONAL                        NaN
PCLANCAGRUPADO             NUMCHEQUE  VARCHAR2(20)                                                 Número do Cheque para Pagamento            OPERACIONAL                        NaN
PCLANCAGRUPADO                DTCHEQ          DATE                                                      Data da Inclusão em Cheque            OPERACIONAL                        NaN
PCLANCAGRUPADO        PORTADORCHEQUE  VARCHAR2(40)                                                              Portador do Cheque            OPERACIONAL                        NaN
PCLANCAGRUPADO              NUMBANCO   NUMBER(4,0)                                                Número do Banco onde foi Baixado            OPERACIONAL                        NaN
PCLANCAGRUPADO              TIPOLANC   VARCHAR2(1)                         Tipo do Lançamento - Confirmado (C) ou Provisionado (P)            OPERACIONAL                        NaN
PCLANCAGRUPADO          AUTENTICACAO  VARCHAR2(64)                             Autenticação Enviada pelo Banco no ato do Pagamento            OPERACIONAL                        NaN
PCLANCAGRUPADO            ASSINATURA  VARCHAR2(40)                                         Usuário que Assinou o Cheque ou Borderô            OPERACIONAL                        NaN
PCLANCAGRUPADO          DTASSINATURA          DATE                                                              Data da Assinatura            OPERACIONAL                        NaN
PCLANCAGRUPADO                 MOEDA   VARCHAR2(1)                                                     Moeda que foi feito a Baixa            OPERACIONAL                        NaN
PCLANCAGRUPADO           AGENDAMENTO   VARCHAR2(1)                                                 Se é Pagamento Borderô Agendado            OPERACIONAL                        NaN
PCLANCAGRUPADO         DTAGENDAMENTO          DATE                                   Data de Agrupamento para Pagamento do Borderô            OPERACIONAL                        NaN
PCLANCAGRUPADO           DTIMPRESSAO          DATE                                           Data de Impressão do Borderô / Cheque            OPERACIONAL                        NaN
PCLANCAGRUPADO             HISTORICO VARCHAR2(200)                                                         Histórico do lançamento            OPERACIONAL                        NaN
PCLANCAGRUPADO             NFSERVICO   VARCHAR2(1) Campo para indicar se o título gerado é referente a uma nota fiscal de serviço.            OPERACIONAL                        NaN
PCLANCAGRUPADO        NUMNOTASERVICO  VARCHAR2(60)                                                      Número da nota de serviço             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*