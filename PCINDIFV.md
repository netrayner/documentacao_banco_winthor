# 📊 Tabela: PCINDIFV

### Estrutura de Colunas e Restrições

  Tabela        Coluna   Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINDIFV    CODINDENIZ   NUMBER(10,0)                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINDIFV       CODPROD    NUMBER(6,0)                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINDIFV            QT   NUMBER(20,6)                                                 NaN            OPERACIONAL                        NaN
PCINDIFV        PVENDA   NUMBER(12,3)                                                 NaN            OPERACIONAL                        NaN
PCINDIFV           OBS   VARCHAR2(60)                                                 NaN            OPERACIONAL                        NaN
PCINDIFV OBSERVACAO_PC VARCHAR2(4000)                                                 NaN            OPERACIONAL                        NaN
PCINDIFV    DTINCLUSAO           DATE                        Data de Inclusão no registro            OPERACIONAL                        NaN
PCINDIFV   DTALTERACAO           DATE                       Data de Alteração no registro            OPERACIONAL                        NaN
PCINDIFV      RECOLHER    VARCHAR2(1) Informa se o produto avariado é para ser recolhido.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*