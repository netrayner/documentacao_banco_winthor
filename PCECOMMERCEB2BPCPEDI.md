# 📊 Tabela: PCECOMMERCEB2BPCPEDI

### Estrutura de Colunas e Restrições

              Tabela      Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEB2BPCPEDI   NUMPEDWEB  VARCHAR2(20)             Numero do Pedido Web    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPCPEDI CODAUXILIAR  VARCHAR2(30)                Codigo do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPCPEDI     BONIFIC   VARCHAR2(3)              Tipo da Bonificacao    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPCPEDI          QT  NUMBER(18,6)            Quantidade do Produto            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDI      PVENDA  NUMBER(18,6)                   Preco de Venda            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDI     PTABELA  NUMBER(18,6)                  Preco de Tabela            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDI       DADOS          CLOB             Dados XML do Produto            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDI         LOG VARCHAR2(500) Log de Integração Winthor (PROC)            OPERACIONAL                        NaN
PCECOMMERCEB2BPCPEDI  PROCESSADO   VARCHAR2(3) Estado da Integracao do Registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*