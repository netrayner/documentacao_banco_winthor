# 📊 Tabela: PCREINFR1070SUSP

### Estrutura de Colunas e Restrições

          Tabela                  Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR1070SUSP                      ID  NUMBER(8,0)                               Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR1070SUSP                R1070_ID  NUMBER(8,0)                         Identificador R1070 CHAVE ESTRANGEIRA (FK)               PCREINFR1070
PCREINFR1070SUSP  CODINDICATIVOSUSPENSAO VARCHAR2(20)              Código indicativo de suspensão            OPERACIONAL                        NaN
PCREINFR1070SUSP    INDICATIVOSUSPEXIGIB      CHAR(2)          Indicativo suspensão exigibilidade            OPERACIONAL                        NaN
PCREINFR1070SUSP               DTDECISAO         DATE                             Data de decisão            OPERACIONAL                        NaN
PCREINFR1070SUSP INDICATIVODEPOSITOINTEG      CHAR(1) Indicativo do depósito do montante integral            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*