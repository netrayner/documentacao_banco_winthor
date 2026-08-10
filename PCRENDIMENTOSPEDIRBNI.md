# 📊 Tabela: PCRENDIMENTOSPEDIRBNI

### Estrutura de Colunas e Restrições

               Tabela             Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRENDIMENTOSPEDIRBNI         CODSERVICO   NUMBER(8,0)               Código do serviço    CHAVE PRIMÁRIA (PK)                        NaN
PCRENDIMENTOSPEDIRBNI  CODTIPORENDIMENTO  NUMBER(10,0)   Código natureza do rendimento CHAVE ESTRANGEIRA (FK)       PCTIPORENDIMENTOSBNI
PCRENDIMENTOSPEDIRBNI       VALORBRUTONF  NUMBER(14,2)           Valor bruto da nota\t            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRBNI VALORBASERENTENCAO  NUMBER(14,2)       Valor da base de retenção            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRBNI       PERCRETENCAO  NUMBER(14,2) Valor do percentual de retenção            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRBNI    VALORRETENCAOIR  NUMBER(14,2)               Valor de retenção            OPERACIONAL                        NaN
PCRENDIMENTOSPEDIRBNI        OBSERVACOES VARCHAR2(200)                     Observações            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*