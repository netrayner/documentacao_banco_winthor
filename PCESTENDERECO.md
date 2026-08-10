# 📊 Tabela: PCESTENDERECO

### Estrutura de Colunas e Restrições

       Tabela        Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTENDERECO   CODENDERECO NUMBER(10,0)                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCESTENDERECO       CODPROD  NUMBER(6,0)                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCESTENDERECO            QT NUMBER(20,8)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO   QTBLOQUEADA NUMBER(20,8)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO      QTRESERV NUMBER(20,8)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO   QTPENDSAIDA NUMBER(20,8)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO QTPENDENTRADA NUMBER(20,8)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO         DTVAL         DATE                            NaN            OPERACIONAL                        NaN
PCESTENDERECO       NUMLOTE VARCHAR2(15)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO  DTFABRICACAO         DATE Data de fabricação do produto.            OPERACIONAL                        NaN
PCESTENDERECO      QTCANCEL NUMBER(16,6)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO   MOVPENDENTE  VARCHAR2(1)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO     CODIGOUMA NUMBER(14,0)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO   QTULTINVENT NUMBER(20,8)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO      QTESTANT NUMBER(20,8)                            NaN            OPERACIONAL                        NaN
PCESTENDERECO   DTULTINVENT         DATE                            NaN            OPERACIONAL                        NaN
PCESTENDERECO     DTENTRADA         DATE      Indica a data de entrada.            OPERACIONAL                        NaN
PCESTENDERECO         TESTE  VARCHAR2(2) Data de fabricação do produto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*