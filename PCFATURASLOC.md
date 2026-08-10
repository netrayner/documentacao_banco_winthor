# 📊 Tabela: PCFATURASLOC

### Estrutura de Colunas e Restrições

      Tabela        Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFATURASLOC   NUMCONTRATO  NUMBER(8,0)                Indica o número do contrato.    CHAVE PRIMÁRIA (PK)         PCCONTRATOCOMODLOC
PCFATURASLOC      DTINICIO         DATE Indica a data de inicio período de locação.    CHAVE PRIMÁRIA (PK)                        NaN
PCFATURASLOC       DTFINAL         DATE  Indica a data final do período de locação.    CHAVE PRIMÁRIA (PK)                        NaN
PCFATURASLOC NUMTRANSVENDA NUMBER(10,0)         Indica o número transação de venda.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*