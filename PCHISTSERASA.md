# 📊 Tabela: PCHISTSERASA

### Estrutura de Colunas e Restrições

      Tabela              Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTSERASA                DATA          DATE                    Data de registro            OPERACIONAL                        NaN
PCHISTSERASA             USUARIO VARCHAR2(100)                             Usuário            OPERACIONAL                        NaN
PCHISTSERASA             MAQUINA VARCHAR2(100)                  Máquina do usuário            OPERACIONAL                        NaN
PCHISTSERASA              ROTINA VARCHAR2(100)         Rotina que inseriu registro            OPERACIONAL                        NaN
PCHISTSERASA       NUMTRANSVENDA  NUMBER(10,0)                  Transação de venda            OPERACIONAL                        NaN
PCHISTSERASA               PREST   VARCHAR2(2)                           Prestação            OPERACIONAL                        NaN
PCHISTSERASA              CODCLI   NUMBER(6,0)                   Código do Cliente            OPERACIONAL                        NaN
PCHISTSERASA                TIPO  VARCHAR2(20)     Inclusão / Alteração / Exclusão            OPERACIONAL                        NaN
PCHISTSERASA       DTENVIOSERASA          DATE             Data de envio ao Serasa            OPERACIONAL                        NaN
PCHISTSERASA    DTENVIOSERASAANT          DATE    Data de envio ao Serasa Anterior            OPERACIONAL                        NaN
PCHISTSERASA    DTRETIRADASERASA          DATE          Data de exclusão do Serasa            OPERACIONAL                        NaN
PCHISTSERASA DTRETIRADASERASAANT          DATE Data de exclusão do Serasa Anterior            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*