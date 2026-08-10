# 📊 Tabela: PCCLIENTFILIALMED

### Estrutura de Colunas e Restrições

           Tabela           Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIENTFILIALMED           CODCLI  NUMBER(6,0)             Código do Cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTFILIALMED        CODFILIAL  VARCHAR2(2)              Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTFILIALMED   CLIENTEFONTEST  VARCHAR2(1)              Calcula ST Fonte            OPERACIONAL                        NaN
PCCLIENTFILIALMED          REPASSE  VARCHAR2(1)               Calcula Repasse            OPERACIONAL                        NaN
PCCLIENTFILIALMED           CODCOB  VARCHAR2(4)            Código da Cobrança            OPERACIONAL                        NaN
PCCLIENTFILIALMED         CODPLPAG  NUMBER(4,0)     Código do Plano Pagamento            OPERACIONAL                        NaN
PCCLIENTFILIALMED    CODPLPAGETICO  NUMBER(4,0)    Código do Plano Pag. Ético            OPERACIONAL                        NaN
PCCLIENTFILIALMED CODPLPAGGENERICO  NUMBER(4,0) Código do Plano Pag. Genérico            OPERACIONAL                        NaN
PCCLIENTFILIALMED         CODUSUR1  NUMBER(4,0)                         RCA 1            OPERACIONAL                        NaN
PCCLIENTFILIALMED  CODFILIALRETIRA  VARCHAR2(2)       Código da Filial Retira            OPERACIONAL                        NaN
PCCLIENTFILIALMED          CODUSUR  NUMBER(4,0) Código do RCA padrão da venda            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*