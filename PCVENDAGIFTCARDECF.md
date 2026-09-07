# 📊 Tabela: PCVENDAGIFTCARDECF

### Estrutura de Colunas e Restrições

            Tabela             Coluna  Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVENDAGIFTCARDECF          NUMPEDECF  NUMBER(10,0)            Número do pedido do caixa.            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF           NUMCAIXA   NUMBER(4,0)                      Número do caixa.            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF      NUMSERIEEQUIP  VARCHAR2(30) Número de série da impressora fiscal.    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDAGIFTCARDECF               DATA          DATE                        Data da venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDAGIFTCARDECF          CODFUNCCX   NUMBER(8,0)                   Código do operador.            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF             NUMCOO   NUMBER(8,0)                        Número do COO.    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDAGIFTCARDECF             CODCLI   NUMBER(6,0)                    Código do cliente.            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF              VALOR  NUMBER(16,3)                       Valor da venda.            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF        NUMGIFTCARD  NUMBER(25,0)            Número do cartão giftcard.    CHAVE PRIMÁRIA (PK)                        NaN
PCVENDAGIFTCARDECF      NUMTRANSVENDA  NUMBER(10,0)         Número da transação de venda.            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF          EXPORTADO   VARCHAR2(1)                Controle de exportação            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF       DTEXPORTACAO          DATE                   Data de exportação.            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF         ASSINATURA VARCHAR2(255)                 Assinatura da rotina.            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF NUMFECHAMENTOMOVCX  NUMBER(10,0)                  Numero de fechamento            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF      DTMOVIMENTOCX          DATE                    Data de fechamento            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF            CODUSUR   NUMBER(4,0)                Código do RCA da venda            OPERACIONAL                        NaN
PCVENDAGIFTCARDECF          NUMPEDHUB  VARCHAR2(50)           Identificador do pedido Web            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*