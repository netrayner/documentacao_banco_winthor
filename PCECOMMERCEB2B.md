# 📊 Tabela: PCECOMMERCEB2B

### Estrutura de Colunas e Restrições

        Tabela               Coluna Tipo/Tamanho                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEB2B            MATRICULA NUMBER(10,0)                   Matricula do usuário do irá gravar como emitente do pedido de venda.            OPERACIONAL                        NaN
PCECOMMERCEB2B            CODFILIAL  VARCHAR2(2)                                                                       Codigo da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2B       TIPOINTEGRACAO  NUMBER(4,0)                                                                     Tipo de integração    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2B            NUMREGIAO  NUMBER(4,0)                                                  Numero da regiao para tabela de preço            OPERACIONAL                        NaN
PCECOMMERCEB2B     NUMTABELA_AVISTA  NUMBER(1,0)                   Coluna da tabela de preço a ser utilizada com plano de pagto a vista            OPERACIONAL                        NaN
PCECOMMERCEB2B     NUMTABELA_07DIAS  NUMBER(1,0)  Coluna da tabela de preço a ser utilizada com plano de pagamento com prazo de 7 dias.            OPERACIONAL                        NaN
PCECOMMERCEB2B     NUMTABELA_14DIAS  NUMBER(1,0) Coluna da tabela de preço a ser utilizada com plano de pagamento com prazo de 14 dias.            OPERACIONAL                        NaN
PCECOMMERCEB2B     NUMTABELA_21DIAS  NUMBER(1,0) Coluna da tabela de preço a ser utilizada com plano de pagamento com prazo de 21 dias.            OPERACIONAL                        NaN
PCECOMMERCEB2B     NUMTABELA_28DIAS  NUMBER(1,0) Coluna da tabela de preço a ser utilizada com plano de pagamento com prazo de 28 dias.            OPERACIONAL                        NaN
PCECOMMERCEB2B     NUMTABELA_CARTAO  NUMBER(1,0)       Coluna da tabela de preço a ser utilizada quando a forma de pagamento for cartão            OPERACIONAL                        NaN
PCECOMMERCEB2B       NUMDIASESTOQUE  NUMBER(4,0)                                                                        Dias de estoque            OPERACIONAL                        NaN
PCECOMMERCEB2B           PRCESTOQUE NUMBER(12,4)                                Percentual de estoque a ser considerado para e-commerce            OPERACIONAL                        NaN
PCECOMMERCEB2B      PRODUTO_DISTRIB  VARCHAR2(1)                                                         Se o produto é de distribuição            OPERACIONAL                        NaN
PCECOMMERCEB2B           CODDISTRIB  VARCHAR2(4)                                                      Código da distribuição do produto            OPERACIONAL                        NaN
PCECOMMERCEB2B              CODUSUR  NUMBER(4,0)                                     Codigo do RCA a ser utilizado na integraçào do B2B            OPERACIONAL                        NaN
PCECOMMERCEB2B      CODPLPAG_AVISTA NUMBER(12,4)                                                   Codigo do plano de pagamento a vista            OPERACIONAL                        NaN
PCECOMMERCEB2B      CODPLPAG_07DIAS  NUMBER(6,0)                                                    Código do plano de pagamento 7 dias            OPERACIONAL                        NaN
PCECOMMERCEB2B      CODPLPAG_14DIAS  NUMBER(6,0)                                                   Código do plano de pagamento 14 dias            OPERACIONAL                        NaN
PCECOMMERCEB2B      CODPLPAG_21DIAS  NUMBER(6,0)                                                   Código do plano de pagamento 21 dias            OPERACIONAL                        NaN
PCECOMMERCEB2B      CODPLPAG_28DIAS  NUMBER(6,0)                                                   Código do plano de pagamento 28 dias            OPERACIONAL                        NaN
PCECOMMERCEB2B      CODPLPAG_CARTAO  NUMBER(6,0)                                               Código do plano de pagamento para cartão            OPERACIONAL                        NaN
PCECOMMERCEB2B       CODPLPAG_TROCA  NUMBER(6,0)                                                Código do palno de pagamento para troca            OPERACIONAL                        NaN
PCECOMMERCEB2B        CODCOB_AVISTA  VARCHAR2(4)                                                  Código de cobrança para venda a vista            OPERACIONAL                        NaN
PCECOMMERCEB2B        CODCOB_07DIAS  VARCHAR2(4)                                                   Código de cobrança para venda 7 dias            OPERACIONAL                        NaN
PCECOMMERCEB2B        CODCOB_14DIAS  VARCHAR2(4)                                                  Código de cobrança para venda 14 dias            OPERACIONAL                        NaN
PCECOMMERCEB2B        CODCOB_21DIAS  VARCHAR2(4)                                                  Código de cobrança para venda 21 dias            OPERACIONAL                        NaN
PCECOMMERCEB2B        CODCOB_28DIAS  VARCHAR2(4)                                                  Código de cobrança para venda 28 dias            OPERACIONAL                        NaN
PCECOMMERCEB2B        CODCOB_CARTAO  VARCHAR2(4)                                               Código de cobrança para venda com cartão            OPERACIONAL                        NaN
PCECOMMERCEB2B         CODCOB_TROCA  VARCHAR2(4)                                                          Código de cobrança para troca            OPERACIONAL                        NaN
PCECOMMERCEB2B CODPLPAG_BONIFICACAO  NUMBER(6,0)                                          Código do plano de pagamento para Bonificação            OPERACIONAL                        NaN
PCECOMMERCEB2B   CODCOB_BONIFICACAO  VARCHAR2(4)                                                    Código de cobrança para bonificação            OPERACIONAL                        NaN
PCECOMMERCEB2B             CODATIVI  NUMBER(4,0)                                           Código do ramos de atividade padrão para B2B            OPERACIONAL                        NaN
PCECOMMERCEB2B     CODCONTABCLIENTE VARCHAR2(12)                                                        Código da conta contábil padrão            OPERACIONAL                        NaN
PCECOMMERCEB2B             CODPRACA  NUMBER(4,0)                                                        Código da praça padrão para B2B            OPERACIONAL                        NaN
PCECOMMERCEB2B        INTERMEDIADOR VARCHAR2(60)                                                                Descrição Intermediador            OPERACIONAL                        NaN
PCECOMMERCEB2B   CNPJ_INTERMEDIADOR NUMBER(14,0)                                                                     CNPJ Intermediador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*