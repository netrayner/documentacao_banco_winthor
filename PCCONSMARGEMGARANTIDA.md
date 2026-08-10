# 📊 Tabela: PCCONSMARGEMGARANTIDA

### Estrutura de Colunas e Restrições

               Tabela                  Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONSMARGEMGARANTIDA                     MES   VARCHAR2(2)              Mês da consolidação    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSMARGEMGARANTIDA                     ANO   VARCHAR2(4)              Ano da consolidação    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSMARGEMGARANTIDA               CODFILIAL   VARCHAR2(2)                 Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSMARGEMGARANTIDA               CODFORNEC   NUMBER(6,0)             Código do fornecedor    CHAVE PRIMÁRIA (PK)                        NaN
PCCONSMARGEMGARANTIDA                VLRVERBA  NUMBER(18,6)                  Valor em verbas            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA              VLRDESPESA  NUMBER(18,6)               Valor das despesas            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA                VLRCUSTO  NUMBER(18,6)                   Valor do custo            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA          VLRFATURAMENTO  NUMBER(18,6)                Valor faturamento            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA    VLRDESCONTOCOMERCIAL  NUMBER(18,6)         Valor desconto comercial            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA          VLRLIVREDEBITO  NUMBER(18,6)            Valor livre de débito            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA              VLRLIQUIDO  NUMBER(18,6)                    Valor líquido            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA             VLRDESCONTO  NUMBER(18,6)                Valor do desconto            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA              PERCMARGEM  NUMBER(18,6)             Percentual de margem            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA         PERCMARGEMVERBA  NUMBER(18,6)          Percentual margem verba            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA    PERCMARGEMCOMDESPESA  NUMBER(18,6) Percentual da margem com despesa            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA VLRACERTOMARGEMACORDADA  NUMBER(18,6)     Valor acerto margem acordada            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA     PERCMARGEMGARANTIDA  NUMBER(18,6)   Percentual da margem garantida            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA            DATAAPURACAO          DATE     Data de apuração do registro            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA              CODUSUARIO   NUMBER(6,0)                Código do usuário            OPERACIONAL                        NaN
PCCONSMARGEMGARANTIDA                 USUARIO VARCHAR2(100)                  Nome do usuário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*