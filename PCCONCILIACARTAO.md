# 📊 Tabela: PCCONCILIACARTAO

### Estrutura de Colunas e Restrições

          Tabela            Coluna Tipo/Tamanho                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONCILIACARTAO            DUPLIC NUMBER(10,0)                                                   Campo para armazenar o número da duplicata.            OPERACIONAL                        NaN
PCCONCILIACARTAO             PREST  VARCHAR2(2)                                                Campo para armazenar a prestação da duplicata.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONCILIACARTAO         DTEMISSAO         DATE                                                       Campo para armazenar a data de emissão.            OPERACIONAL                        NaN
PCCONCILIACARTAO            DTVENC         DATE                                                    Campo para armazenar a data de vencimento.            OPERACIONAL                        NaN
PCCONCILIACARTAO             VALOR NUMBER(10,2)                                                       Campo para armazenar o valor do título.            OPERACIONAL                        NaN
PCCONCILIACARTAO               NSU VARCHAR2(15)                                                         Campo para armazenar o NSU do título.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONCILIACARTAO     CODAUTORIZTEF  NUMBER(6,0)                                    Campo para armazenar o código de autorização da venda TEF.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONCILIACARTAO         CODFILIAL  VARCHAR2(2)                                                      Campo para armazenar o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONCILIACARTAO      CODADMCARTAO  VARCHAR2(3)                                    Campo para armazenar o código da administradora de cartão.            OPERACIONAL                        NaN
PCCONCILIACARTAO         NUMCARTAO VARCHAR2(30)                                                      Campo para armazenar o número do cartão.            OPERACIONAL                        NaN
PCCONCILIACARTAO  NUMLOTECARTAOTEF VARCHAR2(40)                     Campo para armazenar o número do lote gerado para conciliação de cartões.            OPERACIONAL                        NaN
PCCONCILIACARTAO         DTVENCANT         DATE           Campo para armazenar a data de do contas a receber antes de realizar a conciliação.            OPERACIONAL                        NaN
PCCONCILIACARTAO CODFUNCCONCILVENC  NUMBER(8,0)        Campo para armazenar o código do funcionário que realizou a conciliação de vencimento.            OPERACIONAL                        NaN
PCCONCILIACARTAO      DTCONCILVENC         DATE                              Campo para armazenar a data e hora de conciliação do vencimento.            OPERACIONAL                        NaN
PCCONCILIACARTAO            NSUANT VARCHAR2(15)           Campo para armazenar a data de do contas a receber antes de realizar a conciliação.            OPERACIONAL                        NaN
PCCONCILIACARTAO     CODFUNCCONCIL  NUMBER(8,0)          Campo para armazenar o código do funcionário que realizou a conciliação dos títulos.            OPERACIONAL                        NaN
PCCONCILIACARTAO          DTCONCIL         DATE                                Campo para armazenar a data e hora de conciliação dos títulos.            OPERACIONAL                        NaN
PCCONCILIACARTAO      DTEMISSAOANT         DATE                    Campo para armazenar a data de emissão anterior à conciliação dos títulos.            OPERACIONAL                        NaN
PCCONCILIACARTAO  CODAUTORIZTEFANT  NUMBER(6,0) Campo para armazenar o código de autorização da venda TEF anterior à conciliação dos títulos.            OPERACIONAL                        NaN
PCCONCILIACARTAO      TIPOREGISTRO  VARCHAR2(6)                                        Campo para identificar o tipo da operação do registro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*