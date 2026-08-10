# 📊 Tabela: PCCADGIFTCARD

### Estrutura de Colunas e Restrições

       Tabela            Coluna  Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCADGIFTCARD       NUMGIFTCARD  NUMBER(25,0)                                Número do cartão de presente (giftcard).    CHAVE PRIMÁRIA (PK)                        NaN
PCCADGIFTCARD            CODCLI   NUMBER(6,0)                     Código do cliente do cartão de presente (giftcard).            OPERACIONAL                        NaN
PCCADGIFTCARD        DTVALIDADE          DATE                  Data limite de validade do cartão. Data de vencimento.            OPERACIONAL                        NaN
PCCADGIFTCARD         DTINATIVO          DATE                                           Data de inativação do cartão.            OPERACIONAL                        NaN
PCCADGIFTCARD     MOTIVOINATIVO VARCHAR2(100)                                         Motivo da inativação do cartão.            OPERACIONAL                        NaN
PCCADGIFTCARD      CODFUNCATIVO   NUMBER(8,0)                  Registra o código do operador que realizou a ativação.            OPERACIONAL                        NaN
PCCADGIFTCARD              FIXO   VARCHAR2(1)   Identificador de fixo/variável referente ao valor de venda do cartão.            OPERACIONAL                        NaN
PCCADGIFTCARD             VALOR  NUMBER(10,2)                                               Valor de venda do cartão.            OPERACIONAL                        NaN
PCCADGIFTCARD            STATUS   VARCHAR2(1)                    Status do cartão: (A)TIVO,(I)NATIVO ou (D)ISPONÍVEL.            OPERACIONAL                        NaN
PCCADGIFTCARD        DTCADASTRO          DATE                                    Data em que o cartão foi cadastrado.            OPERACIONAL                        NaN
PCCADGIFTCARD   CONSUMIDORFINAL   VARCHAR2(1)     Identificador de tipo de consumidor, se é do tipo consumidor final.            OPERACIONAL                        NaN
PCCADGIFTCARD           DTATIVO          DATE                                     Data da Ativação do Cartão GIFTCARD            OPERACIONAL                        NaN
PCCADGIFTCARD CODCONTAGERENCIAL  NUMBER(10,0) Conta padrão para lançamento de premiação em Gift Card à colaboradores.            OPERACIONAL                        NaN
PCCADGIFTCARD               WEB   VARCHAR2(1)                                         Origem da gravação do Gift Card            OPERACIONAL                        NaN
PCCADGIFTCARD         NUMPEDHUB  VARCHAR2(50)                                             Identificador do pedido Web            OPERACIONAL                        NaN
PCCADGIFTCARD         DTALTERC5  TIMESTAMP(6)                                                       Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*