# 📊 Tabela: PCECOMMERCEB2BPAGAMENTO

### Estrutura de Colunas e Restrições

                 Tabela         Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEB2BPAGAMENTO         NUMPED  NUMBER(10,0)                 Numero do Pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPAGAMENTO         STATUS   VARCHAR2(3)                 Estado do Pedido            OPERACIONAL                        NaN
PCECOMMERCEB2BPAGAMENTO     DTINCLUSAO          DATE          Data Inclusao do Pedido            OPERACIONAL                        NaN
PCECOMMERCEB2BPAGAMENTO          DADOS          CLOB              Dados XML do Pedido            OPERACIONAL                        NaN
PCECOMMERCEB2BPAGAMENTO            LOG VARCHAR2(500) Log da Integração Winthor (PROC)            OPERACIONAL                        NaN
PCECOMMERCEB2BPAGAMENTO     PROCESSADO   VARCHAR2(3) Estado da Integração do Registro            OPERACIONAL                        NaN
PCECOMMERCEB2BPAGAMENTO      CODFILIAL   VARCHAR2(2)                 Código da Filial            OPERACIONAL                        NaN
PCECOMMERCEB2BPAGAMENTO TIPOINTEGRACAO   NUMBER(4,0)               Tipo da Integração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*