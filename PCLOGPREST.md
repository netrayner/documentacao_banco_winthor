# 📊 Tabela: PCLOGPREST

### Estrutura de Colunas e Restrições

    Tabela        Coluna Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPREST          DATA         DATE            Data de exclusão            OPERACIONAL                        NaN
PCLOGPREST NUMTRANSVENDA NUMBER(10,0)     Núm. Transação de venda            OPERACIONAL                        NaN
PCLOGPREST        DUPLIC NUMBER(10,0)         Número da duplicata            OPERACIONAL                        NaN
PCLOGPREST         PREST  VARCHAR2(2)                   Prestação            OPERACIONAL                        NaN
PCLOGPREST        CODCLI  NUMBER(6,0)           Código do cliente            OPERACIONAL                        NaN
PCLOGPREST        CODCOB  VARCHAR2(4)          Código da cobrança            OPERACIONAL                        NaN
PCLOGPREST        DTVENC         DATE      Data vencimento título            OPERACIONAL                        NaN
PCLOGPREST         VALOR NUMBER(14,2)             Valor do título            OPERACIONAL                        NaN
PCLOGPREST         DTPAG         DATE Data de pagamento do título            OPERACIONAL                        NaN
PCLOGPREST         VPAGO NUMBER(14,2)                  Valor pago            OPERACIONAL                        NaN
PCLOGPREST      PROGRAMA VARCHAR2(80)     Rotina que fez exclusão            OPERACIONAL                        NaN
PCLOGPREST       USUARIO VARCHAR2(80)         Usuário da exclusão            OPERACIONAL                        NaN
PCLOGPREST       MAQUINA VARCHAR2(80)         Máquina da exclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*