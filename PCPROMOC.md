# 📊 Tabela: PCPROMOC

### Estrutura de Colunas e Restrições

  Tabela                 Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPROMOC            CODPROMOCAO   NUMBER(6,0)                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPROMOC               DTINICIO          DATE                                         NaN            OPERACIONAL                        NaN
PCPROMOC                  DTFIM          DATE                                         NaN            OPERACIONAL                        NaN
PCPROMOC              DESCRICAO  VARCHAR2(60)                                         NaN            OPERACIONAL                        NaN
PCPROMOC  QTPONTOSNOVOSCLIENTES   NUMBER(8,2)                                         NaN            OPERACIONAL                        NaN
PCPROMOC        MULTIPONTOSMETA   VARCHAR2(1)                                         NaN            OPERACIONAL                        NaN
PCPROMOC APLICARCAMPANHAFAMILIA   VARCHAR2(1)                                         NaN            OPERACIONAL                        NaN
PCPROMOC            METODOLOGIA VARCHAR2(500)                                         NaN            OPERACIONAL                        NaN
PCPROMOC               QTMIXMIN   NUMBER(8,0) Quantidade minima de itens do MIX incluído.            OPERACIONAL                        NaN
PCPROMOC             DTMXSALTER          DATE                                         NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*