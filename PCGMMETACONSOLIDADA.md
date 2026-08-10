# 📊 Tabela: PCGMMETACONSOLIDADA

### Estrutura de Colunas e Restrições

             Tabela             Coluna  Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMMETACONSOLIDADA            CODMETA  NUMBER(10,0)                       Código da meta    CHAVE PRIMÁRIA (PK)                        NaN
PCGMMETACONSOLIDADA        CODTIPOMETA  NUMBER(10,0)               Código do tipo de meta    CHAVE PRIMÁRIA (PK)                        NaN
PCGMMETACONSOLIDADA       CODINDICADOR  NUMBER(10,0)                  Código do indicador    CHAVE PRIMÁRIA (PK)                        NaN
PCGMMETACONSOLIDADA        COLABORADOR VARCHAR2(255)          Nome do colaborador da meta            OPERACIONAL                        NaN
PCGMMETACONSOLIDADA DTULTPROCESSAMENTO          DATE Data do último processamento da meta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*