# 📊 Tabela: PCREINFR2060A

### Estrutura de Colunas e Restrições

       Tabela     Coluna Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2060A         ID  NUMBER(8,0)               Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2060A  R2060I_ID  NUMBER(8,0) Identificador do R2060 item CHAVE ESTRANGEIRA (FK)              PCREINFR2060I
PCREINFR2060A   TPAJUSTE  NUMBER(1,0)              Tipo de ajuste            OPERACIONAL                        NaN
PCREINFR2060A  CODAJUSTE  NUMBER(2,0)            Código do ajuste            OPERACIONAL                        NaN
PCREINFR2060A  VLRAJUSTE NUMBER(12,2)             Valor do ajuste            OPERACIONAL                        NaN
PCREINFR2060A   DTAJUSTE         DATE              Data do ajuste            OPERACIONAL                        NaN
PCREINFR2060A DESCAJUSTE VARCHAR2(20)         Descrição do ajuste            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*