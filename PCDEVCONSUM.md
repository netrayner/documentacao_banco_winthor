# 📊 Tabela: PCDEVCONSUM

### Estrutura de Colunas e Restrições

     Tabela      Coluna  Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEVCONSUM NUMTRANSENT  NUMBER(10,0)                                                        NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCDEVCONSUM     CLIENTE  VARCHAR2(60)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM         CGC  VARCHAR2(18)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM    ENDERECO  VARCHAR2(40)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM      BAIRRO  VARCHAR2(40)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM    TELEFONE  VARCHAR2(13)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM      CIDADE  VARCHAR2(15)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM          UF   VARCHAR2(2)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM         CEP   VARCHAR2(9)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM          IE  VARCHAR2(15)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM         OBS VARCHAR2(100)                                                        NaN            OPERACIONAL                        NaN
PCDEVCONSUM       EMAIL VARCHAR2(100)                                       Endereço de e-mail.             OPERACIONAL                        NaN
PCDEVCONSUM   CODCIDADE   NUMBER(6,0) Indica o código da cidade de acordo com a tabela PCCIDADE.            OPERACIONAL                        NaN
PCDEVCONSUM      NUMERO   VARCHAR2(6)                                       Número da residencia            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*