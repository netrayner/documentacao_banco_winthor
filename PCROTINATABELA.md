# 📊 Tabela: PCROTINATABELA

### Estrutura de Colunas e Restrições

        Tabela             Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTINATABELA          CODROTINA   NUMBER(4,0)                          Código da rotina    CHAVE PRIMÁRIA (PK)                        NaN
PCROTINATABELA         NOMEOBJETO  VARCHAR2(40)         Nome da tabela vinculado a rotina    CHAVE PRIMÁRIA (PK)                        NaN
PCROTINATABELA    USARCADGENERICO       CHAR(1) Verifica se aceita usar cadastro generico            OPERACIONAL                        NaN
PCROTINATABELA WHEREADICIONALPESQ VARCHAR2(250)   Clausula adiciona no select de pesquisa            OPERACIONAL                        NaN
PCROTINATABELA       TITULOROTINA VARCHAR2(150)                                       NaN            OPERACIONAL                        NaN
PCROTINATABELA     PERMITEINCLUIR   VARCHAR2(1)                                       NaN            OPERACIONAL                        NaN
PCROTINATABELA     PERMITEALTERAR   VARCHAR2(1)                                       NaN            OPERACIONAL                        NaN
PCROTINATABELA     PERMITEEXCLUIR   VARCHAR2(1)                                       NaN            OPERACIONAL                        NaN
PCROTINATABELA         DTCADASTRO          DATE                                       NaN            OPERACIONAL                        NaN
PCROTINATABELA ATUALIZARPERMISSAO   VARCHAR2(1)                                       NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*