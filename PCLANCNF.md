# 📊 Tabela: PCLANCNF

### Estrutura de Colunas e Restrições

  Tabela            Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLANCNF       NUMTRANSENT NUMBER(10,0)                         Transação da nota de entrada            OPERACIONAL                        NaN
PCLANCNF            RECNUM NUMBER(10,0)                   Recnum referente ao item na pclanc            OPERACIONAL                        NaN
PCLANCNF            DTVENC         DATE                                    Data devencimento            OPERACIONAL                        NaN
PCLANCNF             VALOR NUMBER(18,6)                                     Valor da parcela            OPERACIONAL                        NaN
PCLANCNF            CODCOB  VARCHAR2(4)                                   Código da cobrança            OPERACIONAL                        NaN
PCLANCNF           NUMNOTA NUMBER(10,0)                                       Número da nota            OPERACIONAL                        NaN
PCLANCNF            DUPLIC  VARCHAR2(2)                                  Número da duplicata            OPERACIONAL                        NaN
PCLANCNF       CODCOBSEFAZ  VARCHAR2(4)                          Código de cobrança do Sefaz            OPERACIONAL                        NaN
PCLANCNF CNPJCREDENCCARTAO VARCHAR2(18)                      CNPJ de credenciadora do cartão            OPERACIONAL                        NaN
PCLANCNF            NSUTEF VARCHAR2(15)                      Número de autorização do cartão            OPERACIONAL                        NaN
PCLANCNF    BANDEIRACARTAO  VARCHAR2(3)                                   Bandeira do cartão            OPERACIONAL                        NaN
PCLANCNF        TP_INTEGRA  VARCHAR2(2)      Tipo de Integração para pagamento (1=TEF/2=POS)            OPERACIONAL                        NaN
PCLANCNF            INDPAG  NUMBER(1,0) Indicador da Forma de Pagamento(0=A vista/1=A prazo)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*