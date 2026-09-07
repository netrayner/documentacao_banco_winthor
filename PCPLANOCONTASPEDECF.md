# 📊 Tabela: PCPLANOCONTASPEDECF

### Estrutura de Colunas e Restrições

             Tabela             Coluna   Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPLANOCONTASPEDECF CODPLANOCONTA_SPED    NUMBER(7,0)               Indica o código do plano contas SPED.            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF      CODCONTA_SPED   VARCHAR2(20)                      Indica o código da conta SPED.            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF          DESCRICAO  VARCHAR2(200)                        Indica a descrição da conta.            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF        ORIENTACOES VARCHAR2(1000) Indica a especificação sobre a utilizaade da conta.            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF           DTINICIO           DATE                                       Data inicial.            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF              DTFIM           DATE                                          Data final            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF              ORDEM    VARCHAR2(5)                             Ordem da conta no grupo            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF               TIPO    VARCHAR2(1)       Tipo da conta: Analítica (A) ou Sintética (S)            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF            COD_SUP   VARCHAR2(20)                            Código da conta superior            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF              NIVEL    VARCHAR2(2)                                      Nível da conta            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF           NATUREZA    VARCHAR2(5)             Indica o grupo ao qual a conta pertence            OPERACIONAL                        NaN
PCPLANOCONTASPEDECF  TIPOPLANOCONTAREF    VARCHAR2(2)                    Indica o tipo do plano de contas            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*