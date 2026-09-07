# 📊 Tabela: PCLOGDELETEDADOS

### Estrutura de Colunas e Restrições

          Tabela       Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDELETEDADOS       TABELA VARCHAR2(40)           Nome da tabela que sofreu deleção            OPERACIONAL                        NaN
PCLOGDELETEDADOS    TRANSACAO NUMBER(10,0)           Chave da linha que sofreu deleção            OPERACIONAL                        NaN
PCLOGDELETEDADOS      USUARIO VARCHAR2(40)           Funcionário OS que fez a deleção.            OPERACIONAL                        NaN
PCLOGDELETEDADOS      ARQUIVO         CLOB Container que armazena o insert da deleção.            OPERACIONAL                        NaN
PCLOGDELETEDADOS     DTDELETE         DATE                             Data da deleção            OPERACIONAL                        NaN
PCLOGDELETEDADOS MOVIMENTACAO  VARCHAR2(1)                Tipo de movimentação, E ou S            OPERACIONAL                        NaN
PCLOGDELETEDADOS       ROTINA VARCHAR2(40)                Rotina que solicitou deleção            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*