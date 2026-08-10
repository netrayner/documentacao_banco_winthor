# 📊 Tabela: PCECOMMERCEB2BPCPEDC

### Estrutura de Colunas e Restrições

              Tabela            Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEB2BPCPEDC         NUMPEDWEB  VARCHAR2(20)                Numero Pedido Web    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPCPEDC              DATA          DATE                   Data do Pedido            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDC     TIPOPAGAMENTO  VARCHAR2(20)                Tipo de Pagamento            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDC           VLTOTAL  NUMBER(18,6)                      Valor Total            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDC        VLDESCONTO  NUMBER(18,6)                Valor do Desconto            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDC             DADOS          CLOB              Dados XML do Pedido            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDC               LOG VARCHAR2(500) Log da Integração Winthor (PROC)            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDC        PROCESSADO   VARCHAR2(3) Estado da Integração do Registro            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDC         CODFILIAL   VARCHAR2(2)                 Código da Filial            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDC CPFCNPJCONSUMIDOR  VARCHAR2(50)           CPF ou CNPJ do Cliente            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDC       INTEGRADORA   NUMBER(6,0)            Código da Integradora            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*