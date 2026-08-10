# 📊 Tabela: PCREJEICAOSEFAZ

### Estrutura de Colunas e Restrições

         Tabela            Coluna   Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREJEICAOSEFAZ          DATAHORA           DATE                                          Data Hora gravação            OPERACIONAL                        NaN
PCREJEICAOSEFAZ       TIPOEMISSAO    NUMBER(2,0) Tipo de emissao do documento fiscal Produção ou Homologação            OPERACIONAL                        NaN
PCREJEICAOSEFAZ     TIPODOCFISCAL   VARCHAR2(20)                            Tipo de documento fiscal emitido            OPERACIONAL                        NaN
PCREJEICAOSEFAZ          NUMCAIXA    NUMBER(4,0)                                             Número do caixa            OPERACIONAL                        NaN
PCREJEICAOSEFAZ    NUMCAIXAFISCAL    NUMBER(4,0)                                      Número do caixa fiscal            OPERACIONAL                        NaN
PCREJEICAOSEFAZ              DATA           DATE                                   Data de emissão documento            OPERACIONAL                        NaN
PCREJEICAOSEFAZ         NUMPEDECF   NUMBER(10,0)                                   Numero do pedido de venda            OPERACIONAL                        NaN
PCREJEICAOSEFAZ       MSGREJEICAO VARCHAR2(4000)                               Mensagem de rejeição resumida            OPERACIONAL                        NaN
PCREJEICAOSEFAZ      MSGREJEICAO2           CLOB                               Mensagem de rejeição completa            OPERACIONAL                        NaN
PCREJEICAOSEFAZ         CODFUNCCX    NUMBER(8,0)                                 Código do operador de caixa            OPERACIONAL                        NaN
PCREJEICAOSEFAZ         EXPORTADO    VARCHAR2(1)     indica que o registro já foi enviado para o faturamento            OPERACIONAL                        NaN
PCREJEICAOSEFAZ NUMPEDECFAUXILIAR   NUMBER(10,0)                                        Sequencial da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCREJEICAOSEFAZ       CODREJEICAO   NUMBER(10,0)                                          Código da rejaição            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*