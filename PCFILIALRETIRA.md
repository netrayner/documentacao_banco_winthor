# 📊 Tabela: PCFILIALRETIRA

### Estrutura de Colunas e Restrições

        Tabela           Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILIALRETIRA   CODFILIALVENDA  VARCHAR2(2)                  Código da filial de venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCFILIALRETIRA  CODFILIALRETIRA  VARCHAR2(2)                    Código da filial retira.    CHAVE PRIMÁRIA (PK)                        NaN
PCFILIALRETIRA PRIORIDADEFILIAL  NUMBER(3,0) Prioridade da filial retira a ser escolhida            OPERACIONAL                        NaN
PCFILIALRETIRA       DTMXSALTER         DATE                                         NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*