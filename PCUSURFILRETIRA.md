# 📊 Tabela: PCUSURFILRETIRA

### Estrutura de Colunas e Restrições

         Tabela          Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCUSURFILRETIRA          CODIGO NUMBER(10,0)            identificador do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCUSURFILRETIRA         CODUSUR  NUMBER(4,0)                        Código do RCA            OPERACIONAL                        NaN
PCUSURFILRETIRA         CODFUNC  NUMBER(6,0) Código do usuário no menu do winthor            OPERACIONAL                        NaN
PCUSURFILRETIRA       ORIGEMPED  VARCHAR2(2)                     Origem do pedido            OPERACIONAL                        NaN
PCUSURFILRETIRA CODFILIALRETIRA  VARCHAR2(2)              Código da filial retira            OPERACIONAL                        NaN
PCUSURFILRETIRA  CODFILIALVENDA  VARCHAR2(2)            Código da filial de venda            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*