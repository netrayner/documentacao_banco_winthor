# 📊 Tabela: PCECOMMERCEUNILEVER

### Estrutura de Colunas e Restrições

             Tabela                Coluna  Tipo/Tamanho                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEUNILEVER             CODFILIAL   VARCHAR2(2)                                          Código da filial que trabalha com o E-Commerce    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEUNILEVER           HOMOLOGACAO   VARCHAR2(1)                                Define se o sistema irá rodar em homologação ou produção            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER             MATRICULA   NUMBER(8,0)                            Matricula do usuário responsável pela inserção dos registros            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER               CODUSUR   NUMBER(4,0)                                                       Código de RCA para novos clientes            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER              CODPRACA   NUMBER(4,0)                                                     Código de praça para novos clientes            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER              CODATIVI   NUMBER(4,0)                                                             Código de ramo de atividade            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER      CODCONTABCLIENTE  VARCHAR2(12)                                                                Código da conta contábil            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER     HOMOLOGAWSDLPRECO VARCHAR2(200)                                                       Endereço WSDL do serviço de preço            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER   HOMOLOGAWSDLESTOQUE VARCHAR2(200)                                                     Endereço WSDL do serviço de estoque            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER    HOMOLOGAWSDLLIMITE VARCHAR2(200)                                           Endereço WSDL do serviço de limite de crédito            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER   HOMOLOGAWSDLCLIENTE VARCHAR2(200)                                                     Endereço WSDL do serviço de cliente            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER   HOMOLOGAWSDLPOSICAO VARCHAR2(200)                                           Endereço WSDL do serviço de posição de pedido            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER       HOMOLOGAUSUARIO  VARCHAR2(50)                                 Usuário de conexão aos WSDL de serviço do InfraCommerce            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         HOMOLOGASENHA  VARCHAR2(50)                                                               Senha do usuário dos WSDL            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER     PRODUCAOWSDLPRECO VARCHAR2(200)                                                       Endereço WSDL do serviço de preço            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER   PRODUCAOWSDLESTOQUE VARCHAR2(200)                                                     Endereço WSDL do serviço de estoque            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER    PRODUCAOWSDLLIMITE VARCHAR2(200)                                           Endereço WSDL do serviço de limite de crédito            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER   PRODUCAOWSDLCLIENTE VARCHAR2(200)                                                     Endereço WSDL do serviço de cliente            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER   PRODUCAOWSDLPOSICAO VARCHAR2(200)                                           Endereço WSDL do serviço de posição de pedido            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER       PRODUCAOUSUARIO  VARCHAR2(50)                                 Usuário de conexão aos WSDL de serviço do InfraCommerce            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         PRODUCAOSENHA  VARCHAR2(50)                                                               Senha do usuário dos WSDL            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER             NUMREGIAO   NUMBER(4,0) Numero da região para obter o preço de venda, caso NULL pegar a região padrão da filial            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER        NUMDIASESTOQUE   NUMBER(4,0)                    Número de dias com base no giro dia para dizer se tem ou não estoque            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER            PRCESTOQUE  NUMBER(12,4)                               Percentual de estoque necessário para dizer se tem ou não            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER      NUMTABELA_AVISTA   NUMBER(1,0)                                              Número da tabela de preço de venda a vista            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER      NUMTABELA_07DIAS   NUMBER(1,0)                                         Número da tabela de preço de venda para 07 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER      NUMTABELA_14DIAS   NUMBER(1,0)                                         Número da tabela de preço de venda para 14 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER      NUMTABELA_21DIAS   NUMBER(1,0)                                         Número da tabela de preço de venda para 21 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER      NUMTABELA_28DIAS   NUMBER(1,0)                                         Número da tabela de preço de venda para 28 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER      NUMTABELA_CARTAO   NUMBER(1,0)                                          Número da tabela de preço de venda para cartão            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER       CODPLPAG_AVISTA   NUMBER(6,0)                                                    Código do plano de pagamento a vista            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER       CODPLPAG_07DIAS   NUMBER(6,0)                                               Código do plano de pagamento para 07 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER       CODPLPAG_14DIAS   NUMBER(6,0)                                               Código do plano de pagamento para 14 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER       CODPLPAG_21DIAS   NUMBER(6,0)                                               Código do plano de pagamento para 21 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER       CODPLPAG_28DIAS   NUMBER(6,0)                                               Código do plano de pagamento para 28 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER       CODPLPAG_CARTAO   NUMBER(6,0)                                                Código do plano de pagamento para cartão            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER        CODPLPAG_TROCA   NUMBER(6,0)                                                 Código do plano de pagamento para troca            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         CODCOB_AVISTA   VARCHAR2(4)                                                              Coidgo da cobrança a vista            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         CODCOB_07DIAS   VARCHAR2(4)                                                         Coidgo da cobrança para 07 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         CODCOB_14DIAS   VARCHAR2(4)                                                         Coidgo da cobrança para 14 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         CODCOB_21DIAS   VARCHAR2(4)                                                         Coidgo da cobrança para 21 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         CODCOB_28DIAS   VARCHAR2(4)                                                         Coidgo da cobrança para 28 dias            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         CODCOB_CARTAO   VARCHAR2(4)                                                          Coidgo da cobrança para cartão            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER          CODCOB_TROCA   VARCHAR2(4)                                                           Coidgo da cobrança para troca            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER CODMOTBLOQUEIO_AVISTA   NUMBER(6,0)                      Coidgo do motivo de desbloqueio para pagamento autorizado - boleto            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER CODMOTBLOQUEIO_CARTAO   NUMBER(6,0)                      Coidgo do motivo de desbloqueio para pagamento autorizado - cartão            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER            DTINCLUSAO          DATE                                                            Data de inclusão do registro            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER           DTALTERACAO          DATE                                                           Data de alteração do registro            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         CODUSUARIOINC   NUMBER(8,0)                                                           Código do usuário que incluiu            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         CODUSUARIOALT   NUMBER(8,0)                                                           Código do usuário que alterou            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER                 SENHA  VARCHAR2(15)                                                                     Senha do webservice            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER        CODFILIALPRINC   VARCHAR2(2)                                                              Código da filial principal            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER  CODPLPAG_BONIFICACAO   NUMBER(6,0)                                                     Plano de pagamento para bonificação CHAVE ESTRANGEIRA (FK)                    PCPLPAG
PCECOMMERCEUNILEVER    CODCOB_BONIFICACAO   VARCHAR2(4)                                                               Cobrança para bonificação CHAVE ESTRANGEIRA (FK)                      PCCOB
PCECOMMERCEUNILEVER       PRODUTO_DISTRIB   VARCHAR2(1)                                                                Produto por distribuição            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER            CODDISTRIB   VARCHAR2(4)                                                                            Distribuição            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER         INTERMEDIADOR  VARCHAR2(60)                                                              Descrição do Intermediador            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER    CNPJ_INTERMEDIADOR  VARCHAR2(14)                                                                   CNPJ do Intermediador            OPERACIONAL                        NaN
PCECOMMERCEUNILEVER           USAFILIALNF   VARCHAR2(1)                                                            Utiliza Filial NF do Cliente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*