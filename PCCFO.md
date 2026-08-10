# 📊 Tabela: PCCFO

### Estrutura de Colunas e Restrições

Tabela            Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
 PCCFO         CODFISCAL   NUMBER(8,0)                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
 PCCFO           DESCCFO  VARCHAR2(60)                                            NaN            OPERACIONAL                        NaN
 PCCFO           CODOPER   VARCHAR2(2)                                            NaN            OPERACIONAL                        NaN
 PCCFO      DESCSINTEGRA VARCHAR2(200)                                            NaN            OPERACIONAL                        NaN
 PCCFO   CODFISCALMASTER   NUMBER(8,0)                                            NaN            OPERACIONAL                        NaN
 PCCFO            OBSCFO VARCHAR2(100)                                            NaN            OPERACIONAL                        NaN
 PCCFO       CFOPINVERSO   NUMBER(8,0)                                            NaN            OPERACIONAL                        NaN
 PCCFO ESTOQUEEMTRANSITO   VARCHAR2(1) Participa do processo de estoque em trÃ¢nsito.            OPERACIONAL                        NaN
 PCCFO        DTMXSALTER          DATE                                            NaN            OPERACIONAL                        NaN
 PCCFO         DTALTERC5  TIMESTAMP(6)                                 DATA ALTERACAO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*