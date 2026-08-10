# 📊 Tabela: PCDADOSGENERICOS

### Estrutura de Colunas e Restrições

          Tabela         Coluna   Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDADOSGENERICOS    CODREGISTRO   NUMBER(10,0)                              Código do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCDADOSGENERICOS CODREGISTROPAI   NUMBER(10,0)                          Código do registro pai            OPERACIONAL                        NaN
PCDADOSGENERICOS        DADOSID   VARCHAR2(10)                         Identificador dos dados            OPERACIONAL                        NaN
PCDADOSGENERICOS      CODFILIAL    VARCHAR2(2)                                Código da filial            OPERACIONAL                        NaN
PCDADOSGENERICOS           DATA           DATE Data do registro (período a qual vai pertencer)            OPERACIONAL                        NaN
PCDADOSGENERICOS       REGISTRO   VARCHAR2(10)                       Identificador do registro            OPERACIONAL                        NaN
PCDADOSGENERICOS          CAMPO   VARCHAR2(30)                                   Nome do campo    CHAVE PRIMÁRIA (PK)                        NaN
PCDADOSGENERICOS      TIPOCAMPO        CHAR(1)                                   Tipo do campo            OPERACIONAL                        NaN
PCDADOSGENERICOS    VALOR_TEXTO VARCHAR2(1000)            Valor do campo, se tipo alfanumerico            OPERACIONAL                        NaN
PCDADOSGENERICOS     VALOR_DATA           DATE                    Valor do campo, se tipo data            OPERACIONAL                        NaN
PCDADOSGENERICOS      VALOR_NUM   NUMBER(20,6)                Valor do campo, se tipo numerico            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*