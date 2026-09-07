# 📊 Tabela: PCGMPERIODO

### Estrutura de Colunas e Restrições

     Tabela        Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMPERIODO        CODIGO NUMBER(10,0)                Código do período    CHAVE PRIMÁRIA (PK)                        NaN
PCGMPERIODO     DESCRICAO VARCHAR2(50)             Descrição do período            OPERACIONAL                        NaN
PCGMPERIODO PERIODICIDADE  VARCHAR2(1)         Periodo mensal ou diário            OPERACIONAL                        NaN
PCGMPERIODO   NUMEROMESES  NUMBER(2,0)              Quantidade de meses            OPERACIONAL                        NaN
PCGMPERIODO           MES  NUMBER(2,0) Número do mês inicial do período            OPERACIONAL                        NaN
PCGMPERIODO           ANO  NUMBER(4,0)                   Ano do período            OPERACIONAL                        NaN
PCGMPERIODO  DATAEXCLUSAO         DATE                 Data da exclusão            OPERACIONAL                        NaN
PCGMPERIODO        FILIAL  VARCHAR2(2)                Filial do período            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*