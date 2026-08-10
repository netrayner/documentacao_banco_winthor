# 📊 Tabela: PCDOCFISCALMETRICAS

### Estrutura de Colunas e Restrições

             Tabela         Coluna  Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCFISCALMETRICAS   NUMTRANSACAO  NUMBER(37,0)        NUMTRANSACAO            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS TIPO_DOCUMENTO  VARCHAR2(10)      TIPO_DOCUMENTO            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS         STATUS  VARCHAR2(25)     STATUS do cstat            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS          CSTAT   VARCHAR2(5)         CSTAT o dfe            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS        XMOTIVO VARCHAR2(255)      XMOTIVO do dfe            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS  CNPJ_EMITENTE  VARCHAR2(20)       CNPJ_EMITENTE            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS             UF   VARCHAR2(2)  UF emitente do dfe            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS       AMBIENTE   VARCHAR2(1) AMBIENTE de emissao            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS   DATA_EMISSAO          DATE        DATA_EMISSAO            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS     DATA_ENVIO  TIMESTAMP(6)          DATA_ENVIO            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS   DATA_RETORNO  TIMESTAMP(6)        DATA_RETORNO            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS    TIPOEMISSAO   NUMBER(1,0)         TIPOEMISSAO            OPERACIONAL                        NaN
PCDOCFISCALMETRICAS        TIPOMOV   VARCHAR2(2)       TIPOMOVIMENTO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*