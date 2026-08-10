# 📊 Tabela: PCPOLITICAVERBACMV

### Estrutura de Colunas e Restrições

            Tabela              Coluna Tipo/Tamanho                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPOLITICAVERBACMV              CODIGO NUMBER(10,0) Código da política para aplicação e verba CMV, este campo será gerado automaticamente sequence).    CHAVE PRIMÁRIA (PK)                        NaN
PCPOLITICAVERBACMV              CODCLI NUMBER(10,0)                                                   Código do cliente para aplicação de verba CMV.            OPERACIONAL                        NaN
PCPOLITICAVERBACMV             CODEPTO  NUMBER(6,0)                                              Código do departamento para aplicação de verba CMV.            OPERACIONAL                        NaN
PCPOLITICAVERBACMV              CODSEC  NUMBER(6,0)                                                    Código da seção para aplicação de verba CMV.             OPERACIONAL                        NaN
PCPOLITICAVERBACMV             CODPROD  NUMBER(6,0)                                                  Código do produto para aplicação de verba CMV.             OPERACIONAL                        NaN
PCPOLITICAVERBACMV            DTINICIO         DATE                               Data de validade inicial da política para aplicação de verba CMV.             OPERACIONAL                        NaN
PCPOLITICAVERBACMV               DTFIM         DATE                                 Data de validade final da política para aplicação de verba CMV.             OPERACIONAL                        NaN
PCPOLITICAVERBACMV        PERCVERBACMV  NUMBER(8,4)                                      Percentual da verba CMV a ser aplicado no pedido de venda.             OPERACIONAL                        NaN
PCPOLITICAVERBACMV             CODREDE  NUMBER(4,0)                                                                       Código da rede de clientes            OPERACIONAL                        NaN
PCPOLITICAVERBACMV ALTERACONTACORRENTE  VARCHAR2(1)                                                                  Alterar o conta corrente do RCA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*