# 📊 Tabela: PCDOCFISCAL_DFES_PROCESSADOS

### Estrutura de Colunas e Restrições

                      Tabela            Coluna  Tipo/Tamanho  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCFISCAL_DFES_PROCESSADOS    TIPO_DOCUMENTO  VARCHAR2(10)       TIPO_DOCUMENTO            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS            STATUS  VARCHAR2(20)        STATUS do dfe            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS             CSTAT   VARCHAR2(5)         CSTAT do dfe            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS           XMOTIVO VARCHAR2(255)       XMOTIVO do dfe            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS     CNPJ_EMITENTE  VARCHAR2(20)        CNPJ_EMITENTE            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS          AMBIENTE   VARCHAR2(1)      AMBIENTE do dfe            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS        DATA_ENVIO  TIMESTAMP(6)           DATA_ENVIO            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS      DATA_RETORNO  TIMESTAMP(6)         DATA_RETORNO            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS      NOME_SERVICO VARCHAR2(255)         NOME_SERVICO            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS                UF   VARCHAR2(2) UF do dfe processado            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS      NUMTRANSACAO  NUMBER(37,0)         NUMTRANSACAO            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS TIPO_MOVIMENTACAO   VARCHAR2(2)    TIPO_MOVIMENTACAO            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS      ORDEM_EVENTO   NUMBER(2,0)         ORDEM_EVENTO            OPERACIONAL                        NaN
PCDOCFISCAL_DFES_PROCESSADOS    DATAHORAEVENTO  TIMESTAMP(6)       DATAHORAEVENTO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*