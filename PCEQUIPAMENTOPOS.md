# 📊 Tabela: PCEQUIPAMENTOPOS

### Estrutura de Colunas e Restrições

          Tabela            Coluna  Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEQUIPAMENTOPOS CODEQUIPAMENTOPOS  NUMBER(10,0)      Sequencial do equipamento    CHAVE PRIMÁRIA (PK)                        NaN
PCEQUIPAMENTOPOS         CODFILIAL   VARCHAR2(2)               Codigo da filial            OPERACIONAL                        NaN
PCEQUIPAMENTOPOS         DESCRICAO VARCHAR2(100)       Descrição do equipamento            OPERACIONAL                        NaN
PCEQUIPAMENTOPOS       NUMEROSERIE  VARCHAR2(50) Numero de serie do equipamento            OPERACIONAL                        NaN
PCEQUIPAMENTOPOS       ADIQUIRENTE   VARCHAR2(6)  Codigo da operadora de cartão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*