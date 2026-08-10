# 📊 Tabela: PCCLIENTCIASHOP

### Estrutura de Colunas e Restrições

         Tabela                    Coluna  Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIENTCIASHOP                 NUMPEDWEB  NUMBER(10,0)                                    Número do pedido Ciashop    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTCIASHOP                   CLIENTE  VARCHAR2(60)                                             Nome do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                 CODFILIAL   VARCHAR2(2)                                    Código da Filial Winthor    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTCIASHOP                    CGCENT  VARCHAR2(18)                                         CPF/CNPJ do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                  ENDERENT  VARCHAR2(40)                                         Endereço do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                 NUMEROENT   VARCHAR2(6)                               Número do endereço do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                 BAIRROENT  VARCHAR2(40)                                           Bairro do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                    TELENT  VARCHAR2(13)                                         Telefone do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                  MUNICENT  VARCHAR2(15)                                        Município do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                    ESTENT   VARCHAR2(2)                                               UF do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                    CEPENT   VARCHAR2(9)                                              CEP do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                     IEENT  VARCHAR2(15)                               Inscrição Estadual do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                     EMAIL VARCHAR2(100)                                            Email do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                       OBS VARCHAR2(100)                                      Observações do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP               NOMECONTATO  VARCHAR2(40)                                  Nome do contato do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP           TELEFONECONTATO  VARCHAR2(13)                              Telefone do contato do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                OBSCONTATO  VARCHAR2(75)                           Observações do contato do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                 CODCIDADE   NUMBER(6,0)                                 Código da cidade do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                        RG  VARCHAR2(20)                          Número do RG do contato do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP                    DTNASC          DATE                    Data de nascimento do contato do cliente            OPERACIONAL                        NaN
PCCLIENTCIASHOP IDENTIFICACAO_ESTRANGEIRO  VARCHAR2(20) Número do documento de identificação de contato estrangeiro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*