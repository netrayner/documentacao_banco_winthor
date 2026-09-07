# 📊 Tabela: PCNUMEROSERIECONFERENCIA

### Estrutura de Colunas e Restrições

                  Tabela        Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNUMEROSERIECONFERENCIA     CODFILIAL  VARCHAR2(2)             Código da filial    CHAVE PRIMÁRIA (PK)              PCNUMEROSERIE
PCNUMEROSERIECONFERENCIA       CODPROD  NUMBER(6,0)            Código do produto    CHAVE PRIMÁRIA (PK)              PCNUMEROSERIE
PCNUMEROSERIECONFERENCIA       CODPROD  NUMBER(6,0)            Código do produto    CHAVE PRIMÁRIA (PK)              PCNUMEROSERIE
PCNUMEROSERIECONFERENCIA       CODPROD  NUMBER(6,0)            Código do produto    CHAVE PRIMÁRIA (PK)                     PCPEDI
PCNUMEROSERIECONFERENCIA       CODPROD  NUMBER(6,0)            Código do produto    CHAVE PRIMÁRIA (PK)                     PCPEDI
PCNUMEROSERIECONFERENCIA      NUMSERIE VARCHAR2(60)              Número de série    CHAVE PRIMÁRIA (PK)              PCNUMEROSERIE
PCNUMEROSERIECONFERENCIA        NUMPED NUMBER(10,0)             Número de pedido CHAVE ESTRANGEIRA (FK)                     PCPEDI
PCNUMEROSERIECONFERENCIA        NUMSEQ NUMBER(20,0)  Número da sequência do item CHAVE ESTRANGEIRA (FK)                     PCPEDI
PCNUMEROSERIECONFERENCIA DATASEPARACAO         DATE Data da separação do produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*