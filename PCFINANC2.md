# 📊 Tabela: PCFINANC2

### Estrutura de Colunas e Restrições

   Tabela                       Coluna   Tipo/Tamanho                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFINANC2                         DATA           DATE                                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC2                    CODFILIAL    VARCHAR2(2)                                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC2                     TIPODADO   VARCHAR2(10)                                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC2                      CODIGON   NUMBER(10,0)                                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC2                      CODIGOA    VARCHAR2(4)                                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFINANC2                        VALOR   NUMBER(24,8)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC2                    DTGERACAO           DATE                                                                      NaN            OPERACIONAL                        NaN
PCFINANC2                    CODROTINA    NUMBER(4,0)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC2                      CODFUNC    NUMBER(8,0)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC2                       VALOR2   NUMBER(24,8)                                                                      NaN            OPERACIONAL                        NaN
PCFINANC2       LISTAFILIAISBANCOCAIXA VARCHAR2(4000) Lista das filiais vinculadas ao caixa / banco cadastradas na rotiina 524            OPERACIONAL                        NaN
PCFINANC2 PARMULTIFILIALCAIXABANCO3882    VARCHAR2(1)                       Status do parametro 3882 multifiliais caixa/banco.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*