# 📊 Tabela: PCCATSP

### Estrutura de Colunas e Restrições

 Tabela            Coluna Tipo/Tamanho                                                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCATSP         SEQUENCIA NUMBER(10,0)                                                                                           Sequência geral da tabela PCCATSP    CHAVE PRIMÁRIA (PK)                        NaN
PCCATSP              TIPO  VARCHAR2(1)                                                                       Tipo de documento (E = ENTRADA; S = SAÍDA; L = SALDO)            OPERACIONAL                        NaN
PCCATSP         CODFILIAL  VARCHAR2(2)                                                                                      Código da filial (Empresa selecionada)            OPERACIONAL                        NaN
PCCATSP           DATADOC         DATE                                                                                       Data do documento de entrada ou saída            OPERACIONAL                        NaN
PCCATSP           CODPROD NUMBER(10,0)                                                                                                           Código do produto            OPERACIONAL                        NaN
PCCATSP   CODPARTICIPANTE NUMBER(10,0)                                                                                             Código de fornecedor ou cliente            OPERACIONAL                        NaN
PCCATSP   CONSUMIDORFINAL  VARCHAR2(1)                                                                                        Consumidor Final ("S" sim e "N" não)            OPERACIONAL                        NaN
PCCATSP          ORGAOPUB  VARCHAR2(1)                                                                                           Órgão Público ("S" sim e "N" não)            OPERACIONAL                        NaN
PCCATSP    PERCALIQVIGINT NUMBER(20,6)                                                                                     Alíquota Vigente no cadastro do produto            OPERACIONAL                        NaN
PCCATSP           CAMPO01 NUMBER(10,0)                                                               Número de Ordem (Sequência de impressão do relatório/arquivo)            OPERACIONAL                        NaN
PCCATSP           CAMPO02         DATE                                                                                             Data (Data da entrada ou Saída)            OPERACIONAL                        NaN
PCCATSP           CAMPO03 VARCHAR2(44)                                                                                        Chave do Documento Fiscal Eletrônico            OPERACIONAL                        NaN
PCCATSP           CAMPO04 VARCHAR2(50)                                                                                        Número de Série de Fabricação do ECF            OPERACIONAL                        NaN
PCCATSP           CAMPO05 VARCHAR2(10)                                                                          Tipo do Documento (Descrição "Entrada" ou "Saída")            OPERACIONAL                        NaN
PCCATSP           CAMPO06  VARCHAR2(5)                                                                                                          Série do Documento            OPERACIONAL                        NaN
PCCATSP           CAMPO07 NUMBER(10,0)                                                                                                         Número do Documento            OPERACIONAL                        NaN
PCCATSP           CAMPO08 NUMBER(10,0)                                                                                         Código do Remetente ou Destinatário            OPERACIONAL                        NaN
PCCATSP           CAMPO09  NUMBER(8,0)                                                                                   CFOP (Código Fiscal Operações/Prestações)            OPERACIONAL                        NaN
PCCATSP           CAMPO10 NUMBER(10,0)                                                                                                 Número do Item no Documento            OPERACIONAL                        NaN
PCCATSP           CAMPO11 NUMBER(20,6)                                                                                                       Quantidade (Entradas)            OPERACIONAL                        NaN
PCCATSP           CAMPO12 NUMBER(20,6)                                                  Valor Total do ICMS Suportado na Retenção ou Antecipação por ST (Entradas)            OPERACIONAL                        NaN
PCCATSP           CAMPO13 NUMBER(20,6)                                                                                                         Quantidade (Saídas)            OPERACIONAL                        NaN
PCCATSP           CAMPO14 NUMBER(20,6)                                                                                   Valor Unitário do ICMS Suportado (Saídas)            OPERACIONAL                        NaN
PCCATSP           CAMPO15 NUMBER(20,6)                                               Saída a Consumidor ou Usuário Final - Código Enquadramento Legal = 1 (Saídas)            OPERACIONAL                        NaN
PCCATSP           CAMPO16 NUMBER(20,6)                                                        Fato Gerador Não Realizado - Código Enquadramento Legal = 2 (Saídas)            OPERACIONAL                        NaN
PCCATSP           CAMPO17 NUMBER(20,6)                          Saída ou Saída Subsequente com Isenção ou Não Incidência - Código Enquadramento Legal = 3 (Saídas)            OPERACIONAL                        NaN
PCCATSP           CAMPO18 NUMBER(20,6)                                                           Saída para Outro Estado - Código Enquadramento Legal = 4 (Saídas)            OPERACIONAL                        NaN
PCCATSP           CAMPO19 NUMBER(20,6)                            Saída para Comercialização Subsequente (Demais Saídas) - Código Enquadramento Legal = 0 (Saídas)            OPERACIONAL                        NaN
PCCATSP           CAMPO20 NUMBER(20,6) ICMS Efetivo na Saída: a Consumidor ou Usuário Final ou no caso de Saída Subsequente com Isenção ou Não Incidência (Saídas)            OPERACIONAL                        NaN
PCCATSP           CAMPO21 NUMBER(20,6)                                                                      ICMS Efetivo da Entrada, nas Demais Hipóteses (Saídas)            OPERACIONAL                        NaN
PCCATSP           CAMPO22 NUMBER(20,6)                                                                                                          Quantidade (Saldo)            OPERACIONAL                        NaN
PCCATSP           CAMPO23 NUMBER(20,6)                                                                                             Valor Unitário do Saldo (Saldo)            OPERACIONAL                        NaN
PCCATSP           CAMPO24 NUMBER(20,6)                                                                                                Valor Total do Saldo (Saldo)            OPERACIONAL                        NaN
PCCATSP           CAMPO25 NUMBER(20,6)                                                                                           Valor do Ressarcimento (Apuração)            OPERACIONAL                        NaN
PCCATSP           CAMPO26 NUMBER(20,6)                                                                                             Valor do Complemento (Apuração)            OPERACIONAL                        NaN
PCCATSP           CAMPO27 NUMBER(20,6)                                                         ICMS - Crédito da Operação Própria (artigo 271 do RICMS) (Apuração)            OPERACIONAL                        NaN
PCCATSP SOMARQUANTENTRADA  VARCHAR2(1)                                                                                         Soma Quantidade de Entrada no Saldo            OPERACIONAL                        NaN
PCCATSP       DATAPERIODO         DATE                                                                                                  Data do Período de Geração            OPERACIONAL                        NaN
PCCATSP           CODOPER  VARCHAR2(2)                                                                                         Código de Operação de Entrada/Saída            OPERACIONAL                        NaN
PCCATSP         QTCONTENT NUMBER(20,6)                                                                                                       Quantidade de entrada            OPERACIONAL                        NaN
PCCATSP      QTCONTMOVSAI NUMBER(20,6)                                                                                     Quantidade de Saída vinculada a entrada            OPERACIONAL                        NaN
PCCATSP         QTCONTSAI NUMBER(20,6)                                                                                                         Quantidade de Saída            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*