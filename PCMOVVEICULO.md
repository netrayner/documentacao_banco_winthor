# 📊 Tabela: PCMOVVEICULO

### Estrutura de Colunas e Restrições

      Tabela           Coluna  Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVVEICULO       CODVEICULO   NUMBER(4,0)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVVEICULO     CODMOTORISTA   NUMBER(8,0)                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVVEICULO   DTSAIDAVEICULO          DATE                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVVEICULO        DTRETORNO          DATE                 NaN            OPERACIONAL                        NaN
PCMOVVEICULO    QTCOMBUSTIVEL  NUMBER(18,6)                 NaN            OPERACIONAL                        NaN
PCMOVVEICULO    VLCOMBUSTIVEL   NUMBER(8,4)                 NaN            OPERACIONAL                        NaN
PCMOVVEICULO        KMINICIAL  NUMBER(12,2)                 NaN            OPERACIONAL                        NaN
PCMOVVEICULO          KMFINAL  NUMBER(12,2)                 NaN            OPERACIONAL                        NaN
PCMOVVEICULO   HISTORICOSAIDA VARCHAR2(240)                 NaN            OPERACIONAL                        NaN
PCMOVVEICULO HISTORICORETORNO VARCHAR2(240)                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*