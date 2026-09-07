# 📊 Tabela: PCMANIFESTOELETRONICOPGTO

### Estrutura de Colunas e Restrições

                   Tabela          Coluna Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFESTOELETRONICOPGTO    NUMTRANSACAO NUMBER(10,0)                                                        Transação do MDF-e    CHAVE PRIMÁRIA (PK)                        NaN
PCMANIFESTOELETRONICOPGTO    NOMERESPPGTO VARCHAR2(60)                                          Nome do responsável do pagamento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTO CNPJCPFRESPPGTO VARCHAR2(20)                                      CNPJ/CPF do responsável do pagamento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTO        CODBANCO  VARCHAR2(5)                                                           Código do banco            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTO      CODAGENCIA VARCHAR2(10)                                                         Código da agência            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTO        CNPJIPEF VARCHAR2(14)            Número do CNPJ da Instituição de pagamento Eletrônico do Frete            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTO       NUMEVENTO NUMBER(10,0)                                               Número sequencial do evento    CHAVE PRIMÁRIA (PK)                        NaN
PCMANIFESTOELETRONICOPGTO      VLCONTRATO NUMBER(18,6)                                                   Valor total do contrato            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTO          INDPAG  NUMBER(1,0)                                           Indicador da Forma de Pagamento            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTO   TIPOPAGAMENTO  VARCHAR2(1) Tipo da forma de pagamento do frete (1=AGENCIA/ CONTA, 2=CNPJIPEF, 3=PIX)            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTO        CHAVEPIX VARCHAR2(60)                            Informar a chave PIX para recebimento do frete            OPERACIONAL                        NaN
PCMANIFESTOELETRONICOPGTO  VLADIANTAMENTO NUMBER(13,2)                                       Valor do adiantamento do pagamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*