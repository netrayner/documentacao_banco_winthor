# 📊 Tabela: PCVENDAGIFTCARD

### Estrutura de Colunas e Restrições

         Tabela             Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVENDAGIFTCARD          NUMPEDECF  NUMBER(10,0)                 Numero do pedido            OPERACIONAL                        NaN
PCVENDAGIFTCARD           NUMCAIXA   NUMBER(4,0)                  Número do Caixa            OPERACIONAL                        NaN
PCVENDAGIFTCARD      NUMSERIEEQUIP  VARCHAR2(30)   Número de série do equipamento            OPERACIONAL                        NaN
PCVENDAGIFTCARD               DATA          DATE                    Data da venda    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDAGIFTCARD          CODFUNCCX   NUMBER(8,0) Codigo do funcionário que vendeu            OPERACIONAL                        NaN
PCVENDAGIFTCARD             NUMCOO   NUMBER(8,0)     Número de COO do comprovante            OPERACIONAL                        NaN
PCVENDAGIFTCARD             CODCLI   NUMBER(6,0)                Código do Cliente            OPERACIONAL                        NaN
PCVENDAGIFTCARD              VALOR  NUMBER(16,3)                   Valor da venda            OPERACIONAL                        NaN
PCVENDAGIFTCARD        NUMGIFTCARD  NUMBER(25,0)       Número do cartão Gift Card    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDAGIFTCARD      NUMTRANSVENDA  NUMBER(10,0)     Número de transação de Venda            OPERACIONAL                        NaN
PCVENDAGIFTCARD          EXPORTADO   VARCHAR2(1)             Status da exportação            OPERACIONAL                        NaN
PCVENDAGIFTCARD       DTEXPORTACAO          DATE               Data da exportação            OPERACIONAL                        NaN
PCVENDAGIFTCARD         ASSINATURA VARCHAR2(255)         Hash do arquivo de venda            OPERACIONAL                        NaN
PCVENDAGIFTCARD NUMFECHAMENTOMOVCX  NUMBER(10,0)             Numero de fechamento            OPERACIONAL                        NaN
PCVENDAGIFTCARD      DTMOVIMENTOCX          DATE               Data de fechamento            OPERACIONAL                        NaN
PCVENDAGIFTCARD            CODUSUR   NUMBER(4,0)           Código do RCA da venda            OPERACIONAL                        NaN
PCVENDAGIFTCARD          NUMPEDHUB  VARCHAR2(50)      Identificador do pedido Web            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*