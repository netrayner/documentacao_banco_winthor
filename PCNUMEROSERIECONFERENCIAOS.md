# 📊 Tabela: PCNUMEROSERIECONFERENCIAOS

### Estrutura de Colunas e Restrições

                    Tabela         Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNUMEROSERIECONFERENCIAOS      CODFILIAL  VARCHAR2(2)                         Código da filial    CHAVE PRIMÁRIA (PK)              PCNUMEROSERIE
PCNUMEROSERIECONFERENCIAOS        CODPROD  NUMBER(6,0)                        Código do produto    CHAVE PRIMÁRIA (PK)              PCNUMEROSERIE
PCNUMEROSERIECONFERENCIAOS        CODPROD  NUMBER(6,0)                        Código do produto    CHAVE PRIMÁRIA (PK)              PCITEMSERVICO
PCNUMEROSERIECONFERENCIAOS        CODPROD  NUMBER(6,0)                        Código do produto    CHAVE PRIMÁRIA (PK)              PCNUMEROSERIE
PCNUMEROSERIECONFERENCIAOS        CODPROD  NUMBER(6,0)                        Código do produto    CHAVE PRIMÁRIA (PK)              PCITEMSERVICO
PCNUMEROSERIECONFERENCIAOS       NUMSERIE VARCHAR2(60)                          Número de série    CHAVE PRIMÁRIA (PK)              PCNUMEROSERIE
PCNUMEROSERIECONFERENCIAOS   NUMOSSERVICO  NUMBER(6,0)                         Número de pedido CHAVE ESTRANGEIRA (FK)              PCITEMSERVICO
PCNUMEROSERIECONFERENCIAOS CODEQUIPAMENTO  NUMBER(6,0)                    Número do equipamento CHAVE ESTRANGEIRA (FK)              PCITEMSERVICO
PCNUMEROSERIECONFERENCIAOS  NUMSERIEEQUIP VARCHAR2(30) Número do número de série do equipamento CHAVE ESTRANGEIRA (FK)              PCITEMSERVICO
PCNUMEROSERIECONFERENCIAOS  DATASEPARACAO         DATE             Data da separação do produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*