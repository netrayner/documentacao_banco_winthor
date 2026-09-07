# 📊 Tabela: PCSUPPLIPARAMFAT

### Estrutura de Colunas e Restrições

          Tabela              Coluna Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPPLIPARAMFAT          CONDFINANC  VARCHAR2(9)                                                                    Condição de Financiamento            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT       DTFATURAMENTO         DATE                                                                          Data do Faturamento            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT             DTVENC1         DATE                                                                        Data do 1º Vencimento            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT               PLANO  NUMBER(2,0)                                                                       Quantidade de parcelas            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT         COEFICIENTE NUMBER(18,6)                                     Coeficiente suppliercard - Parametrização de faturamento            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT                TAXA NUMBER(13,4)                                            Taxa suppliercard - Parametrização de faturamento            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT QTDDIASPGTOPARCEIRO  NUMBER(2,0) Quantidade de dias para o pagamento do parceiro suppliercard - Parametrização de faturamento            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT              FILIAL  VARCHAR2(4)                                                             Código da filial na suppliercard            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT          TIPOPESSOA  VARCHAR2(1)                                                            0=Física,  1=Jurídica, NULL=Ambos            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT         TIPOCLIENTE  VARCHAR2(5)                                         Código do tipo de cliente cadastrado na suppliercard            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT        TIPOOPERACAO  VARCHAR2(2)                                                                       0=Padrão, 1=Pague Flex            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT  QTDIASVENCPARCELA1  NUMBER(5,0)                                                     Qtde de dias para o primeiro vencimento.            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT    VLRTXANTECIPACAO NUMBER(18,6)                                                                          Taxa de Antecipação            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT         CODEMSUPPLI  VARCHAR2(2)                                       Código da empresa parceira informado pela Suppliercard            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT   VLRTXCANCELAMENTO NUMBER(18,6)                                                                         Taxa de Cancelamento            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT    VLRTXPRORROGACAO NUMBER(18,6)                                                                          Taxa de Prorrogação            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT        TIPOCONDICAO  NUMBER(1,0)                                                           Tipo de Condição: 1=Padrão, 0=Flex            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT     QTDDIASPROXVENC  NUMBER(5,0)                                           Qtde de dias para cálculo dos próximos vencimentos            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT                  ID  NUMBER(8,0)                                                                              Chave da tabela            OPERACIONAL                        NaN
PCSUPPLIPARAMFAT          DTMXSALTER         DATE                                                                                          NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*