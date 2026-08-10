# 📊 Tabela: PCGMINDICADOR

### Estrutura de Colunas e Restrições

       Tabela             Coluna   Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMINDICADOR             CODIGO   NUMBER(10,0)             Código do indicador    CHAVE PRIMÁRIA (PK)                        NaN
PCGMINDICADOR          DESCRICAO  VARCHAR2(100)          Descrição do indicador            OPERACIONAL                        NaN
PCGMINDICADOR REGRACALCREALIZADO VARCHAR2(3000) Regra para calcular o realizado            OPERACIONAL                        NaN
PCGMINDICADOR  REGRACALCPREVISTO VARCHAR2(1000)  Regra para calcular o previsto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*