# 📊 Tabela: PCDESCONTOI

### Estrutura de Colunas e Restrições

     Tabela       Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESCONTOI       CODIGO NUMBER(10,0)                         Indica o código da campanha de desconto.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCONTOI    SEQUENCIA NUMBER(10,0)                 Indica o código do item de campanha de desconto.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCONTOI      CODPROD  NUMBER(6,0)     Indica o código do produto do item da campanha de descontos.            OPERACIONAL                        NaN
PCDESCONTOI     QTMINIMA NUMBER(12,6)               Indica a quantidade mínima para efetivar desconto.            OPERACIONAL                        NaN
PCDESCONTOI      PERDESC NUMBER(12,6) Indica o percentual de desconto concedido ao atingir quantidade.            OPERACIONAL                        NaN
PCDESCONTOI  TIPOPRODUTO  VARCHAR2(1)                            Indica o tipo do produto da campanha.            OPERACIONAL                        NaN
PCDESCONTOI     QTMAXIMA NUMBER(12,6)        Quantidade máxima para intervalo da politica de desconto.            OPERACIONAL                        NaN
PCDESCONTOI       SYNCFV  VARCHAR2(1)                                                              NaN            OPERACIONAL                        NaN
PCDESCONTOI TIPODESCONTO  VARCHAR2(2)      Define qual o tipo de desconto será aplicado para o produto            OPERACIONAL                        NaN
PCDESCONTOI  CODAUXILIAR NUMBER(20,0)                                   Código da Embalagem do produto            OPERACIONAL                        NaN
PCDESCONTOI   DTMXSALTER         DATE                                                              NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*