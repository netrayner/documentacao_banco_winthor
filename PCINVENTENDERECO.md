# 📊 Tabela: PCINVENTENDERECO

### Estrutura de Colunas e Restrições

          Tabela         Coluna Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINVENTENDERECO      NUMINVENT  NUMBER(8,0)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTENDERECO      CODFILIAL  VARCHAR2(2)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO           DATA         DATE                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO        CODFUNC  NUMBER(8,0)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO    CODENDERECO NUMBER(10,0)                                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTENDERECO  DTATUALIZACAO         DATE                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO         VERSAO    NVARCHAR2                                            VERSAO DA ROTINA            OPERACIONAL                        NaN
PCINVENTENDERECO       INVENTOS  NUMBER(6,0)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO       BLOQUEIO  VARCHAR2(1)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO           TIPO  VARCHAR2(1)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO  VALIDAESTOQUE  VARCHAR2(1)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO     DIGITACEGA  VARCHAR2(1)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO TODOSENDERECOS  VARCHAR2(2)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO             RF  VARCHAR2(1)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO     ATUALIZADO  VARCHAR2(1)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO       CODPARAM NUMBER(10,0)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO         STATUS  VARCHAR2(2)                                                         NaN            OPERACIONAL                        NaN
PCINVENTENDERECO  CODFUNCCANCEL  NUMBER(8,0) Indica a matricula do funcionário que cancelou o inventário            OPERACIONAL                        NaN
PCINVENTENDERECO       DTCANCEL         DATE               Indica a data que o inventário foi cancelado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*