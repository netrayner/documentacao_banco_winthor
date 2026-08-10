# 📊 Tabela: PCINTEGRACAOTGI

### Estrutura de Colunas e Restrições

         Tabela                Coluna Tipo/Tamanho                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOTGI             CODFILIAL  VARCHAR2(2)                                 Código da filial integrada com TGI            OPERACIONAL                        NaN
PCINTEGRACAOTGI               USUARIO VARCHAR2(50)                        Nome de usuário utilizado para logar no TGI            OPERACIONAL                        NaN
PCINTEGRACAOTGI                 SENHA VARCHAR2(50)                                  Senha utilizada para logar no TGI            OPERACIONAL                        NaN
PCINTEGRACAOTGI            CODCLIENTE VARCHAR2(11)                                  Código do cliente que utiliza TGI            OPERACIONAL                        NaN
PCINTEGRACAOTGI         CODEMPRESAPCP  VARCHAR2(4)                                   Código da empresa no sistema PCP            OPERACIONAL                        NaN
PCINTEGRACAOTGI             NOTIFICAR  VARCHAR2(1) Indica se a empresa notifica e protesta ou se protesta diretamente            OPERACIONAL                        NaN
PCINTEGRACAOTGI            TXCOBRANCA  NUMBER(7,2)                      Informar a taxa de cobrança cadastrada no TGI            OPERACIONAL                        NaN
PCINTEGRACAOTGI              CODBANCO  NUMBER(4,0)                                         Código do banco da empresa            OPERACIONAL                        NaN
PCINTEGRACAOTGI               AGCONTA  VARCHAR2(9)                                                  Número da agência            OPERACIONAL                        NaN
PCINTEGRACAOTGI              CODCONTA VARCHAR2(11)                                                    Código da conta            OPERACIONAL                        NaN
PCINTEGRACAOTGI              CARTEIRA  VARCHAR2(5)                       Número da carteira da empresa junto ao banco            OPERACIONAL                        NaN
PCINTEGRACAOTGI           NUMCONVENIO NUMBER(10,0)                       Número do convênio da empresa junto ao banco            OPERACIONAL                        NaN
PCINTEGRACAOTGI               CODCONF VARCHAR2(11)                                              Código interno do TGI            OPERACIONAL                        NaN
PCINTEGRACAOTGI VLCARTORIONOTIFICACAO  NUMBER(7,2)                                   Valor da notificação no cartório            OPERACIONAL                        NaN
PCINTEGRACAOTGI          BASEPRODUCAO  VARCHAR2(1)                                      Tipo da base utilizada no Tgi            OPERACIONAL                        NaN
PCINTEGRACAOTGI          CODFILIALCOB  VARCHAR2(2)                                Código da filial de cobrança no Tgi            OPERACIONAL                        NaN
PCINTEGRACAOTGI                CODCOB  VARCHAR2(4)                                  Código da cobrança enviada ao TGI            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*