# 📊 Tabela: PCREINFR2060I

### Estrutura de Colunas e Restrições

       Tabela          Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2060I              ID   NUMBER(8,0)                             Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2060I       R2060C_ID   NUMBER(8,0)             Identificador R2060 cabeçalho CHAVE ESTRANGEIRA (FK)              PCREINFR2060C
PCREINFR2060I          STATUS VARCHAR2(100)                                    Status            OPERACIONAL                        NaN
PCREINFR2060I     CODATIVECON   VARCHAR2(8)                               Codigo CNAE            OPERACIONAL                        NaN
PCREINFR2060I VLRRECBRUTAATIV  NUMBER(12,2)             Valor receita bruta atividade            OPERACIONAL                        NaN
PCREINFR2060I  VLREXCRECBRUTA  NUMBER(12,2)              Valor exclusão receita bruta            OPERACIONAL                        NaN
PCREINFR2060I VLRADICRECBRUTA  NUMBER(12,2)          Valor adicional de receita bruta            OPERACIONAL                        NaN
PCREINFR2060I       VLRBCCPRB  NUMBER(12,2)    Valor base contribuição previdenciaria            OPERACIONAL                        NaN
PCREINFR2060I     VLRCPRBAPUR  NUMBER(12,2) Valor contribuição previdenciaria apurada            OPERACIONAL                        NaN
PCREINFR2060I     VLRPROCESSO  NUMBER(12,2)                         Valor do processo            OPERACIONAL                        NaN
PCREINFR2060I     RETIFICACAO   VARCHAR2(1)      Controle de processo em retificação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*