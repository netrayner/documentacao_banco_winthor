# 📊 Tabela: PCALIENACLIENTE

### Estrutura de Colunas e Restrições

         Tabela          Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCALIENACLIENTE          CODCLI  NUMBER(6,0)                                 Código do cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCALIENACLIENTE       CODFILIAL  VARCHAR2(2)                                 Código da fililal            OPERACIONAL                        NaN
PCALIENACLIENTE         CODUSUR  NUMBER(4,0)                                Código do vendedor            OPERACIONAL                        NaN
PCALIENACLIENTE          CODCOB  VARCHAR2(4)                                Código da cobrança            OPERACIONAL                        NaN
PCALIENACLIENTE        CODPLPAG  NUMBER(4,0)                      Código do plano de pagamento            OPERACIONAL                        NaN
PCALIENACLIENTE          PRAZO1  NUMBER(4,0)                               Prazo da parcela 01            OPERACIONAL                        NaN
PCALIENACLIENTE          PRAZO2  NUMBER(4,0)                               Prazo da parcela 02            OPERACIONAL                        NaN
PCALIENACLIENTE          PRAZO3  NUMBER(4,0)                               Prazo da parcela 03            OPERACIONAL                        NaN
PCALIENACLIENTE          PRAZO4  NUMBER(4,0)                               Prazo da parcela 04            OPERACIONAL                        NaN
PCALIENACLIENTE          PRAZO5  NUMBER(4,0)                               Prazo da parcela 05            OPERACIONAL                        NaN
PCALIENACLIENTE          PRAZO6  NUMBER(4,0)                               Prazo da parcela 06            OPERACIONAL                        NaN
PCALIENACLIENTE          PRAZO7  NUMBER(4,0)                               Prazo da parcela 07            OPERACIONAL                        NaN
PCALIENACLIENTE          PRAZO8  NUMBER(4,0)                               Prazo da parcela 08            OPERACIONAL                        NaN
PCALIENACLIENTE          PRAZO9  NUMBER(4,0)                               Prazo da parcela 09            OPERACIONAL                        NaN
PCALIENACLIENTE         PRAZO10  NUMBER(4,0)                               Prazo da parcela 10            OPERACIONAL                        NaN
PCALIENACLIENTE         PRAZO11  NUMBER(4,0)                               Prazo da parcela 11            OPERACIONAL                        NaN
PCALIENACLIENTE         PRAZO12  NUMBER(4,0)                               Prazo da parcela 12            OPERACIONAL                        NaN
PCALIENACLIENTE       DTENTREGA  NUMBER(8,0)                    Período para Entrega (em dias)            OPERACIONAL                        NaN
PCALIENACLIENTE        DTFATURA  NUMBER(8,0)                Período para Faturamento (em dias)            OPERACIONAL                        NaN
PCALIENACLIENTE       CODTRANSP  NUMBER(6,0)                          Código da Transportadora            OPERACIONAL                        NaN
PCALIENACLIENTE           PRECO  VARCHAR2(2)                            Preço de Venda (A / T)            OPERACIONAL                        NaN
PCALIENACLIENTE IMPMENORUNIDADE  VARCHAR2(1) Importar pedido na menor unidade de venda (S / N)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*